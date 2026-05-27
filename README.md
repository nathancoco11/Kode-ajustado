# 🚀 Kode - O Universo da Programação ao seu Alcance

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![Versão](https://img.shields.io/badge/Vers%C3%A3o-2.0.4-blue)

E aí, dev! Seja bem-vindo ao **Kode**! 👋 

Criamos essa plataforma web para ser um guia prático, visual e super direto para quem quer começar a entender o mundo da tecnologia. O nosso objetivo é centralizar tudo o que você precisa saber sobre o mercado de trabalho, as carreiras do momento e as tecnologias mais bombadas, dando aquele empurrãozinho inicial para quem quer aprender a programar.

---

## 🖥️ O que tem no projeto?

O site foi feito com um visual moderno (estilo *Cyberpunk Dark Mode*) e navegação bem fluida. Separamos o projeto em algumas páginas principais:

* **Página Inicial (`inicio.html`):** A nossa Landing Page! Ela tem um visual bem limpo, um botão chamativo para começar a jornada e efeitos visuais leves para prender a atenção do usuário logo de cara.
* **Sobre a Programação (`sobre.html`):** Uma página feita em formato de blocos (cards) com efeito de desfoque de fundo (*blur*). Ela explica de um jeito simples o que é programação, onde ela está no nosso dia a dia e por que vale a pena aprender.
* **Linguagens Populares (`linguagens.html`):** Um catálogo com as principais linguagens do mercado (HTML/CSS, JS, Python, Java, C#, PHP). Quando você passa o mouse por cima dos blocos, eles dão um zoom de leve (animação interativa).
* **Áreas de Atuação (`areas.html`):** Uma seção que mostra os caminhos profissionais que você pode seguir: Front-End, Back-End, Full-Stack, Inteligência Artificial e Cyber Security.

---

## 🔮 Recursos Avançados do Nosso Sistema

Para deixar a plataforma ainda mais completa e com cara de sistema profissional, nossa equipe desenvolveu as seguintes funções:

### 1. Sistema de Login Completo
* Criamos uma área restrita para o estudante entrar com sua conta e salvar o progresso nas trilhas de estudo.
* O formulário valida as informações na hora e usa o `LocalStorage` para manter o usuário conectado mesmo se ele fechar o navegador.

### 2. Quiz Interativo (`quiz.html`)
* Desenvolvemos um teste de orientação vocacional super legal com 10 perguntas para descobrir o perfil do usuário.
* O sistema roda um algoritmo que lê as respostas e diz qual área combina mais com você (ex: se você prefere a parte visual, ele sugere a rota de Front-End!).

### 3. Sistema de Busca e Filtros por Tags
* Na página de Linguagens, você não precisa ficar procurando de um em um. Adicionamos filtros por tags como `#Web`, `#Mobile`, `#DataScience` ou `#Games` para você achar o que quer na hora.


---

## 🛠️ Tecnologias que Usamos

Focamos em usar tecnologias puras e direto na fonte, sem complicar:

* **HTML5:** Para construir a estrutura organizada e semântica de todas as páginas.
* **CSS3:** Para deixar o site bonito, usando Flexbox e Grid (para alinhar as coisas), gradientes de cor modernos e as *Media Queries* (para o site caber no celular).
* **Google Fonts:** Importamos as fontes *Roboto* e *Poppins* direto da internet para deixar os textos bem modernos.

---

## 📁 Organização das Pastas

Aqui está como organizamos os arquivos do repositório para você se achar:

```text
├── inicio.html          # Tela de entrada (Landing Page)
├── sobre.html           # Página que explica a programação
├── sobre.css            # Estilos da página Sobre
├── linguagens.html      # Nosso catálogo de tecnologias
├── linguagens.css       # Layout e responsividade do catálogo
├── areas.html           # Página com as carreiras da tecnologia
├── areas.css            # Estilos dos cartões de carreiras
└── ImG/                 # Pasta com as fotos e logos das linguagens
    ├── HTML-CSS.png
    ├── JS.png
    ├── PYTHON.png
    ├── JAVA.webp
    ├── C.png
    └── PHP.svg
