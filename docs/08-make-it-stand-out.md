# Step 8 – Make it stand out

[⬅ Previous: Share it everywhere](07-share-it-everywhere.md) | [Next: Troubleshooting ➡](09-troubleshooting.md)

## 8.1 Run the final checklist
Go through [`examples/final-checklist.md`](../examples/final-checklist.md) before you send your link to anyone.

## 8.2 Check the LinkedIn link preview
When you paste your link into LinkedIn, it should show a proper title and description (the brief asked Claude for these "Open Graph" tags).
1. Go to https://www.linkedin.com/post-inspector/.
2. Paste your link → **Inspect**.
3. You should see your name and title. If not, ask Claude in your design chat:
   ```
   Add Open Graph meta tags: og:title "<name> - <title>", og:description "<tagline>",
   og:type "website", and a matching <title> and meta description. Keep everything else exactly as it is.
   ```
   Then export and redeploy ([Step 6](06-update-your-site.md)).

## 8.3 What makes recruiters stop
| Do | Why |
|---|---|
| **Projects first, with links** | Proof beats claims. A recruiter can click your GitHub. |
| **Problem → What I built → Result** on every project | Shows business thinking, not just tools |
| **Real numbers** when you have them (accuracy, time saved, cost) | Specific beats vague. **Never invent them.** |
| **Title = the job you want** | Recruiters search by title |
| **Fast, mobile-friendly, no typos** | Many recruiters open links on their phone |
| **Keep it updated** | Add each new lab or certification ([Step 6](06-update-your-site.md)) |

## 8.4 (Optional) Custom domain, about $10–15/year
`firstnamelastname.com` looks even more professional than `.netlify.app`.
1. In Netlify, open your project → **Domain management** → **Add a domain**.
2. Search for the name you want and follow **Register** to buy it through Netlify (the easiest option, set up automatically), **or** buy it elsewhere (Namecheap, Cloudflare, etc.) and follow Netlify's **Add a domain you already own** instructions.
3. Wait for HTTPS to be provisioned (minutes to a few hours), then update your link everywhere.

## 8.5 (Optional) Visitor stats
Netlify's analytics is a paid add-on. A free alternative is to add privacy-friendly analytics later. Ask Claude how, once you're comfortable.

## 8.6 (Optional) Announce it with a great LinkedIn post
Paste this into Claude or ChatGPT, after filling in the brackets:
```
Write a short LinkedIn post (120-180 words) announcing my new portfolio website.
Hook: one line about turning hands-on cloud/AI labs into proof of skills.
Mention 3 projects in one line each: [project 1], [project 2], [project 3].
Tools: Claude Design to build it, Netlify to host it.
End with: open to [roles] - link: [your link]. Add 5 relevant hashtags.
Tone: confident, professional, no hype, no invented numbers.
```

[⬅ Previous: Share it everywhere](07-share-it-everywhere.md) | [Next: Troubleshooting ➡](09-troubleshooting.md)
