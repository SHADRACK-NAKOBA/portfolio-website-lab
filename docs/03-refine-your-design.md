# Step 3 – Refine your design

[⬅ Previous: Build it in Claude Design](02-build-in-claude-design.md) | [Next: Export the HTML ➡](04-export-html.md)

Your first draft is a starting point. You have three ways to improve it:

| Tool | Best for | How |
|---|---|---|
| **Chat** | Whole-page changes: new sections, layout, colours, rewriting text | Type in the message box beside the canvas |
| **Inline comments** | One specific element: a button, a heading, spacing | Click the part of the canvas you want to change, type the request in the comment box, submit |
| **Direct editing** | Quick visual tweaks | Drag, resize and align elements on the canvas |

> If an inline comment doesn't seem to take effect, paste the same request into the **chat** instead.

## 3.1 Fix what Claude couldn't use
Claude listed anything it couldn't use from your spreadsheet. Fix each one in the chat, for example:
```
My GitHub link is https://github.com/your-username - please add it to the hero and contact section.
```

## 3.2 Apply improvements
Open [`prompts/02-refinement-prompts.md`](../prompts/02-refinement-prompts.md) and paste the ones you want, **one at a time**. Recommended order:
1. **Merge duplicate skill rows** (if you see any).
2. **Rewrite project cards as Problem → What I built → Result.**
3. **Phone check:** fix anything that breaks on a small screen.
4. **Link check:** list every link so you can verify it.
5. **Remove placeholders or invented details.**

## 3.3 Check it yourself (don't skip)
Go through this list on the canvas:
- [ ] Name, title and photo are correct.
- [ ] **Every** project link opens *your* GitHub repo.
- [ ] Email, LinkedIn and GitHub buttons point to *your* accounts.
- [ ] No "Your Name", "Lorem ipsum", `example.com` or skills you don't have.
- [ ] No spelling mistakes in your name, company names or certifications.

> 💡 **Version history:** if a change makes things worse, ask in the chat: *"Undo the last change."*

[⬅ Previous: Build it in Claude Design](02-build-in-claude-design.md) | [Next: Export the HTML ➡](04-export-html.md)
