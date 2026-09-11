# 🚀 Desafio de Linha do Tempo e Paradigmas da Programação

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

---

## 📌 O que é?

Este projeto é uma aplicação web interativa desenvolvida como resposta a um desafio prático de desenvolvimento web. O objetivo principal é apresentar uma visão cronológica e conceitual da evolução das linguagens e paradigmas de programação — desde os modelos imperativos e orientados a objetos clássicos até a era da Engenharia Assistida por Inteligência Artificial e Agentes Autônomos (2022–2026).

**Objetivos alcançados:**
* Apresentar marcos históricos e avanços estruturais da programação.
* Demonstrar a transição entre paradigmas (Imperativo, Declarativo, Reativo e Tipagem Estática Moderna).
* Desenvolver uma interface semântica, responsiva e visualmente moderna utilizando CSS puro.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo (`<header>`, `<main>`, `<article>`, `<footer>`).
* **CSS3:** Estilização modular, flexbox, CSS grid, variáveis e responsividade.
* **Git:** Controle de versão.
* **GitHub & GitHub Pages:** Hospedagem do código-fonte e deploy da aplicação.

---

## 🚀 Execução

Siga as instruções abaixo para clonar e rodar o projeto localmente em sua máquina.

## 🏗️ Funcionamento

A estrutura da aplicação foi dividida em componentes semânticos e organizada para facilitar a leitura e manutenção do código:
index.html: Arquivo principal contendo a marcação semântica dividida em Seção de Paradigmas, Marcos Tecnológicos e a Linha do Tempo da Programação.
Style.css: Folha de estilo responsável pela identidade visual do projeto.
Variáveis CSS: Centralização de cores, fontes e espaçamentos no topo do arquivo.
Layout Responsivo: Ajuste automático dos cards para diferentes tamanhos de tela.
Componentização dos Cards: Estilização isolada para .concept-card e .timeline-card, garantindo alinhamento centralizado dos títulos e tags.

## 🤖 Documentação do Uso de Inteligência Artificial

Para otimizar o desenvolvimento, refatoração de código e estruturação da documentação, utilizou-se o modelo Gemini (Google AI) como co-piloto:

Prompts empregados:
HTML
Crie uma Landing Page responsiva com a estrutura completa de uma página sobre o Tema Evolução no Desenvolvimento
de Software nos últimos 20 anos.
Utilize HTML semântico, empregue <main>, <section>, <article> no lugar de <div> sempre que adequado.
Utilize as Seções para a Página:
Header: Marca fictícia "EvoluCode" e menu com links internos (<nav>).
Hero Section: Uma mensagem impactante e real sobre a mudança na engenharia de software "Da Programação Monolítica à Co-criação com IA.
Seção 1: Linguagens e Paradigmas (O Custo da Abstração)
Como a indústria migrou de linguagens imperativas para linguagem declarativa e as abstrações de alto nível.
Indicar marco de linguagem e paradigma e relacionar maiores desafios de cada linguagem e paradigma.
Seção 2: Arquiteturas de Distribuição (Alcance e Escala).
Descreva para cada arquitetura do período o alcance e a escala de desenvolvimento.
Seção 3: A Mudança de Raciocínio Lógico (COMO desenvolvemos)
Divida o conteúdo por transformações lógicas (linguagens, arquiteturas, paradigmas e alcances), a cada 5 período de 5 anos, utilize 
fontes públicas e confiáveis.
Crie uma seção contendo 4 cards. Cada card com um título (<h2>) referente ao período de cada 5 anos da linha do tempo da evolução 
dos últimos 20 anos: 2007 a 2011, 2012 a 2016, 2017 a 2021, 2022 a 20026. Lembro que o período considera o ano inicial e o ano final, 
no caso de 2026, até o mês de agosto, visto que estamos em setembro. Cada card deve possuir um parágrafo (<p>) com o resumo 
da mudança mais relevante daquele período.
Seção 4: Tabela Comparativa (2007 vs 2026) - crie Tabela HTML que compare conceitos como Hospedagem, Linguagem Predominante no Front-end, 
Gerenciamento de Estado e Ferramentas de Desenvolvimento.
Crie o arquivo index.html. 

CSS
Crie um arquivo style.css para estilizar o projeto Desafio gerado.
Empregue a psicologia das cores. 
Utilize o tema Visual "Code Editor". Use fundo estilo editor de código (como tom VS Code ou Dracula) para os cards, utilize 
fontes monospace (Consolas, Fira Code) nos títulos.
Badges/Tags: Crie classes no CSS para simular "tags de linguagens" (<span class="tag">TypeScript</span>) decorativas ao redor das 
descrições.
Organize os 4 cards lado a lado, utilize o Flexbox, adicione espaçamento, margem, bordas e imagem referente ao marco histórico
destacado no parágrafo do card. ‌Insira a tag <img> dentro da estrutura de cada card, posicione-a no topo do container do card.
‌Adicione obrigatoriamente o atributo alt descritivo em cada imagem para garantir a acessibilidade para leitores de tela.
‌Defina o atributo loading="lazy" para otimizar o carregamento.
‌Garanta que as imagens sejam responsivas e preencham a largura total do card sem distorcer 
‌Garanta que os cards ajustem o layout suavemente em dispositivos móveis, tablets e desktops.
‌‌Utilize URLs de imagens de exemplo de bancos de imagens gratuitos (como Unsplash, Pixabay ou Pexels) ou referências locais 
sintaticamente corretas.
Mantenha foco em boas práticas de UI/UX, acessibilidade e responsividade.
Adicione comentários no CSS explicando as principais propriedades utilizadas. 
Não altere o HTML, não utilize JS.
Crie o arquivo style.css.
Adicione imagens aos cards da aplicação, mantendo o foco em boas práticas de UI/UX, acessibilidade e responsividade.
Instruções de Implementação:
‌Estrutura HTML/JSX:
‌Insira a tag <img> dentro da estrutura de cada card, posicionando-a no topo do container do card.
‌Adicione obrigatoriamente o atributo alt descritivo em cada imagem para garantir a acessibilidade para leitores de tela.
‌Defina o atributo loading="lazy" para otimizar o carregamento.
‌Estilização CSS:
‌Garanta que as imagens sejam responsivas e preencham a largura total do card sem distorcer 
‌Garanta que os cards ajustem o layout suavemente em dispositivos móveis, tablets e desktops.
‌Fontes de Imagem:
‌Utilize URLs de imagens de exemplo de bancos de imagens gratuitos (como Unsplash, Pixabay ou Pexels) ou referências locais 
sintaticamente corretas.

README
Crie o arquivo README.md completo, profissional, bem formatado em Markdown para o projeto Desafio gerado. 
Utilize ícones/emojis e blocos de código para tornar a leitura agradável.
Siga a estrutura das seções abaixo:
O que é?
‌Uma breve introdução sobre o projeto, explicando o seu propósito principal, o tema relevante de que ele trata, os objetivos alcançados.
‌Tecnologias Utilizadas
‌Liste as linguagens, frameworks, bibliotecas e ferramentas utilizadas no desenvolvimento (ex: HTML5, CSS3, Git, GitHub, etc.).
‌Execução
‌Instruções detalhadas e claras para clonar e rodar a aplicação localmente:
‌Pré-requisitos.
‌Passo a passo de comandos no terminal:
‌Clonar o repositório (git clone ...).
‌Entrar na pasta do projeto (cd ...).
‌Instalar as dependências (npm install ou yarn).
‌Executar o projeto em modo de desenvolvimento (npm run dev ou npm start).
‌Funcionamento
‌Uma explicação detalhada sobre o funcionamento da aplicação, arquitetura/estrutura dos componentes (ex: global.css, Header, Main, 
Footer), como a estilização/módulos foram organizados.
Onde Acessar?
‌Espaço para o link do projeto publicado (Deploy ex: Vercel, Netlify, GitHub Pages).
‌Quem Desenvolveu?
‌Seção dedicada a autora/desenvolvedora do projeto, com nome, link para o perfil do GitHub e LinkedIn.
Desenvolvedora: Weridiana Maria & Gemini
GitHub (https://github.com/Weridiana)
Linkedin (www.linkedin.com/in/weridianamaria)

## 👩‍💻 Quem Desenvolveu?
Desenvolvido por Weridiana Maria em colaboração com o Gemini (Google AI).

GitHub: https://github.com/Weridiana
LinkedIn: www.linkedin.com/in/weridianamaria

### 📋 Pré-requisitos
* Um navegador web atualizado (Google Chrome, Firefox, Edge, Safari).
* Git instalado em sua máquina (opcional, para clonar via terminal).

### 💻 Passo a passo no terminal

1. **Clonar o repositório:**
```bash
git clone [https://github.com/Weridiana/Desafio1_EvoluCode.git](https://github.com/Weridiana/Desafio1_EvoluCode.git)



