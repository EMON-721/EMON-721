# EMON-721 Profile — Editing Guide

## One-time activation

This package is designed for the **public** GitHub repository `EMON-721/EMON-721` on its default `main` branch. If the repository does not exist, create it at https://github.com/new with repository name `EMON-721`, Public visibility, and initialize with `README.md`. This is the unique GitHub convention that enables profile READMEs.

The 13 design images belong in `assets/`. Keep `README.md` and this guide in the repository root. The folder structure is already published. Do not upload the ZIP without extracting it; GitHub will not extract it automatically.

## Editing sections

- **Edit content**: `README.md` → pencil icon → edit text → Commit changes.
- **Add a research mode**: create a new mode graphic and `<details>` block under the Research heading; update `research-cycle.gif` if you also want it in the animation.
- **Add a project**: create `assets/project-your-new-project.png`; duplicate a `<td>` project block in the projects section; add title, summary, verified link and appropriate visibility note.
- **Delete or reorder**: remove or move the relevant Markdown / HTML section. Every major section begins with a `<!-- ===== -->` marker in README source.
- **Update a picture**: upload a genuine photo and replace the approved stylized portrait in `assets/hero.png`, or regenerate the banner. A standalone `assets/stylized-portrait.png` is included as reference.
- **Add new sections**: create a heading `## 09 / ...` after the last section (e.g. Awards, Certifications, Publications, Blog or Resume). No code changes are needed.
- **Keep work safe**: GitHub commits preserve history. Use History / Revert to restore earlier versions.

## Important limits

GitHub README markdown strips JavaScript and custom CSS. The concept's Edit/Add/Manage controls are implemented as **owner edit links**, clearly commented sections, and an expanding owner tools guide; they are not live CMS dialogs. The AI/ML/NLP/Data Science diagram is a GIF carousel plus native expandable content. A genuinely interactive web dashboard would require a separate site (e.g. a Next.js site on Vercel) linked from GitHub.

The portrait used in this package is a **stylized image from the user's approved mockup**, not a verified original headshot. Replace it with your own photo before representing it as an authentic photographic portrait.

The repo itself is public: do not add personal secrets, banking data, credentials, student documents, private paper drafts, unpublished research, or private repo contents.

## Publish quickly

1. Open https://github.com/new.
2. Create **EMON-721**, visibility **Public**, check **Add README**.
3. Upload `assets/` and `EDITING_GUIDE.md` via **Add file → Upload files**.
4. Open `README.md`, click **Edit**, replace its body with the supplied `README.md`, and commit.
5. Refresh https://github.com/EMON-721.

The profile README only appears after the repository exists and contains a `README.md` in the root of its default branch.