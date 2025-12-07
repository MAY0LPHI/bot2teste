# 🤖 YURI BOT - WhatsApp Bot

<div align="center">

![Version](https://img.shields.io/badge/version-2.5.0-blue.svg?style=flat-square)
![Node](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)
![Issues](https://img.shields.io/github/issues/MAY0LPHI/bot2teste?style=flat-square)
![Stars](https://img.shields.io/github/stars/MAY0LPHI/bot2teste?style=flat-square)

**Um bot avançado e completo para WhatsApp com recursos de automação, entretenimento e gerenciamento de grupos** 🚀

[Features](#-features) • [Tecnologias](#-tecnologias) • [Instalação](#-instalação) • [Uso](#-uso) • [Configuração](#%EF%B8%8F-configuração) • [Contribuir](#-contribuindo)

</div>

---

## 📑 Sumário

- [🎯 Sobre o Projeto](#-sobre-o-projeto)
- [✨ Features](#-features)
- [🛠️ Tecnologias](#%EF%B8%8F-tecnologias)
- [📋 Pré-requisitos](#-pré-requisitos)
- [🚀 Instalação](#-instalação)
- [💻 Uso](#-uso)
- [⚙️ Configuração](#%EF%B8%8F-configuração)
- [📸 Screenshots](#-screenshots)
- [🤝 Contribuindo](#-contribuindo)
- [📄 Licença](#-licença)
- [👤 Autor](#-autor)
- [🙏 Créditos](#-créditos)

---

## 🎯 Sobre o Projeto

O **YURI BOT** é um bot multifuncional para WhatsApp desenvolvido em Node.js, projetado para automatizar tarefas, fornecer entretenimento e facilitar o gerenciamento de grupos. Com uma ampla gama de comandos e integrações com APIs externas, o bot oferece funcionalidades como reconhecimento de música, tradução, geração de imagens com IA, jogos interativos e muito mais.

### Por que usar?

- 🔧 **Automação completa**: Gerencie grupos, modere conteúdo e automatize respostas
- 🎮 **Entretenimento**: Jogos, quiz, música e muito mais
- 🤖 **Inteligência Artificial**: Integração com Gemini, Prodia e outras APIs de IA
- 🔒 **Seguro e confiável**: Sistema anti-spam e controle de permissões
- 🌐 **Multi-idioma**: Suporte a traduções e múltiplas linguagens

---

## ✨ Features

### 🎵 Multimídia
- Reconhecimento de músicas (Shazam/ACRCloud)
- Download de vídeos e áudios do YouTube
- Conversão de áudio/vídeo
- Criação de figurinhas (stickers) personalizadas
- Remoção de fundo de imagens

### 🤖 Inteligência Artificial
- Chatbot com IA Gemini
- Geração de imagens com Prodia e Karlo AI
- Tradução automática (Google Translate, Bing Translate)
- OCR (Reconhecimento de texto em imagens) com Tesseract
- Transcrição de áudio com AssemblyAI

### 🎮 Entretenimento
- Jogo da velha (Tic-Tac-Toe)
- Quiz de animais
- Enigmas e charadas
- Gartic
- Akinator
- Sistema de relacionamento/namoro

### 👥 Gerenciamento de Grupos
- Sistema de boas-vindas e despedidas
- Anti-spam e anti-link
- Votação e enquetes
- Marcar todos (@todos)
- Promover/rebaixar administradores
- Detecção de mudanças no grupo (X9)

### 🔧 Utilidades
- Informações meteorológicas
- Busca no Google
- Encurtador de links
- Tabela de horários
- Sistema de níveis e XP
- Comandos personalizados

---

## 🛠️ Tecnologias

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- **[Node.js](https://nodejs.org/)** - Runtime JavaScript
- **[@cognima/walib](https://www.npmjs.com/package/@cognima/walib)** - Biblioteca para integração com WhatsApp Web
- **[Axios](https://axios-http.com/)** - Cliente HTTP
- **[FFmpeg](https://ffmpeg.org/)** - Processamento de multimídia
- **[Cheerio](https://cheerio.js.org/)** - Parser HTML/XML
- **[Tesseract.js](https://tesseract.projectnaptha.com/)** - OCR (Reconhecimento Óptico de Caracteres)
- **[AssemblyAI](https://www.assemblyai.com/)** - Transcrição de áudio
- **[Jimp](https://github.com/jimp-dev/jimp)** - Processamento de imagens
- **[Moment.js](https://momentjs.com/)** - Manipulação de datas

E muitas outras bibliotecas listadas no `package.json`.

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter os seguintes requisitos instalados:

- **[Node.js](https://nodejs.org/)** versão 18.0.0 ou superior
- **[Git](https://git-scm.com/)** para clonar o repositório
- **[FFmpeg](https://ffmpeg.org/)** para processamento de mídia
- **WhatsApp** instalado em um dispositivo móvel (para autenticação)

### Dependências opcionais
- **ImageMagick** - Para processamento avançado de imagens
- **libwebp** - Para criação de stickers WebP

---

## 🚀 Instalação

Siga os passos abaixo para instalar e configurar o bot:

### 1. Clone o repositório

```bash
git clone https://github.com/MAY0LPHI/bot2teste.git
cd bot2teste
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Configure as variáveis de ambiente

Edite o arquivo de configuração localizado em `settings/config.json`:

```json
{
  "OwnerNumber": {
    "value": "5511999999999"  // Seu número de WhatsApp
  },
  "Prefix": {
    "value": "."  // Prefixo dos comandos
  },
  "botName": {
    "value": "MEU BOT"  // Nome do seu bot
  }
}
```

Edite também o arquivo `settings/creds.json` com suas credenciais de APIs (opcional para funcionalidades avançadas):

```json
{
  "Gemini": {
    "apikeys": ["sua-api-key-gemini"]
  },
  "Prodia": {
    "apikeys": ["sua-api-key-prodia"]
  }
}
```

### 4. Execute o bot

**Opção 1: Com QR Code** (requer outro dispositivo para escanear)

```bash
npm start
```

ou

```bash
bash start.sh
```

**Opção 2: Com código de emparelhamento** (não requer escanear QR code)

```bash
bash start.sh sim
```

Digite o número do WhatsApp quando solicitado e insira o código de emparelhamento recebido no WhatsApp.

---

## 💻 Uso

Após a autenticação bem-sucedida, o bot estará pronto para receber comandos no WhatsApp.

### Comandos básicos

```
.menu             - Exibe o menu principal com todos os comandos
.help             - Mostra ajuda sobre comandos específicos
.ping             - Verifica o tempo de resposta do bot
.info             - Informações sobre o bot
```

### Exemplos de uso

**Criar sticker:**
```
Envie uma imagem com a legenda:
.sticker
ou
.s
```

**Traduzir texto:**
```
.traduzir pt Hello, how are you?
```

**Buscar música:**
```
Envie um áudio e responda com:
.shazam
```

**Jogar jogo da velha:**
```
.ttt @usuario
```

**Informações do grupo:**
```
.groupinfo
```

### Estrutura de comandos

A maioria dos comandos segue o padrão:
```
<prefixo><comando> <parâmetros>
```

Por padrão, o prefixo é `.` (ponto), mas pode ser alterado na configuração.

---

## ⚙️ Configuração

### Arquivos de configuração

O bot utiliza os seguintes arquivos de configuração na pasta `settings/`:

#### `config.json` - Configurações gerais
- `OwnerNumber` - Número do dono do bot
- `Prefix` - Prefixo dos comandos (padrão: ".")
- `nameOwner` - Nome do dono
- `botName` - Nome do bot
- `NewsletterConfig` - ID do canal do WhatsApp
- `subOwners` - Números de sub-donos (donos secundários)

#### `creds.json` - Credenciais de APIs
- `Gemini.apikeys` - API keys do Google Gemini
- `Prodia.apikeys` - API keys do Prodia
- `KarloAI.apikeys` - API keys do Karlo AI
- `TMDB.apikeys` - API keys do The Movie Database
- `APIs.website` - URL da API customizada
- `APIs.apikey` - Chave da API customizada

### Variáveis de ambiente importantes

| Variável | Descrição | Obrigatório |
|----------|-----------|-------------|
| `OwnerNumber` | Número do WhatsApp do dono | ✅ Sim |
| `Prefix` | Prefixo dos comandos | ❌ Não (padrão: ".") |
| `API_KEY_GEMINI` | Chave API do Gemini | ❌ Não* |
| `API_KEY_PRODIA` | Chave API do Prodia | ❌ Não* |

*Necessário para funcionalidades de IA

### Personalização

Você pode personalizar diversos aspectos do bot editando os arquivos em `settings/`:
- Mensagens de boas-vindas
- Respostas automáticas
- Filtros de conteúdo
- Permissões de comandos
- E muito mais!

---

## 📸 Screenshots

> **Nota**: Para adicionar screenshots do bot em ação, crie uma pasta `assets/` na raiz do projeto e coloque as imagens lá.

Exemplo de estrutura:
```
bot2teste/
├── assets/
│   ├── screenshot-menu.png
│   ├── screenshot-sticker.png
│   └── screenshot-game.png
├── arquivos/
├── settings/
└── ...
```

Depois, adicione as imagens ao README:
```markdown
![Menu do Bot](assets/screenshot-menu.png)
![Criação de Sticker](assets/screenshot-sticker.png)
```

---

## 🤝 Contribuindo

Contribuições são muito bem-vindas! Se você deseja contribuir com o projeto, siga os passos abaixo:

### 1. Faça um Fork do projeto

Clique no botão "Fork" no topo da página do repositório.

### 2. Clone seu fork

```bash
git clone https://github.com/seu-usuario/bot2teste.git
cd bot2teste
```

### 3. Crie uma branch para sua feature

```bash
git checkout -b feature/minha-nova-feature
```

### 4. Faça suas alterações

Desenvolva sua feature ou correção de bug.

### 5. Commit suas mudanças

```bash
git add .
git commit -m "feat: adiciona nova funcionalidade X"
```

Utilize mensagens de commit semânticas:
- `feat:` para novas funcionalidades
- `fix:` para correções de bugs
- `docs:` para alterações na documentação
- `style:` para formatação de código
- `refactor:` para refatoração de código
- `test:` para adição de testes
- `chore:` para tarefas de manutenção

### 6. Push para o GitHub

```bash
git push origin feature/minha-nova-feature
```

### 7. Abra um Pull Request

Acesse o repositório original e clique em "New Pull Request". Descreva suas alterações detalhadamente.

### Diretrizes de contribuição

- Siga o padrão de código existente
- Teste suas alterações antes de enviar
- Documente novas funcionalidades
- Mantenha as mensagens de commit claras e descritivas
- Não inclua informações sensíveis (API keys, tokens, etc.)

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Isso significa que você pode:

- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Usar de forma privada

**Condições:**
- 📋 Incluir uma cópia da licença e aviso de copyright
- 📋 Indicar mudanças significativas feitas no código

Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

> **Nota**: Caso o arquivo LICENSE não exista no repositório, considere criar um com a licença MIT ou outra de sua preferência.

---

## 👤 Autor

<div align="center">

**YURI MODZ**

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/556593065507)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YuriModz)

📱 **Contato**: +55 65 9306-5507  
🌐 **Website**: [yuribot.xyz/docs](http://yuribot.xzy/docs)

</div>

---

## 🙏 Créditos

Este projeto foi desenvolvido com base em tecnologias e bibliotecas open-source. Agradecimentos especiais a:

- **[@cognima/walib](https://www.npmjs.com/package/@cognima/walib)** - Biblioteca principal para integração WhatsApp
- **Comunidade Node.js** - Pelo ecossistema incrível
- **Todos os colaboradores** - Que ajudam a melhorar o projeto

### Bibliotecas principais utilizadas

- `axios` - Requisições HTTP
- `ffmpeg` - Processamento de mídia
- `tesseract.js` - OCR
- `jimp` - Manipulação de imagens
- `cheerio` - Web scraping
- `moment-timezone` - Manipulação de datas
- E muitas outras listadas em `package.json`

---

<div align="center">

### ⭐ Se este projeto foi útil para você, considere dar uma estrela!

**Feito com ❤️ por [YURI MODZ](https://github.com/YuriModz)**

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=MAY0LPHI.bot2teste)

</div>
