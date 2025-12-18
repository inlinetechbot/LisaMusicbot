🎵 LisaMusic Telegram Music Bot

LisaMusic is a powerful and advanced Telegram Group Music Bot that allows users to play high-quality music in Telegram voice chats with smooth performance and rich features.


---

✨ Features

🎶 Play music in Telegram voice chats

🔍 Search and stream songs from multiple sources

📜 Queue management (add, remove, skip tracks)

⏯️ Pause, resume, stop playback

🤖 Userbot assistant support (string session)

🔐 Secure MongoDB database integration

👑 Owner-only admin commands

📢 Logger group support

🚀 Stable and optimized performance



---

🧰 Requirements

Python 3.10+

Telegram API_ID & API_HASH

Telegram Bot Token

Userbot String Session

MongoDB URI

VPS / Cloud / Hosting with voice support



---

📂 Project Structure

LisaMusic/
│
├── LisaX/
│   ├── __main__.py
│   ├── core/
│   │   ├── bot.py
│   │   ├── call.py
│   │   ├── mongo.py
│   │   ├── userbot.py
│   │   └── ...
│
├── plugins/
│   ├── admin.py
│   ├── play.py
│   ├── privacy.py
│   └── ...
│
├── config/
│   └── config.py
│
├── requirements.txt
├── sample.env
├── Dockerfile
├── Procfile
└── README.md


---

⚙️ Configuration

Rename sample.env to .env and fill in the required values:

API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token

STRING_SESSIONS=your_userbot_string
MONGO_DB_URI=your_mongodb_uri

OWNER_ID=your_telegram_id
LOGGER_ID=your_logger_group_id

⚠️ Do not use quotes and do not add spaces.


---

▶️ Installation & Run

Install dependencies

pip3 install -r requirements.txt

Start the bot

python3 -m LisaX


---

🎮 Commands

User Commands

/play – Play music

/pause – Pause playback

/resume – Resume playback

/skip – Skip current track

/stop – Stop music

/queue – Show queue

/privacy – View privacy policy


Admin / Owner Commands

/broadcast – Broadcast message (owner only)

/stats – Bot statistics

/reload – Reload configuration



---

🔐 Privacy Policy

LisaMusic respects user privacy and data protection.

📜 Read our Privacy Policy here:
https://telegra.ph/Privacy-Policy-for-LisaMusic-12-18


---

🚀 Deployment

LisaMusic can be deployed on:

VPS / Dedicated Server

Render

Docker-based hosting

Any Python-supported hosting with voice chat support



---

⚠️ Disclaimer

This project is intended for educational purposes only.
The developer is not responsible for misuse or copyright issues.


---

👤 Developer

Maintained by: Legend PlayYT
Bot Name: LisaMusic

