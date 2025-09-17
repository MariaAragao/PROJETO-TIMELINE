# Projeto Timeline - React + TypeScript + Vite

![React Logo](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript Logo](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite Logo](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## 📌 Sobre o Projeto

O **Projeto Timeline** é uma aplicação web desenvolvida com **React**, **TypeScript** e **Vite**, criada durante um curso da Rocketseat.  
O projeto simula uma rede social simples, onde é possível:

- Publicar posts;
- Aplaudir posts (like);
- Deletar posts.

Todos os estilos foram implementados utilizando **CSS Modules**, garantindo um estilo modular e isolado para cada componente.  

O objetivo do projeto é reforçar conceitos de:

- Componentização em React;
- Tipagem com TypeScript;
- Gerenciamento de estado local;
- Reutilização de componentes;
- Boas práticas em CSS modular.

---

## 🗂 Estrutura do Projeto

```text
src/
 ├─ assets/                # Arquivos de mídia e imagens
 ├─ components/            # Componentes reutilizáveis
 │   ├─ Avatar.tsx
 │   ├─ Comment.tsx
 │   ├─ Header.tsx
 │   ├─ Post.tsx
 │   └─ Sidebar.tsx
 ├─ App.tsx
 ├─ main.tsx
 └─ global.css
```
---

⚙ Tecnologias Utilizadas
React
TypeScript
Vite
CSS Modules

---

🚀 Funcionalidades:

Criar post: O usuário pode adicionar novos posts, inserindo conteúdo e autor.
Aplaudir post: O usuário pode clicar no botão de aplauso para aumentar o contador de likes.
Deletar post: O usuário pode remover posts publicados da timeline.

---

💻 Como Rodar o Projeto
Clone este repositório:
git clone https://github.com/SEU_USUARIO/PROJETO-TIMELINE.git
Acesse a pasta do projeto:
cd PROJETO-TIMELINE
Instale as dependências:
npm install
Inicie o servidor de desenvolvimento:
npm run dev
Abra o navegador em http://localhost:5173

---

📐 Estilo e Componentização:

Cada componente possui seu próprio arquivo de CSS modular (.module.css) garantindo que:
Estilos não vazem para outros componentes;
Facilita manutenção e reaproveitamento de código;
Possibilita temas e personalizações futuras.

---

📝 Licença
Este projeto está sob a licença MIT.

