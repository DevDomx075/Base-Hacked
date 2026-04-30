# Base-Hacked
🤖 Base simples e funcional pronta para uso, 100% editavél.



«Bot de WhatsApp com, comandos básicos e sistema modular.»

---

📌 SOBRE O PROJETO

Este é um bot de WhatsApp desenvolvido em Node.js usando a biblioteca Baileys.
Possui uma estrutura modular, simples de usar e fácil de personalizar.

---

⚙️ FUNCIONALIDADES

- 📲 Conexão via QR Code ou Pairing Code
- 🧩 Sistema modular de comandos
- 👥 Comandos básicos para grupos e usuários
- 🔧 Estrutura fácil de editar e expandir

---

📥 INSTALAÇÃO NO TERMUX

🔹 Passo a passo

pkg update && pkg upgrade -y
pkg install git nodejs -y

git clone https://github.com/SEU-USUARIO/Base-Hacked.git
cd Base-Hacked

npm install
node index.js

---

⚡ Instalação rápida (1 comando)

pkg update && pkg upgrade -y && pkg install git nodejs -y && git clone https://github.com/SEU-USUARIO/Base-Hacked.git && cd Base-Hacked && npm install && node index.js

---

🔑 CONEXÃO DO BOT

Ao iniciar o bot:

- 📷 Escaneia o QR Code
  ou
- 🔢 Usa o código de pareamento

---

⚙️ CONFIGURAÇÃO

Arquivo principal de configuração:

config.js

✏️ Exemplo de configuração:

module.exports = {
  nomeBot: "ˢʸˢᵗᵉᵐHACKED BOT",
  prefixo: "!",
  dono: "258858123028"
}

---

📁 ESTRUTURA DE COMANDOS

Para adicionar novos comandos, vá até:

src/commands/

📂 Organização:

- "adm" → comandos administrativos
- "geral" → comandos gerais
- "dono" → comandos exclusivos do dono
- "jogos" → comandos de diversão

---

🚀 COMANDOS BÁSICOS

!menu
!ping
!info

---

⚠️ IMPORTANTE

- ❌ Não é necessário subir "node_modules" no GitHub
- ✔ Sempre executar "npm install" após clonar
- ✔ Projeto pode ser modificado livremente

---

👨‍💻 AUTOR

DAÚDO OMAR
📞 858123028
