# 🚀 Deployment & Publishing Instructions — Shrawani Kapse

Welcome to your redesigned, premium animated GitHub profile! Follow these simple, step-by-step instructions to publish it to your GitHub profile.

---

## 📁 Files Included in This Package

Your finished project contains the exact required structure:

```text
github-profile/
├── README.md                 <-- Your new profile README
├── preview.html              <-- Interactive local test & audit dashboard
├── README-INSTRUCTIONS.md    <-- This instruction guide
├── github-profile.zip        <-- Upload-ready archive
└── assets/                   <-- Profile SVGs and original retina portrait
    ├── id.png                <-- High-resolution portrait (alpha preserved)
    ├── hero.svg              <-- Animated greeting, name reveal & cycling roles
    ├── about-life.svg        <-- Core capabilities & 3-slide interests carousel
    ├── stack.svg             <-- Orbital constellation & verified tech chips
    ├── id-dashboard.svg      <-- Swinging lanyard ID pass & verified milestones
    └── connect.svg           <-- Portrait & interactive social links
```

---

## 🛠️ Step 1: Create or Open Your Special GitHub Repository

1. Open your browser and go to [GitHub](https://github.com).
2. Click the **`+`** icon in the top-right corner and select **New repository**.
3. In the **Repository name** field, enter your exact GitHub username:
   ```text
   shrawanikapse09
   ```
   > 💡 *GitHub will display a special note: "You've found a secret! `shrawanikapse09/shrawanikapse09` is a ✨special✨ repository that you can use to add a README to your GitHub profile."*
4. Make sure the repository visibility is set to **Public**.
5. (Optional) Check **Add a README file** if you are creating it for the first time.
6. Click **Create repository**.
   *(If you already have this repository created, simply open `github.com/shrawanikapse09/shrawanikapse09`)*.

---

## 📤 Step 2: Upload the Files to GitHub

You can publish your profile in one of two ways:

### Option A: Web Browser Upload (Easiest — Beginner Friendly)

1. Unzip `github-profile.zip` on your computer (or use the folder directly).
2. Go to your repository page: `https://github.com/shrawanikapse09/shrawanikapse09`.
3. Click the **Add file** button near the top right, then choose **Upload files**.
4. Drag and drop the following items into the upload box:
   - `README.md`
   - The entire `assets` folder (containing `id.png`, `hero.svg`, `about-life.svg`, `stack.svg`, `id-dashboard.svg`, and `connect.svg`).
5. In the **Commit changes** box at the bottom:
   - Title: `feat: launch redesigned animated profile`
   - Select **Commit directly to the `main` branch**.
6. Click **Commit changes**.

---

### Option B: Using Git in Terminal / Command Prompt

If you prefer git commands:

```bash
# 1. Clone your special repository
git clone https://github.com/shrawanikapse09/shrawanikapse09.git
cd shrawanikapse09

# 2. Copy README.md and the assets folder into this directory
# (Copy README.md and assets/ into the repository folder)

# 3. Stage, commit, and push
git add README.md assets/
git commit -m "feat: launch premium animated GitHub profile"
git push origin main
```

---

## 🔍 Step 3: Check Your Live Profile

1. Visit your public profile: [github.com/shrawanikapse09](https://github.com/shrawanikapse09).
2. Verify that:
   - All 5 animated banners load cleanly.
   - The cycling roles in the hero section transition smoothly every 3 seconds.
   - The carousel in the About section advances every 4 seconds.
   - The hanging ID card maintains its gentle, damped pendulum swing.
   - The clickable social links (GitHub, LinkedIn, Gmail) open your verified profiles.
   - The project links for **StudySage** and **Semantic Resume Analyzer** open the live apps and repositories.

---

## 💡 Troubleshooting & GitHub Camo Caching

- **Images not updating after a change?**
  GitHub proxies all images through its `camo` CDN and caches them aggressively. When you make an edit to any SVG in `assets/`, simply update the version query parameter in `README.md` from `?v=1` to `?v=2` (e.g. `![Hero](./assets/hero.svg?v=2)`). This immediately forces GitHub to fetch the newest version.
- **Testing offline or locally?**
  Double click `preview.html` to open it in any modern browser (Chrome, Edge, Firefox, Brave, Safari). You can test tablet and mobile viewports, toggle dark/light modes, and verify that portrait transparency has zero halos.
