# Telegram Referral Bot (Webhook Version)

Bot Telegram sederhana menggunakan webhook, cocok untuk Vercel.

## 🚀 Cara Jalankan (Vercel)
1️⃣ Deploy ke Vercel, pastikan root directory = `api`  
2️⃣ Set webhook:
```
curl -F "url=https://your-vercel-url.vercel.app/webhook" https://api.telegram.org/bot<BOT_TOKEN>/setWebhook
```
3️⃣ Bot akan menerima update melalui endpoint `/webhook`

## 📦 Dependensi
- Flask
- pyTelegramBotAPI
- python-dotenv
