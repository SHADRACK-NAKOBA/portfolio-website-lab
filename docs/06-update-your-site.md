# Step 6 – Update your site later (same link)

[⬅ Previous: Publish on Netlify](05-publish-on-netlify.md) | [Next: Share it everywhere ➡](07-share-it-everywhere.md)

When you finish a new project or earn a certification, update the site but **keep the same link**, so you don't have to change your CV or LinkedIn.

## 6.1 Change the design
1. Go to https://claude.ai → open the chat where you built your portfolio (use **Search** in the sidebar, or the **Artifacts** list).
2. Paste a prompt from [`prompts/03-update-later.md`](../prompts/03-update-later.md) (new project, certification or job). It ends with *"Keep everything else exactly as it is."*
3. Check the result on the canvas.

## 6.2 Export again
1. **Export → Standalone HTML → Download**.
2. In your **`my-portfolio`** folder, **delete the old `index.html`**.
3. Move the new download into the folder and rename it to **`index.html`** (as in [Step 4.2](04-export-html.md#42-create-your-website-folder-prevents-the-1-publishing-error)).

## 6.3 Redeploy to the SAME Netlify project
1. Go to https://app.netlify.com → click your project (**your-name**).
2. Open the **Deploys** tab.
3. Scroll to the box that says **"Drag and drop your project folder here"** (*"...to deploy new changes"*).
4. Drag your **`my-portfolio`** folder onto it.
5. Wait for **Published**, then open your link and press **Ctrl + F5** (Windows) or **Cmd + Shift + R** (macOS) to see the new version.

> ⚠️ Don't use **app.netlify.com/drop** for updates. That creates a **new** project with a **new** link.

[⬅ Previous: Publish on Netlify](05-publish-on-netlify.md) | [Next: Share it everywhere ➡](07-share-it-everywhere.md)
