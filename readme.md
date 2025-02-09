# Stella

#### Stella is a Discord AI chatbot powered by Google Gemini. It can generate text, answer questions, and assist with coding.

#### Stella leverages Google's Gemini 1.5 Flash-8B model to process requests and provide intelligent responses.

#### [Invite Stella]() to your server 🚀

### ✨ Features
- AI-Powered Responses : Generates text and answers questions using Google Gemini 1.5 Flash-8B.

- Code Assistance : Helps with coding, debugging, and explaining programming concepts.

- Conversational AI : Engages in natural, human-like conversations.

- Discord Integration : Seamlessly interacts with users in Discord servers.

- Optimized for Performance : Uses efficient chunking for larger responses and smartly reject absurdly long requests.

- Lightweight & Fast : Built for quick responses with minimal resource usage.

### 📦 Installation
#### Want to run Stella locally ? 
Here's what you'll need and how to do it.

- Get a ***Gemini API Key*** : [Click Here](https://ai.google.dev/gemini-api/docs/api-key?authuser=1) to get your own Gemini API Key.

- Create a bot : Login To [Discord Developer Portal](https://discord.com/developers/applications) and create a bot.

- Get your Unique ***Bot Token*** : Go into your *Bot* > *bot* > *reset Token* > Then copy the *Token*.

- Get your ***client ID*** : Go into your *Bot* > *OAuth2* > Under Client Information copy *Client ID*.

**Clone the Repository :**
```bash
git clone https://github.com/nexus949/Stella
```

**Install the dependencies :**
```bash
npm install
```

**Create a ```.env``` file and paste your credentials :**
```bash
BOT_TOKEN = your-bot-Token
CLIENT_ID = your-client-id
GEMINI_API_KEY = your-gemini-api-key
``` 

**Register the commands :**
```bash
node botCommands.js
```

**Start the Bot :**
```bash
nodemon bot.js
```

### ℹ Additional Information
- Stella is built using the Discord.js library to handle interactions seamlessly. For registering new commands or troubleshooting, refer to their official documentation.

- You can integrate any other AI service, but setup requirements may vary, and it will be your sole responsibility to configure it correctly.

- By default, Stella uses Google Gemini’s free-tier API, but you are free to upgrade to a higher tier if needed.

- Customization is encouraged! You can tweak Stella’s behavior, responses, and AI model settings as per your needs.

- Ensure you have the necessary API keys and permissions when making modifications to avoid service disruptions.