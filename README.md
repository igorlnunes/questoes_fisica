# ⚛️ Física Genial: Exercícios de Física com Inteligência Artificial para o Ensino Médio 🚀

**Desvende os mistérios da física de forma interativa e inteligente!**

## 💡 Sobre o Projeto

Este projeto inovador utiliza a inteligência artificial do Gemini para gerar exercícios de física sob demanda, focados nos principais tópicos do Ensino Médio: Cinemática, Ondulatória e Dinâmica. Ideal para estudantes que buscam praticar e aprofundar seus conhecimentos, e para educadores que desejam recursos dinâmicos e personalizados.

Com uma interface simples e intuitiva, o usuário pode selecionar o tópico e o nível de dificuldade desejado e, instantaneamente, receber uma questão inédita. Mas a jornada de aprendizado não para por aí! Cada questão vem acompanhada da **alternativa correta** para uma verificação rápida e de uma **resolução detalhada**, passo a passo, utilizando a clareza do texto e a precisão da notação LaTeX.

## ✨ Funcionalidades Principais

* **Geração Dinâmica de Questões:** Crie exercícios únicos sobre Cinemática, Ondulatória e Dinâmica, com o poder do Gemini.
* **Seleção de Dificuldade:** Escolha entre os níveis Iniciante, Intermediário e Avançado para adequar o desafio ao seu nível de aprendizado.
* **Resposta Direta:** Verifique sua compreensão com a indicação imediata da alternativa correta.
* **Resolução Detalhada:** Desvende o passo a passo da solução, com explicações claras e fórmulas em LaTeX para um aprendizado completo.
* **Interface Amigável:** Uma experiência de usuário simples e direta, focada na praticidade do estudo.

## 🛠️ Tecnologias Utilizadas

* **Backend:**
    * **Python:** A linguagem de programação principal para a lógica do backend.
    * **Flask:** Um microframework web para construir a API que serve o frontend.
    * **Google AI SDK (Gemini):** A inteligência artificial por trás da geração de questões e resoluções.
    * **Flask-CORS:** Para habilitar o acesso à API de diferentes origens (o frontend).
* **Frontend:**
    * **HTML:** Para a estrutura da página web.
    * **CSS:** Para a estilização e o layout da interface.
    * **JavaScript:** Para a interatividade e a comunicação com o backend.
    * **`fetch` API:** Para realizar as requisições HTTP ao backend.
    * **`polyfill.io`:** Para garantir compatibilidade com navegadores mais antigos.
    * **MathJax:** Para a renderização elegante de notações matemáticas em LaTeX.
* **Ambiente de Desenvolvimento e Testes:**
    * **Google Colaboratory (Colab):** Plataforma utilizada para o desenvolvimento e testes do backend.

## 🚀 Como Utilizar

1.  **Backend (Google Colab - para desenvolvedores):**
    * Abra o notebook Python no Google Colab (`backend/app.ipynb` ou similar).

2.  **Frontend (Navegador):**
    * Abra o arquivo `frontend/index.html` no seu navegador web.
    * Selecione a **Dificuldade** desejada (Iniciante, Intermediário, Avançado).
    * Selecione o **Tópico** de seu interesse (Cinemática, Ondulatória, Dinâmica).
    * Clique no botão "Gerar Exercício".
    * A questão gerada, a alternativa correta e a resolução detalhada serão exibidas na tela.

## 🧑‍💻 Para Desenvolvedores

Se você deseja contribuir ou entender melhor o código:

* **Backend (`backend/app.py`):** Contém a lógica principal do Agente que utiliza o Gemini para gerar as questões e resoluções. As funções `gerar_enunciado_alternativas_resposta_tool` e `gerar_resolucao_tool` são as peças chave. A função `obter_questao_e_resolucao` orquestra a interação com o Agente.
* **Frontend (`frontend/index.html` e `frontend/script.js`):** O `index.html` define a estrutura da página e o `script.js` contém o JavaScript para capturar as seleções do usuário e fazer a chamada à API do backend, além de exibir os resultados.

## 🚀 Próximos Passos e Melhorias

* Adicionar mais tópicos da física para o Ensino Médio.
* Implementar diferentes formatos de questões (discursivas, verdadeiro/falso).
* Permitir a personalização do número de alternativas.
* Criar um sistema de feedback para avaliar a qualidade das questões e resoluções.
* Integrar um sistema de acompanhamento do progresso do usuário.
* Otimizar a comunicação entre o frontend e o backend.
* Considerar o deploy do backend em uma plataforma mais robusta para acesso contínuo.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para relatar bugs ou sugerir melhorias, e pull requests com novas funcionalidades ou correções.

## 📄 Licença

[Insira aqui a licença do seu projeto, por exemplo, MIT License]

## 🎉 Divirta-se aprendendo física de uma maneira totalmente nova! 🎉