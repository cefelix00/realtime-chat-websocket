# 💬 Chat em Tempo Real com WebSocket

Este é um projeto de **chat em tempo real** criado com **Node.js**, **Express** e **Socket.IO**, que permite múltiplos utilizadores comunicarem instantaneamente através de WebSockets.

O frontend é construído com HTML, CSS e JavaScript puro, oferecendo uma interface simples, funcional e responsiva.

---
<!-- 
## 🖼️ Demonstração

<img src="https://user-images.githubusercontent.com/your-image-preview.gif" alt="Demonstração do chat" width="600"/>

*(Opcional: substitua pelo link de um GIF ou vídeo do projeto rodando)*

--- -->

## 🛠️ Tecnologias Utilizadas

| Camada      | Tecnologias                       |
|-------------|-----------------------------------|
| Backend     | Node.js, Express, Socket.IO       |
| Frontend    | HTML5, CSS3, JavaScript (Vanilla) |
| Comunicação | WebSockets (via Socket.IO)        |

---

## 🚀 Funcionalidades

- Envio de mensagens em tempo real
- Comunicação bidirecional usando WebSocket
- Suporte a múltiplos utilizadores simultaneamente
- Atualização dinâmica da interface sem recarregar a página
- Layout responsivo e minimalista

---

## 📂 Estrutura do Projeto

```
realtime-chat-websocket/
├── client/
│   ├── index.html       # Interface do utilizador
│   ├── style.css        # Estilos da aplicação
│   └── script.js        # Lógica frontend + integração com Socket.IO
├── server/
│   └── index.js         # Servidor Node.js com Express e Socket.IO
├── package.json         # Dependências e scripts
└── README.md            # Documentação do projeto
```

---

## ⚙️ Como Executar Localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/cefelix00/realtime-chat-websocket.git
cd realtime-chat-websocket
```

### 2. Instalar dependências

```bash
npm install
```

### 3. Iniciar o servidor

```bash
node server/index.js
```

### 4. Aceder ao chat

Abre o navegador em:  
👉 `http://localhost:3000`

> 💡 Dica: Abre em duas abas ou navegadores diferentes para testar a troca de mensagens entre utilizadores.

---

## 🔧 Melhorias Futuras (em aberto)

- [ ] Atribuir nomes de utilizador
- [ ] Indicar quando alguém está a escrever ("usuário digitando...")
- [ ] Criar salas de chat (chat rooms)
- [ ] Guardar histórico de mensagens com MongoDB
- [ ] Autenticação simples (login anónimo)
- [ ] Deploy completo (Vercel/Netlify para frontend + Render para backend)

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.  
Sinta-se livre para usar, modificar e compartilhar.

---

## 🤝 Contribuições

Contribuições são muito bem-vindas!  
Se tiveres ideias, melhorias ou bugs para corrigir, abre um [issue](https://github.com/cesaltinofelix/realtime-chat-websocket/issues) ou envia um [pull request](https://github.com/cefelix00/realtime-chat-websocket/pulls).

---

## 👨🏽‍💻 Autor

**Cesaltino Félix**  
👨🏽‍🏫 Engenheiro Informático, Professor e Tutor  
🔐 Interessado em Tecnologia e Cibersegurança  
📧 Email: [cesaltinofelix2000@gmail.com](mailto:cesaltinofelix2000@gmail.com)  
🌐 GitHub: [github.com/cesaltinofelix](https://github.com/cesaltinofelix)  
🌐 LinkedIn: [linkedin.com/in/cesaltino-felix](https://linkedin.com/in/cesaltino-felix)

---
