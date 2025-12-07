# 🤖 YURI BOT - WhatsApp Bot Multifuncional

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-16.x%20%7C%2018.x%20%7C%2020.x-brightgreen?logo=node.js&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/Version-2.5.0-orange)
![Stars](https://img.shields.io/github/stars/MAY0LPHI/bot2teste?style=social)
![Issues](https://img.shields.io/github/issues/MAY0LPHI/bot2teste)

**Um bot avançado para WhatsApp com recursos de automação, inteligência artificial, jogos, mídia e muito mais!** 🚀

[🌟 Funcionalidades](#-funcionalidades) •
[📋 Pré-requisitos](#-pré-requisitos) •
[🚀 Instalação](#-instalação) •
[💻 Como Usar](#-como-usar) •
[⚙️ Configuração](#️-configuração) •
[🤝 Contribuindo](#-contribuindo) •
[📄 Licença](#-licença)

</div>

---

## 📑 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Como Usar](#-como-usar)
- [Configuração](#️-configuração)
- [Comandos Disponíveis](#-comandos-disponíveis)
- [Testes](#-testes)
- [Contribuindo](#-contribuindo)
- [Roadmap](#-roadmap)
- [Licença](#-licença)
- [Contato](#-contato)
- [Créditos](#-créditos)

---

## 📖 Sobre o Projeto

O **YURI BOT** é um bot completo para WhatsApp desenvolvido em Node.js, baseado na biblioteca `@cognima/walib` (Baileys). Ele oferece uma ampla gama de funcionalidades, desde comandos de entretenimento e jogos até integração com APIs de inteligência artificial, ferramentas de mídia, tradução e muito mais.

Este bot foi criado para facilitar a automação de tarefas no WhatsApp, proporcionando interação dinâmica em grupos e conversas privadas com recursos modernos e personalizáveis.

### 🎯 Objetivo

Automatizar interações no WhatsApp através de comandos, integrações com APIs externas e recursos de IA, oferecendo uma experiência rica e interativa para usuários e administradores de grupos.

---

## ✨ Funcionalidades

### 🎮 **Entretenimento e Jogos**
- Jogo da Velha multiplayer
- Quiz de animais e enigmas
- Jogos de namoro e interação
- Akinator (jogo de adivinhação)
- Gartic e outros jogos em grupo

### 🤖 **Inteligência Artificial**
- Integração com Gemini AI para conversas inteligentes
- Geração de imagens com Prodia e KarloAI
- Reconhecimento de música (Shazam/ACRCloud)
- OCR (Tesseract) para extração de texto de imagens
- Tradução automática em múltiplos idiomas

### 🎵 **Mídia e Conteúdo**
- Download de vídeos e músicas do YouTube
- Pesquisa e download do SoundCloud
- Conversão de áudio para texto (AssemblyAI)
- Criação e edição de stickers/figurinhas
- Conversão de formatos (WebP, GIF, MP4)
- Remoção de fundo de imagens

### 🛡️ **Administração de Grupos**
- Anti-spam e filtros de conteúdo
- Sistema de avisos e banimentos
- Detecção de novos admins e membros
- Sistema de boas-vindas personalizável
- Controle de mensagens deletadas
- Sistema de níveis e XP

### 🔧 **Utilidades**
- Informações de clima e localização
- Pesquisas no Google
- Geração de QR codes
- Encurtador de links
- Calculadora e conversores
- Sistema de lembretes e anotações

### 💎 **Recursos Premium**
- Comandos exclusivos para usuários premium
- Limite de uso estendido
- Prioridade em processamento
- Acesso antecipado a novas funcionalidades

---

## 🛠️ Tecnologias Utilizadas

O projeto utiliza uma stack moderna de JavaScript/Node.js com as seguintes tecnologias principais:

| Tecnologia | Descrição | Versão |
|------------|-----------|--------|
| **Node.js** | Runtime JavaScript | 16.x / 18.x / 20.x |
| **@cognima/walib** | Biblioteca para WhatsApp Web | latest |
| **Axios** | Cliente HTTP | 0.21.1 |
| **FFmpeg** | Processamento de áudio/vídeo | 2.1.2 |
| **Cheerio** | Web scraping | 1.0.0-rc.12 |
| **Tesseract.js** | OCR (reconhecimento de texto) | 5.1.0 |
| **Jimp** | Manipulação de imagens | 0.16.13 |
| **Moment.js** | Manipulação de datas | - |
| **AssemblyAI** | Transcrição de áudio | 2.0.2 |
| **Google Translate API** | Tradução automática | 9.2.0 |

### 📦 Outras Dependências Importantes
- **chalk** e **colors**: Estilização de terminal
- **qrcode-terminal**: Geração de QR code
- **crypto-js**: Criptografia
- **archiver**: Compressão de arquivos
- **ytdl**: Download de vídeos do YouTube

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter os seguintes requisitos instalados em seu sistema:

### **Obrigatório:**
- **Node.js** (versão 16.x ou superior) - [Download](https://nodejs.org/)
- **Git** - [Download](https://git-scm.com/)
- **FFmpeg** - [Download](https://ffmpeg.org/)

### **Recomendado:**
- **Tesseract OCR** - Para reconhecimento de texto em imagens
- **ImageMagick** - Para manipulação avançada de imagens
- **Conta no WhatsApp** - Para conectar o bot

### **Sistema Operacional:**
- ✅ Linux (Ubuntu, Debian, Arch, etc.)
- ✅ Windows (10/11 com WSL ou nativo)
- ✅ macOS
- ✅ Termux (Android)

---

## 🚀 Instalação

### **Método 1: Instalação Padrão (Linux/macOS/Windows)**

```bash
# 1. Clone o repositório
git clone https://github.com/MAY0LPHI/bot2teste.git
cd bot2teste

# 2. Instale as dependências
npm install

# 3. Configure as credenciais e settings
# Edite os arquivos em ./settings/ conforme necessário

# 4. Inicie o bot
npm start
```

### **Método 2: Instalação no Termux (Android)**

```bash
# 1. Atualize os pacotes do Termux
pkg update && pkg upgrade -y

# 2. Instale as dependências do sistema
pkg install nodejs-lts git ffmpeg wget tesseract -y

# 3. Clone o repositório
git clone https://github.com/MAY0LPHI/bot2teste.git
cd bot2teste

# 4. Instale as dependências do Node.js
npm install

# 5. Execute o script de inicialização
bash start.sh
```

### **Método 3: Usando o Script de Instalação Automática**

O projeto inclui um script interativo (`start.sh`) que facilita a instalação e execução:

```bash
# Dê permissão de execução ao script
chmod +x start.sh

# Execute o script
bash start.sh

# Ou use npm
npm start
```

O script oferece as seguintes opções:
1. **Instalar dependências** - Instala tudo automaticamente
2. **Iniciar por QR Code** - Conecta via leitura de QR code
3. **Iniciar por código** - Conecta via código de emparelhamento
4. **Apagar QR Code** - Remove dados de sessão para reconectar
5. **Suporte** - Link para contato com o desenvolvedor

---

## 💻 Como Usar

### **Primeira Conexão**

#### **Opção 1: Conexão via QR Code (Padrão)**

```bash
npm start
# ou
bash start.sh
# Selecione a opção [2] - Iniciar a bot por qrcode
```

1. Execute o comando acima
2. Um QR code aparecerá no terminal
3. Abra o WhatsApp no seu celular
4. Vá em **Configurações** > **Aparelhos conectados** > **Conectar um aparelho**
5. Escaneie o QR code exibido no terminal
6. Aguarde a conexão ser estabelecida ✅

#### **Opção 2: Conexão via Código de Emparelhamento**

```bash
bash start.sh sim
# ou
npm start -- sim
# Selecione a opção [3] - Iniciar a bot por código
```

1. Execute o comando acima
2. Digite seu número de telefone quando solicitado (com código do país)
3. Um código de 8 dígitos será exibido
4. No WhatsApp, vá em **Aparelhos conectados** > **Conectar usando número de telefone**
5. Digite o código exibido
6. Conexão estabelecida! 🎉

### **Usando Comandos**

Após conectar o bot, você pode enviar comandos no WhatsApp:

```
# Exemplo de comandos básicos (o prefixo padrão geralmente é /)
/menu          - Exibe todos os comandos disponíveis
/ping          - Testa a velocidade de resposta do bot
/sticker       - Converte imagem/vídeo em figurinha
/play <música> - Baixa música do YouTube
/tradutor      - Traduz textos
/ia <pergunta> - Conversa com inteligência artificial
```

> **Nota:** O prefixo dos comandos pode variar conforme a configuração. Verifique em `./settings/` ou digite `/menu` para ver todos os comandos.

---

## ⚙️ Configuração

O bot possui vários arquivos de configuração localizados no diretório `./settings/`:

### **Principais Configurações**

#### **1. Credenciais de API** (`./settings/creds.json`)

```json
{
  "APIs": {
    "website": "https://api.exemplo.com",
    "apikey": "SUA_API_KEY_AQUI"
  },
  "Gemini": {
    "apikeys": ["sua_chave_gemini_aqui"]
  },
  "Prodia": {
    "apikeys": ["sua_chave_prodia_aqui"]
  }
}
```

#### **2. Configurações Gerais** (`./settings/config.json`)

```json
{
  "OwnerNumber": {
    "value": "+55 65 9306-5507"
  },
  "NomeDoBot": "YURI BOT",
  "prefix": "/"
}
```

### **Variáveis de Ambiente Importantes**

| Variável | Descrição | Exemplo |
|----------|-----------|---------|
| `API_KEY_YURI` | Chave da API principal | `abc123xyz...` |
| `TOKEN_GEMINI` | Token da API Gemini (IA) | `AIza...` |
| `APP_KEY_PRODIA` | Chave para geração de imagens | `prod_...` |
| `API_KEY_TMDB` | The Movie Database API | `tmdb_...` |

### **Arquivos de Dados**

O bot armazena dados em JSON no diretório `./arquivos/database/`:
- **Grupos**: `./arquivos/database/groups/db/`
- **QR Code**: `./arquivos/database/qr-code/`
- **Usuários**: Vários arquivos JSON na raiz de `database/`

> ⚠️ **Importante:** Nunca compartilhe seus arquivos de configuração ou credenciais publicamente!

---

## 📱 Comandos Disponíveis

O bot possui mais de 100 comandos diferentes! Aqui estão alguns exemplos por categoria:

### **🎮 Entretenimento**
- `/jogodavelha` - Inicia jogo da velha
- `/quiz` - Quiz de conhecimentos
- `/akinator` - Jogo de adivinhação
- `/gartic` - Jogo tipo Gartic

### **🎵 Mídia**
- `/play [nome]` - Baixa música do YouTube
- `/ytmp4 [link]` - Baixa vídeo do YouTube
- `/tomp3` - Converte vídeo para áudio
- `/sticker` - Cria figurinha

### **🤖 IA e Utilidades**
- `/ia [pergunta]` - IA conversacional (Gemini)
- `/img [descrição]` - Gera imagens com IA
- `/tradutor [texto]` - Traduz textos
- `/clima [cidade]` - Informações do clima
- `/google [busca]` - Pesquisa no Google

### **🛡️ Admin (apenas administradores)**
- `/ban [@user]` - Banir membro
- `/kick [@user]` - Remover membro
- `/promote [@user]` - Promover a admin
- `/antilink [on/off]` - Ativa/desativa anti-link

> 💡 **Dica:** Digite `/menu` ou `/help` no chat com o bot para ver a lista completa de comandos!

---

## 🧪 Testes

Para testar a conexão do bot:

```bash
# Teste de conexão (modo teste)
npm test

# Este comando executa o arquivo connect.js
# e permite verificar se o bot conecta corretamente
```

### **Testes Manuais**

1. **Teste de Ping:**
   - Envie `/ping` para o bot
   - Deve responder com o tempo de latência

2. **Teste de Mídia:**
   - Envie uma imagem com a legenda `/sticker`
   - O bot deve converter para figurinha

3. **Teste de IA:**
   - Envie `/ia olá, tudo bem?`
   - O bot deve responder com IA

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Se você quer ajudar a melhorar o YURI BOT, siga estas etapas:

### **Como Contribuir:**

1. **Faça um Fork do projeto**
   ```bash
   # Clique no botão "Fork" no GitHub
   ```

2. **Clone seu fork**
   ```bash
   git clone https://github.com/SEU_USUARIO/bot2teste.git
   cd bot2teste
   ```

3. **Crie uma branch para sua feature**
   ```bash
   git checkout -b feature/minha-nova-feature
   ```

4. **Faça suas alterações e commit**
   ```bash
   git add .
   git commit -m "feat: adiciona nova funcionalidade X"
   ```

5. **Push para o GitHub**
   ```bash
   git push origin feature/minha-nova-feature
   ```

6. **Abra um Pull Request**
   - Acesse seu fork no GitHub
   - Clique em "Compare & pull request"
   - Descreva suas alterações detalhadamente

### **Padrões de Commit**

Seguimos o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/):

- `feat:` - Nova funcionalidade
- `fix:` - Correção de bug
- `docs:` - Mudanças na documentação
- `style:` - Formatação, ponto e vírgula, etc
- `refactor:` - Refatoração de código
- `test:` - Adição ou correção de testes
- `chore:` - Atualizações de build, configs, etc

### **Reportando Bugs**

Encontrou um bug? [Abra uma issue](https://github.com/MAY0LPHI/bot2teste/issues) com:
- Descrição clara do problema
- Passos para reproduzir
- Comportamento esperado vs. atual
- Screenshots (se aplicável)
- Versão do Node.js e sistema operacional

---

## 🗺️ Roadmap

Planos futuros para o YURI BOT:

- [ ] 🌐 Suporte multi-idiomas completo
- [ ] 📊 Dashboard web para gerenciamento
- [ ] 🔐 Sistema de autenticação em dois fatores
- [ ] 🎨 Temas personalizáveis para mensagens
- [ ] 📈 Sistema de analytics e estatísticas
- [ ] 🔌 Sistema de plugins para extensões
- [ ] 💾 Backup automático de dados
- [ ] 🚀 Performance otimizada e cache avançado
- [ ] 📱 Suporte para WhatsApp Business API
- [ ] 🤝 Integração com Discord, Telegram, etc.

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

```
MIT License

Copyright (c) 2025 Yuri Modz / MAY0LPHI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[...]
```

---

## 📞 Contato

### 👤 Autor Original
**Yuri Modz**
- 📱 WhatsApp: [+55 65 9306-5507](https://wa.me/556593065507)
- 🌐 Website: [yuribot.xyz](http://yuribot.xyz/docs)
- 💻 GitHub: [@YuriModz](https://github.com/YuriModz/Yuri-Bot)

### 👥 Mantenedor do Fork
**MAY0LPHI**
- 💻 GitHub: [@MAY0LPHI](https://github.com/MAY0LPHI)
- 📦 Repositório: [bot2teste](https://github.com/MAY0LPHI/bot2teste)

### 💬 Comunidade e Suporte

- 📢 Para dúvidas, sugestões ou reportar problemas, [abra uma issue](https://github.com/MAY0LPHI/bot2teste/issues)
- 💡 Para discussões gerais, use as [Discussions](https://github.com/MAY0LPHI/bot2teste/discussions)
- ⭐ Se este projeto foi útil, considere dar uma estrela!

---

## 🙏 Créditos

Este projeto não seria possível sem:

- 🎯 **Yuri Modz** - Desenvolvedor original do YURI BOT
- 📚 **[@cognima/walib](https://github.com/cognima/walib)** - Biblioteca base para WhatsApp
- 🤝 **Comunidade Open Source** - Por todas as bibliotecas utilizadas
- 💻 **Contribuidores** - Todos que ajudaram a melhorar este projeto

### 🔗 Links Relacionados

- 📖 Documentação oficial: [yuribot.xyz/docs](http://yuribot.xyz/docs)
- 🔄 Repositório original: [YuriModz/Yuri-Bot](https://github.com/YuriModz/Yuri-Bot)
- 📦 NPM - @cognima/walib: [npmjs.com/package/@cognima/walib](https://www.npmjs.com/package/@cognima/walib)

---

<div align="center">

### ⭐ Se este projeto te ajudou, considere dar uma estrela!

[![GitHub Stars](https://img.shields.io/github/stars/MAY0LPHI/bot2teste?style=social)](https://github.com/MAY0LPHI/bot2teste/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/MAY0LPHI/bot2teste?style=social)](https://github.com/MAY0LPHI/bot2teste/network/members)

**Feito com ❤️ e ☕ por desenvolvedores para desenvolvedores**

[⬆ Voltar ao topo](#-yuri-bot---whatsapp-bot-multifuncional)

</div>
