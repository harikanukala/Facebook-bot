Start with
* a Wit.ai bot setup (https://wit.ai/docs/quickstart)
* a Messenger Platform setup (https://developers.facebook.com/docs/messenger-platform/quickstart)

Steps to run app:
1. npm install body-parser express request
2. Download and install ngrok from https://ngrok.com/download
3. ./ngrok http 8445
4. WIT_TOKEN=your_access_token FB_APP_SECRET=your_app_secret FB_PAGE_TOKEN=your_page_token 
run node messenger.js
5. Subscribe your page to the Webhooks using verify_token and `https://<your_ngrok_io>/webhook` as callback URL.
6. Talk to your bot on Messenger!