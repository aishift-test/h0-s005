# Start here

## 1. Start Claude Code

1. Click inside the Terminal at the bottom. If it is empty: menu (three lines, top left) > Terminal > New Terminal.
2. Type `claude` and press Enter.
3. Wait for the box with the arrow `>`. Then copy the prompt from your hackathon page, paste it, and press Enter.

## 2. Add a picture or file

Drag it from your computer onto the file list on the left. If Chrome asks about the clipboard, click **Allow**. A file only goes online when you tell Claude: `save everything to GitHub`

## 3. See your page

Ask Claude: `give me the link to my live page`. A new page can take 1 minute to appear.

## If something goes wrong

Ask the AI Shift Hackathon Assistant. Copy the last lines from the terminal into the chat.

## Only if your team told you to

If the Terminal says SETUP PROBLEM, or your page does not appear after 5 minutes:

1. Add your key: open github.com/settings/codespaces in a new tab. Next to "Secrets", click **New secret**. Name: `OPENROUTER_API_KEY`. Value: your key from the welcome email (starts with `sk-or-`). Repository access: pick this repository. Click **Add secret**. Come back here and click **Reload to apply**.
2. Turn on your page: open your repository on github.com, click **Settings**, then **Pages**. Under **Branch**, pick **main** and **/ (root)**. Click **Save**. Wait 1 minute.
