# Step 9 – Troubleshooting

[⬅ Back to README](../README.md)

| # | Problem |
|---|---|
| [T1](#t1-claude-says-ive-reached-my-usage-limit) | Usage limit reached |
| [T2](#t2-i-cant-find-output--design) | Can't find Output → Design |
| [T3](#t3-my-photo-doesnt-show) | Photo doesn't show |
| [T4](#t4-the-site-has-placeholder-text-or-invented-skills) | Placeholder text or invented skills |
| [T5](#t5-claude-cant-read-my-spreadsheet) | Claude can't read the spreadsheet |
| [T6](#t6-netlify-shows-page-not-found) | Netlify "Page not found" |
| [T7](#t7-my-changes-dont-show-on-the-live-site) | Changes don't show on the live site |
| [T8](#t8-i-got-a-new-link-instead-of-updating-my-site) | Got a new link instead of updating |
| [T9](#t9-the-name-i-want-is-already-taken-on-netlify) | Netlify name already taken |
| [T10](#t10-it-looks-broken-on-my-phone) | Broken on phone |
| [T11](#t11-a-comment-on-the-canvas-did-nothing) | Comment did nothing |

---

### T1. Claude says I've reached my usage limit
Claude Design shares your account's usage limit. Wait until it resets (Claude shows when). Next time, send the **full brief** in one message and batch several changes into one refinement message instead of many tiny ones.

### T2. I can't find Output → Design
- Make sure you're on **https://claude.ai** and signed in, in a **new chat**.
- Look for **Output** in or near the message box. On some screens it's behind a **+** or tools icon.
- Or simply start your message with **"Create a design:"** followed by the brief.
- In the **Artifacts** area of the sidebar you can also start from a **Design** template.
- Older guides mention **claude.ai/design**. That standalone page closes on **14 December 2026**. Use Design inside a normal chat instead.

### T3. My photo doesn't show
| Where | Fix |
|---|---|
| On the canvas | Check `profile.jpg` was attached (file card visible) when you sent the brief. If not, attach it now and say: *"Use the attached profile.jpg as my profile photo in the hero."* |
| After export (broken image icon) | The photo wasn't embedded. Ask: *"Embed my profile photo directly inside the HTML (as a base64 data URI) so it works in a standalone HTML file. Keep everything else exactly as it is."* Then export again. |
| Still broken | Use the separate-file method: ask Claude to *"Load the profile photo from a file named profile.jpg in the same folder."* Export, then copy **`profile.jpg`** into your `my-portfolio` folder next to `index.html` and redeploy the whole folder. |
| Photo is .HEIC or huge | Convert to JPG and shrink it ([Step 1.2](01-prepare-your-content.md#12-prepare-your-profile-photo)). |

### T4. The site has placeholder text or invented skills
Paste into the chat:
```
Remove all placeholder text (e.g. "Your Name", "you@example.com", "Lorem ipsum") and any
skill, number, employer or certification that is not in my spreadsheet. Use only my data.
List what you removed.
```
Also check your spreadsheet: if you left the **Example** rows or typed "N/A", Claude may have used them.

### T5. Claude can't read my spreadsheet
- It must be **.xlsx** (not `.numbers`, `.ods` or a Google Sheets link). From Google Sheets: **File → Download → Microsoft Excel (.xlsx)**.
- Close the file in Excel before uploading.
- Still failing? Copy the content of each tab and paste it into the chat as text with the brief.

### T6. Netlify shows "Page not found"
Your home page isn't called **`index.html`**, or you dropped the file instead of the folder.
1. Rename the file to exactly `index.html` (watch out for `index.html.html` on Windows: turn on **File name extensions**, [Step 4.2](04-export-html.md#42-create-your-website-folder-prevents-the-1-publishing-error)).
2. Put it in the `my-portfolio` folder and drag the **folder** onto your project's **Deploys** tab.

### T7. My changes don't show on the live site
- Hard refresh: **Ctrl + F5** (Windows) / **Cmd + Shift + R** (macOS), or open the link in a private window.
- Check the **Deploys** tab: the newest deploy should say **Published**.
- Check you replaced `index.html` with the **new** export.

### T8. I got a new link instead of updating my site
You used **app.netlify.com/drop**, which creates a new project. Delete the extra project (**Project configuration → General → Danger zone → Delete project**) and redeploy through your original project's **Deploys** tab ([Step 6.3](06-update-your-site.md#63-redeploy-to-the-same-netlify-project)).

### T9. The name I want is already taken on Netlify
Names are first come, first served. Try `firstname-lastname-ai`, `firstnamelastname`, `firstname-lastname-dev`, or add your middle initial.

### T10. It looks broken on my phone
Paste: *"Check the whole page on a phone-sized screen and fix anything that overflows, overlaps or is too small to read. Keep everything else exactly as it is."* Export and redeploy.

### T11. A comment on the canvas did nothing
Paste the same request into the **chat** instead. Chat works for everything.

---

Still stuck? Post a screenshot of the problem (hide private details) and the step number in the Prince community.

[⬅ Back to README](../README.md)
