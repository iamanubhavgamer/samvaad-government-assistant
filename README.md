# Samvaad — Public Deployment

This version is designed for public use. Visitors do not need their own Gemini API key. The browser calls `/api/chat`, and the Vercel serverless function uses the `GEMINI_API_KEY` environment variable.

## Deploy
1. Upload this folder to a GitHub repository.
2. Import that repository into Vercel.
3. In Vercel, open **Settings → Environment Variables**.
4. Add `GEMINI_API_KEY` with your fresh Gemini API key.
5. Redeploy.
6. Open the Vercel URL and test the chatbot.

Never commit a real `.env` file or API key to GitHub.
