# Step 4 – Export the HTML

[⬅ Previous: Refine your design](03-refine-your-design.md) | [Next: Publish on Netlify ➡](05-publish-on-netlify.md)

## 4.1 Download your site
1. With your design open, click **Export** in the **upper-right** corner of the canvas.
2. Choose **Standalone HTML** → **Download**.
3. Also click **Export → Download as .zip** and keep it as a **backup** of your project.

## 4.2 Create your website folder (prevents the #1 publishing error)
Hosting services look for a file called **`index.html`** as the home page. If your file is called `Portfolio.html` or `Untitled.html`, visitors to your link can see **"Page not found"**.

1. Create a new folder on your Desktop called **`my-portfolio`**.
   - **Windows:** right-click the Desktop → **New → Folder**.
   - **macOS:** right-click the Desktop → **New Folder**.
2. Move the downloaded HTML file from **Downloads** into **`my-portfolio`**.
3. Rename it to exactly **`index.html`**:
   - **Windows:** right-click → **Rename** (or press F2). If you can't see `.html`, first open File Explorer → **View → Show → File name extensions** (Windows 11), or tick **File name extensions** (Windows 10). The name must be `index.html`, **not** `index.html.html`.
   - **macOS:** click the file → press **Enter** → type `index.html` → **Enter** → if asked, click **Use .html**.
4. (Optional) Copy **`resume.pdf`** into the same folder if your site has a Download resume button.

Your folder should look like this:
```
my-portfolio/
├── index.html
└── resume.pdf      (optional)
```

## 4.3 Test it locally
Double-click **`index.html`**. It opens in your browser. Check:
- [ ] Your **photo** shows. (If not, see [T3](09-troubleshooting.md#t3-my-photo-doesnt-show).)
- [ ] All sections look right.
- [ ] Links open (email, LinkedIn, GitHub, projects).
- [ ] Make the browser window narrow: the layout adapts like on a phone.

[⬅ Previous: Refine your design](03-refine-your-design.md) | [Next: Publish on Netlify ➡](05-publish-on-netlify.md)
