# Step 1 – Prepare your content

[⬅ Previous: Get the files](00-get-the-files.md) | [Next: Build it in Claude Design ➡](02-build-in-claude-design.md)

**This is the most important step.** Claude can only build a great portfolio from great content. Spend most of your time here.

## 1.1 Fill in Portfolio_Data.xlsx

Open the file and read the **START HERE** tab first. Then go through each tab:

| Tab | What to put in | Tips |
|---|---|---|
| **About Me** | Name, title, tagline, bio, location, email, LinkedIn, GitHub, what you're open to, style and colour | Title = the job you **want**, e.g. *AI & Cloud Engineer*. Tagline = one line on what you do. |
| **Skills** | Comma-separated skills per category | Only skills you can talk about in an interview. Empty rows are fine. |
| **Projects** | 3–6 projects: problem, what you built, tech, result, link | **Most important tab.** Add your Prince labs (see below). |
| **Experience** | Jobs, most recent first | No experience yet? Leave it empty. Projects become your main section. |
| **Credentials** | Certifications, education, achievements | Only real ones. Never list a certification you haven't earned. |

**Rules:**
- ✅ Type only in **yellow** cells. Grey italic rows are examples.
- ✅ Leave cells **empty** if they don't apply. Never write "N/A" or invent anything.
- ✅ Copy URLs from your browser's address bar (they must start with `https://`).
- ❌ No home address, date of birth or personal phone number. The site is **public**.

### Your Prince lab projects (copy these into the Projects tab)

Replace `your-username` with your GitHub username, and only add the labs you completed and pushed.

| Project name | Problem | What you built | Tech | Result | Link |
|---|---|---|---|---|---|
| AutoML Classification on Azure ML | Choosing the right model takes a lot of manual trial and error | Azure ML workspace, versioned data asset, AutoML job comparing 10 models on serverless compute | Azure Machine Learning, AutoML, Python SDK v2 | Best model accuracy: *your number* | `https://github.com/your-username/azure-ml-workspace-lab` |
| MLOps Model Training Optimization | Notebook experiments can't be repeated, tracked or scaled | Notebook → parameterised script → tracked command job (MLflow) → parallel hyperparameter sweep on a cluster | Azure ML, Azure CLI, MLflow, scikit-learn | Repeatable tracked training; tuning time roughly halved by parallel trials | `https://github.com/your-username/Azure-Model-training-Optimization` |
| Enterprise Knowledge Agent in Teams & Copilot | Employees waste time searching policy documents | Microsoft Foundry agent grounded in company policies (RAG), published to Teams and Microsoft 365 Copilot | Microsoft Foundry, Azure Bot Service, Python | Accurate, cited policy answers inside Teams | `https://github.com/your-username/Microsoft-AI-Agent-Deployment` |

> 💡 **Your own words are better.** Use the table as a starting point and add what *you* noticed or solved while doing the lab.

When finished: **File → Save** (keep the name `Portfolio_Data.xlsx` and the `.xlsx` format).

## 1.2 Prepare your profile photo

| Do | Don't |
|---|---|
| Face clearly visible, looking at the camera | Group photos, sunglasses, heavy filters |
| Plain or blurred background, good light | Screenshots or photos with text on them |
| Square-ish crop, head and shoulders | Huge files (keep it **under 1 MB**) |
| **JPG** or **PNG** | HEIC (iPhone format), see below |

**Crop and shrink it:**
- **Windows:** right-click the photo → **Open with → Photos** → **Edit** (or the crop icon) → **Crop**, choose **Square** → **Save as copy**.
- **macOS:** open in **Preview** → select a square area → **Tools → Crop** → **Tools → Adjust Size** → width **800** → **File → Export** → **Format: JPEG**.
- **iPhone photo (.HEIC)?** On iPhone: **Settings → Camera → Formats → Most Compatible** before taking the photo, or email the photo to yourself (it usually converts to JPG), or use a free online HEIC-to-JPG converter.

Rename the file to **`profile.jpg`** and save it in the same folder as your spreadsheet.

> **Photo inside a PDF** (for example a graduation photo)? Take a screenshot of it (**Windows:** Win + Shift + S, **macOS:** Cmd + Shift + 4), crop it as above, and save it as `profile.jpg`.

## 1.3 (Optional) Your resume

If you want a **Download resume** button, export your CV as **resume.pdf**. (You'll add it to the website folder in step 5.)

## Check before you continue
- [ ] Every tab of `Portfolio_Data.xlsx` is filled in (or deliberately empty), and saved.
- [ ] At least 3 projects, each with a link.
- [ ] `profile.jpg` is ready, under 1 MB.

[⬅ Previous: Get the files](00-get-the-files.md) | [Next: Build it in Claude Design ➡](02-build-in-claude-design.md)
