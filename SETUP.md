# GitHub Profile README – Setup

This folder is a **GitHub profile README** template, inspired by [vidyacheekuri/vidyacheekuri](https://github.com/vidyacheekuri/vidyacheekuri). It’s meant to be the **only** repo named after your GitHub username so it shows on your profile.

## Quick setup

1. **Customize `README.md`**
   - Replace `[Your Name]`, `[Your Location]`, `[Languages]`, and any other placeholders.
   - Fill in **Experience** with your real roles and bullet points.
   - Replace `YOUR_GITHUB_USERNAME` in the stats and Connect links.
   - Replace `YOUR_LINKEDIN` and `YOUR_EMAIL` in the Connect section.

2. **Create the repo on GitHub**
   - Create a **new repository**.
   - Name it **exactly** your GitHub username (e.g. if you’re `johndoe`, the repo must be `johndoe`).
   - Set it to **Public**.
   - Do **not** add a README, .gitignore, or license (you already have a README here).

3. **Push this folder**
   ```bash
   cd "profile-readme"
   git init
   git add README.md SETUP.md
   git commit -m "Add profile README"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.git
   git push -u origin main
   ```
   Use your real username in the `origin` URL.

4. **Result**
   - Whatever is in `README.md` will appear on `https://github.com/YOUR_USERNAME`.

## Optional

- **Remove SETUP.md** from the repo after setup if you don’t want it on your profile (or keep it in a branch).
- **Themes for stats:** Change `theme=default` in the image URLs to e.g. `theme=radical`, `theme=gruvbox`, etc. (see [github-readme-stats](https://github.com/anuraghazra/github-readme-stats#themes)).
