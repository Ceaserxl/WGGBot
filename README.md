# Discord Bot + ChatGPT + Plex Integration

This project is a multi-feature Discord bot that integrates with:  
- OpenAI ChatGPT / Dall-E-3
- Stable Diffusion (for image generation)

---

## 🔧 Environment Configuration

Create a `.env` file in the root directory with the following contents:

```env
# Discord Bot Tokens
LIVE_DISCORD_TOKEN=your_live_bot_token
BETA_DISCORD_TOKEN=your_beta_bot_token

# OpenAI API Key
OPENAI_API_KEY=your_openai_key

# Application & AI Settings
APP_URL=your_app_ip_or_url
CHATGPT_MODEL=gpt-4.1-nano

# Stable Diffusion Web UI
SD_API_URL=http://your-stable-diffusion-url:port
````

---

## 🛠️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/Ceaserxl/WGGBot.git
   cd WGGBot
   ```

2. **Create and activate a virtual environment**

   * **Linux/macOS**

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   * **Windows**

     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the bot**

   ```bash
   python main.py
   ```

## 🤖 Features

* **ChatGPT Integration**: Respond to Discord messages using OpenAI.
* **Stable Diffusion**: Generate images on demand.
* **Live & Beta Modes**: Switch tokens to test in staging vs production.

---