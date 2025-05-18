# Gerador de Questões de Física com Resolução

Este projeto é um conjunto de scripts Python que utilizam o modelo Gemini para gerar questões de física de múltipla escolha e suas respectivas resoluções passo a passo. Ele foi desenvolvido para auxiliar na criação de materiais didáticos e avaliações para estudantes do ensino médio.

## Exemplo de Uso

![Texto alternativo para o GIF](assets/exemplo.gif)

1.  Execute as células do Colab sequencialmente.
2.  Utilize os dropdowns para selecionar o tópico e a dificuldade da questão.
3.  Clique no botão "Gerar Questão" para gerar a questão.
4.  Clique em "Revelar Resposta" para ver a resposta correta.
5.  Clique em "Mostrar Resolução" para ver a resolução detalhada.

## Funcionalidades

* **Geração de Questões:** O script permite gerar questões de física especificando o tópico (Cinemática, Ondulatória, Dinâmica) e a dificuldade (Iniciante, Intermediário, Avançado).
* **Formato de Saída:** As questões são geradas em formato JSON, contendo o enunciado, as opções de múltipla escolha (A, B, C, D) e a resposta correta.
* **Resolução Detalhada:** Para cada questão gerada, o script também pode gerar uma resolução detalhada, explicando o passo a passo da solução, incluindo fórmulas e cálculos em notação LaTeX.
* **Interface Interativa:** O projeto inclui widgets interativos (dropdowns e botões) para facilitar a seleção de tópicos, dificuldades e a geração das questões e resoluções.

## Como Funciona

O projeto é estruturado em células de um Colab do Google, organizado da seguinte forma:

1.  **Configuração e Importações:**
    * Configura a API Key do Google Gemini.
    * Importa as bibliotecas necessárias (google.genai, ipywidgets, etc.).
2.  **Funções Auxiliares:**
    * `to_markdown(text)`: Formata o texto para exibição em Markdown.
    * `display_markdown_with_mathjax(markdown_string)`: Exibe texto Markdown com suporte a MathJax para renderização de fórmulas.
3.  **Funções de Geração:**
    * `gerar_enunciado_alternativas_resposta(topico, dificuldade)`: Gera a questão de física.
    * `gerar_resolucao_estruturada(enunciado, resposta_correta)`: Gera a resolução da questão.
4.  **Widgets e Interação:**
    * Cria os widgets de dropdown (para tópico e dificuldade) e botões (para gerar questão, revelar resposta e mostrar resolução).
    * Define as funções que tratam os eventos de clique dos botões, controlando o fluxo da aplicação e a exibição dos resultados.
5.  **Exibição dos Widgets:**
    * Exibe os widgets na interface do Colab.

## Requisitos

* Conta no Google Colab
* API Key do Google Gemini configurada no Colab (User Data)
* Conhecimento básico de Python

## Instalação

1.  Abra o Colab do Google.
2.  Crie um novo notebook ou faça upload dos arquivos do projeto.
3.  Configure sua API Key do Gemini no Colab usando User Data.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorar o projeto.

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](License.md) para detalhes.