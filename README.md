# Arjit Singh — Portfolio

Static portfolio site (HTML/CSS/JS) with an optional AI chat assistant ("IRIS") that answers questions from the resume and page content.

Based on the open-source layout from [AtharSayed/athar-portfolio](https://github.com/AtharSayed/athar-portfolio) — all content here is Arjit Singh's.

## Run locally
```bash
cd server
npm install
cp .env.example .env   # then add HF_API_KEY=your_huggingface_token
npm start              # http://localhost:5173
```
Without an API key the site works normally; only the chat assistant is disabled.

## Deploy
Deploy the folder to Vercel (static site + `api/chat.js`) and set the `HF_API_KEY` environment variable.

## Replace before publishing
- `images/profile-placeholder.svg` → your photo (update the `<img>` in the About section)
- Add your GitHub link next to LinkedIn in the About section, if you want one
