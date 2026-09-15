# Grokbot

## Newsletter viewer (phone)

Open this URL on your phone — it is the live GitHub-hosted page:

**https://clemclemclemm.github.io/Grokbot/newsletter/**

Site root (redirects to the newsletter): https://clemclemclemm.github.io/Grokbot/

Source file: [`newsletter/index.html`](newsletter/index.html)

### One-time GitHub setup (required)

This repo must be **public** and GitHub Pages must be on. The Cloud Agent cannot flip those settings (no admin token).

1. Make the repo public: [Settings → General → Danger zone → Change repository visibility → Public](https://github.com/clemclemclemm/Grokbot/settings)
2. Turn on Pages: [Settings → Pages](https://github.com/clemclemclemm/Grokbot/settings/pages)
   - **Source:** GitHub Actions  
   - or **Deploy from a branch:** `main` / `/` (root)
3. Wait about a minute, then open the Pages URL above.

Until Pages is built, this public preview also renders the HTML on a phone:

https://htmlpreview.github.io/?https://github.com/clemclemclemm/Grokbot/blob/main/newsletter/index.html

### What Grokbot should send you

Every Cloud Agent reply should include the Pages newsletter link (see `AGENTS.md`). That is the URL to open on your phone.
