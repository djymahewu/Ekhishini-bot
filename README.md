# Ekhishini WhatsApp Bot

Starter Next.js project for an Ekhishini WhatsApp bot.

## Run locally

1. Install Node.js.
2. Open this folder in a terminal.
3. Run:
   npm install
   npm run dev

## Deploy

This project is ready for Vercel.

After deployment, your webhook endpoint is:

https://YOUR-DOMAIN.vercel.app/api/webhook

In Meta WhatsApp configuration:
- Callback URL: the URL above
- Verify token: the same value used for WHATSAPP_VERIFY_TOKEN

Add the environment variables in Vercel before using the bot.

## Important

This starter verifies Meta webhook requests and receives webhook POST events. Sending replies and adding commands still needs to be connected to the WhatsApp Cloud API using your Meta credentials.
