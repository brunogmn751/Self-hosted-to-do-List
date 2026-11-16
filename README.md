# ✅ To-do List

A to-do list made with plain HTML, CSS and JavaScript, built to practice JavaScript fundamentals while still caring about how the page looks. It is self-hosted on my own home server.

🔗 **Live site:** https://to-do.b-azevedo.dev

## ✨ Features

- Add tasks with the **Add** button or the **Enter** key (empty tasks are ignored)
- Mark a task as done with the checkbox (the text gets struck through) and unmark it again
- Delete a task with the close icon
- Counter of done and incomplete tasks, updated on every change
- Tasks are saved in the browser's `localStorage`, so the list is still there after a reload
- Responsive layout with breakpoints at 1100px, 767px and 480px

## 🛠️ Technologies

- **HTML**
- **CSS**: custom properties (CSS variables), Flexbox, Grid, native CSS nesting and media queries
- **JavaScript** (no frameworks): DOM manipulation, events, `localStorage` with `JSON.stringify`/`JSON.parse`

## 🖥️ Hosting

The site runs on my own self-hosted home server, not on a hosting platform:

- **Server:** ZimaOS, with the containers managed through Portainer
- **Web server:** an `nginx:alpine` Docker container serving the static files
- **Public access:** my own domain, exposed through a **Cloudflare Tunnel**, so no router port has to be opened

## 📁 Structure

```
├── index.html   # page structure
├── style.css    # styles and responsive layout
├── script.js    # task logic and localStorage persistence
└── images/      # page and close icons
```

---

# Em Português

# ✅ Lista de Tarefas

Lista de tarefas feita com HTML, CSS e JavaScript puro, criada para praticar os fundamentos de JavaScript sem deixar de lado o visual da página. O site fica hospedado no meu próprio servidor doméstico.

🔗 **Site no ar:** https://to-do.b-azevedo.dev

## ✨ Funcionalidades

- Adicionar tarefas pelo botão **Add** ou pela tecla **Enter** (tarefas vazias são ignoradas)
- Marcar uma tarefa como concluída pela caixa de seleção (o texto fica riscado) e desmarcar depois
- Excluir uma tarefa pelo ícone de fechar
- Contador de tarefas concluídas e pendentes, atualizado a cada mudança
- As tarefas ficam salvas no `localStorage` do navegador e continuam lá depois de recarregar a página
- Layout responsivo, com breakpoints em 1100px, 767px e 480px

## 🛠️ Tecnologias

- **HTML**
- **CSS**: variáveis CSS, Flexbox, Grid, aninhamento nativo de CSS e media queries
- **JavaScript** (sem frameworks): manipulação do DOM, eventos, `localStorage` com `JSON.stringify`/`JSON.parse`

## 🖥️ Hospedagem

O site roda no meu próprio servidor doméstico (self-hosted), e não numa plataforma de hospedagem:

- **Servidor:** ZimaOS, com os containers gerenciados pelo Portainer
- **Servidor web:** um container Docker `nginx:alpine` servindo os arquivos estáticos
- **Acesso público:** domínio próprio, exposto por um **Cloudflare Tunnel**, sem precisar abrir portas no roteador

Depois acesse http://localhost:8080.

## 📁 Estrutura

```
├── index.html   # estrutura da página
├── style.css    # estilos e layout responsivo
├── script.js    # lógica das tarefas e persistência no localStorage
└── images/      # ícones da página e de fechar
```
