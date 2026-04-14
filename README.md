# 🧮 UNIVESP - Aritmética Modular Interativa

> **Objeto de Aprendizagem Digital (OAD)** desenvolvido para a disciplina de Elementos de Álgebra da Licenciatura em Matemática da UNIVESP. 

Este projeto é uma ferramenta educacional interativa que traduz conceitos abstratos da álgebra — como aritmética modular, classes de equivalência, anéis e corpos — em uma experiência visual, acessível e gamificada.

---

## 🎯 Objetivo do Projeto
Resolver o desafio da Semana 1 ("Aritmética Modular e as Classes de Equivalência") não apenas entregando as respostas, mas criando um ambiente onde o aluno possa **explorar, testar e visualizar** as propriedades algébricas em tempo real.

## ✨ Principais Funcionalidades

- **🖩 Calculadora de Redução Modular:** Explica passo a passo o algoritmo da divisão euclidiana, mostrando como dois números são somados e reduzidos a uma classe de equivalência com a analogia do "relógio".
- **📊 Tábuas de Cayley Dinâmicas:** Geração instantânea de tabelas de adição e multiplicação para módulos de 2 a 12. Identifica visualmente **Divisores de Zero**, ajudando a diferenciar Anéis de Corpos.
- **🎮 Modo Desafio (Gamificado):** Transforma a Tábua de Cayley em um exercício interativo. O aluno preenche as células vazias e recebe feedback imediato via Modal.
- **🧠 Rigor Algébrico:** O sistema é inteligente o suficiente para aceitar **respostas congruentes** no Modo Desafio (ex: no módulo 3, digitar `5` é aceito como correto para a classe `\bar{2}`).
- **🌓 Dark Mode Automático:** Suporte nativo a tema escuro/claro baseado na preferência do sistema do usuário.
- **♿ Acessibilidade (a11y):** - Navegação 100% funcional via teclado (`Tab` e `Enter`) no Modo Desafio.
  - Avisos dinâmicos para leitores de tela utilizando `aria-live`.
  - Tooltips adaptados para interfaces *touch* em dispositivos móveis.
- **📱 Totalmente Responsivo:** Layout adaptável com rolagem horizontal suave (`overflow-x`) para tabelas matemáticas em telas pequenas.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído focando em performance e compatibilidade, sem dependência de frameworks pesados:

- **HTML5 & CSS3:** Estrutura semântica e estilização moderna com CSS Variables (Custom Properties).
- **JavaScript (ES6+):** Lógica matemática, manipulação do DOM e interatividade (Vanilla JS).
- **[MathJax 3](https://www.mathjax.org/):** Renderização de fórmulas e notações matemáticas (LaTeX) de alta qualidade direto no navegador.
- **[Font Awesome](https://fontawesome.com/):** Ícones vetoriais para UI/UX.

---

👨‍🏫 Autor
Desenvolvido com 💡 e ☕ por Sérgio Eric.

🎓 Licenciando em Matemática (UNIVESP)

📸 Instagram: @prof.sergio.eric.matematica

---

📜 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para utilizá-lo, modificá-lo e aplicá-lo em suas aulas ou estudos!
   
