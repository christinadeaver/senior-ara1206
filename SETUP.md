# GitHub Profile Setup Guide

Your customized profile lives in this folder. Follow the steps below to publish it.

## 1. Create the special profile repo

1. Go to https://github.com/new
2. Repository name must be exactly: `senior-ara1206`
3. Set it to Public
4. Do NOT add a README, .gitignore, or license on GitHub
5. Click Create repository

## 2. Push this folder

In PowerShell:

```powershell
cd D:\zz\senior-ara1206
git init
git add .
git commit -m "feat: add customized GitHub profile README"
git branch -M main
git remote add origin https://github.com/senior-ara1206/senior-ara1206.git
git push -u origin main
```

## 3. Turn on the contribution snake

1. Open the repo on GitHub
2. Go to Actions
3. Allow Actions if prompted
4. Open Generate contribution snake
5. Click Run workflow

After it finishes, the snake animation appears on your profile.

## 4. Customize your GitHub account settings

Go to https://github.com/settings/profile and fill these in:

| Field | Suggested value |
| --- | --- |
| Name | Ara or your real name |
| Bio | Full-Stack and Cloud Engineer. Building web apps. Open to remote roles. |
| Pronouns | optional |
| Location | Remote or your city |
| Website | portfolio URL if you have one |
| Social accounts | LinkedIn, Handshake, etc. |
| Status | Open to work |
| Hireable | check Available for hire if shown |

Also:

1. Upload a clear profile photo
2. Pin your best 4 to 6 repos under Customize your pins
3. Star a few quality open-source repos you actually use
4. Follow people in your stack so the network grows naturally

## 5. Make commits look professional

Use clear commit messages on real work:

```text
feat: add login page
fix: correct API timeout
docs: update README
chore: update dependencies
```

Tips:

1. Commit from your real projects only
2. Prefer many small meaningful commits over empty ones
3. Push regularly so your contribution graph stays honest and active
4. Do not use fake commit scripts. Recruiters notice empty commit farms

## 6. Optional upgrades later

1. Add LinkedIn and portfolio links in README Connect section
2. Replace project table rows with live demo URLs
3. Add AWS or Azure cert badges when you earn them
4. Write short README files for each existing repo
5. Enable Discussions or a simple Issues welcome template if you want community

## What this package already includes

1. Typing header animation
2. Profile views badge
3. Followers and remote-ready badges
4. About Me block
5. Tech stack badges
6. Featured projects table
7. GitHub stats, languages, streak, trophies
8. Activity graph
9. Contribution snake workflow
10. Footer wave and quote widget
