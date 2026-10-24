# Step 10 – Optional: host on GitHub Pages instead

[⬅ Back to README](../README.md)

**GitHub Pages** is another free host. Use it if you want your portfolio's code on GitHub too, which is extra proof that you use Git. Your link will be `https://your-username.github.io`.

## 10.1 Create the special repository
1. Go to https://github.com/new.
2. **Repository name:** exactly **`your-username.github.io`** (your GitHub username, all lowercase, then `.github.io`).
3. Select **Public**.
4. Tick **Add a README file**.
5. Click **Create repository**.

## 10.2 Upload your site
1. In the new repository, click **Add file → Upload files**.
2. Drag **`index.html`** (and `profile.jpg` / `resume.pdf` if you use them) from your `my-portfolio` folder.
3. Scroll down, type a message like `Add portfolio site`, and click **Commit changes**.

## 10.3 Turn on Pages
1. Click **Settings** (top of the repository) → **Pages** (left menu).
2. Under **Build and deployment**: **Source = Deploy from a branch**, **Branch = main**, folder **/(root)** → **Save**.
3. Wait 1–3 minutes, then refresh the page. It shows **"Your site is live at https://your-username.github.io"**.

## 10.4 Update later
**Add file → Upload files** → upload the new `index.html` (it replaces the old one) → **Commit changes**. The site updates in 1–3 minutes.

> ❌ **404 at your link?** The file must be named `index.html` and sit at the top of the repository (not inside a folder), and the repository name must exactly match `your-username.github.io`.

[⬅ Back to README](../README.md)
