# Setup & Publishing Guide for github.com/mehersoni

This repository contains your complete GitHub Profile README system. Follow these quick steps to publish it to your live GitHub profile page.

---

## Step 1: Create the Special Repository on GitHub

1. Go to [github.com/new](https://github.com/new).
2. Set the **Repository Name** to exactly `mehersoni`.
   > *GitHub will display a green banner stating: "You found a secret! `mehersoni/mehersoni` is a special repository that you can use to add a README.md to your GitHub profile."*
3. Make sure the repository visibility is set to **Public**.
4. Check **Add a README file** (or leave unchecked if uploading files from your computer).
5. Click **Create repository**.

---

## Step 2: Push These Files to the Repository

You can upload the files directly via GitHub web UI, or use git commands from your local computer:

```bash
cd "c:\Users\Meher\OneDrive\Desktop\New folder"

# Initialize git repository
git init
git add .
git commit -m "feat: setup Apple x Academic Journal GitHub profile README"

# Link to your GitHub repository and push
git branch -M main
git remote add origin https://github.com/mehersoni/mehersoni.git
git push -u origin main
```

---

## Step 3: Fill in your Placeholders

Open `README.md` and replace the following placeholder bracketed links with your actual URLs:

- `[YOUR_LINKEDIN_URL]` → `https://linkedin.com/in/mehersoni` (or your exact URL)
- `[YOUR_PORTFOLIO_URL]` → `https://mehersoni.dev` (or your personal website)
- `[YOUR_SCHOLAR_URL]` → Your Google Scholar profile link
- `[YOUR_NYAYA_REPO_URL]` → `https://github.com/mehersoni/nyaya-ai`
- `[YOUR_SPEECH_ASR_REPO_URL]` → `https://github.com/mehersoni/speech-to-text-asr`
- `[YOUR_INDIC_TTS_REPO_URL]` → `https://github.com/mehersoni/indic-speech-g2p`
- `[YOUR_SUDARSHANA_REPO_URL]` → `https://github.com/mehersoni/sudarshana-wearable`

---

## Included Files

- [`README.md`](./README.md) — Master Profile README
- [`assets/header.svg`](./assets/header.svg) — Abstract animated vector header banner
- [`assets/divider.svg`](./assets/divider.svg) — Minimalist section divider SVG
- [`PROJECT_README_TEMPLATE.md`](./PROJECT_README_TEMPLATE.md) — Reusable research README template for your individual project repos
