# EMON-721 Profile — Editing Guide

## One-time activation

This package is designed for the **public** GitHub repository `EMON-721/EMON-721` on its default `main` branch. If the repository does not exist, create it at https://github.com/new with repository name `EMON-721`, Public visibility, and initialize with `README.md`. This is the unique GitHub convention that enables profile READMEs.

The 13 design images belong in `assets/`. Keep `README.md` and this guide in the repository root. The folder structure is already published. Do not upload the ZIP without extracting it; GitHub will not extract it automatically.

## Editing sections

- **Edit content**: `README.md` → pencil icon → edit text → Commit changes.
- **Research concept map:** the live profile uses `assets/research-concept-map.svg`, which contains SVG-only flowing network lines and five timed modes: Machine Learning, Artificial Intelligence, Language & NLP, Big Data, and Data Science. Edit that SVG source to change labels, the visual flow, colours, or timing (`dur="35s"`). Preserve valid SVG/XML. The README contains five corresponding `<details>` blocks. `assets/research-cycle.gif` is retained as an optional older-animation archive.
- **Add a research mode**: add a sixth topic to the `<details>` blocks in `README.md` and an additional timed state/menu item inside `assets/research-concept-map.svg`. It is a source-code edit, not a button in the GitHub Overview.
- **Add a project**: create `assets/project-your-new-project.png`; duplicate a `<td>` project block in the projects section; add title, summary, verified link and appropriate visibility note.
- **Delete or reorder**: remove or move the relevant Markdown / HTML section. Every major section begins with a `<!-- ===== -->` marker in README source.
- **Update a picture**: upload a genuine photo and replace the approved stylized portrait in `assets/hero.png`, or regenerate the banner. A standalone `assets/stylized-portrait.png` is included as reference.
- **Add new sections**: create a heading `## 09 / ...` after the last section (e.g. Awards, Certifications, Publications, Blog or Resume). No code changes are needed.
- **Keep work safe**: GitHub commits preserve history. Use History / Revert to restore earlier versions.

## Important limits

GitHub README markdown strips JavaScript and custom CSS. The concept's Edit/Add/Manage controls are implemented as **owner edit links**, clearly commented sections, and an expanding owner tools guide; they are not live CMS dialogs. The AI/ML/NLP/Big Data/Data Science diagram is a connected-node **animated SVG concept map** with native expandable sections. If a client blocks SVG animation, static nodes should still display; the optional original four-mode GIF is kept in the archived details panel. A genuinely interactive web dashboard would require a separate site (e.g. a Next.js site on Vercel) linked from GitHub.

The portrait used in this package is a **stylized image from the user's approved mockup**, not a verified original headshot. Replace it with your own photo before representing it as an authentic photographic portrait.

The repo itself is public: do not add personal secrets, banking data, credentials, student documents, private paper drafts, unpublished research, or private repo contents.

## Publish quickly

1. Open https://github.com/new.
2. Create **EMON-721**, visibility **Public**, check **Add README**.
3. Upload `assets/` and `EDITING_GUIDE.md` via **Add file → Upload files**.
4. Open `README.md`, click **Edit**, replace its body with the supplied `README.md`, and commit.
5. Refresh https://github.com/EMON-721.

The profile README only appears after the repository exists and contains a `README.md` in the root of its default branch.
## Latest profile update — 25 October 2026

- An animated four-stage, twelve-node, five-topic concept map was published to `assets/research-concept-map.svg`.
- `README.md` now presents that map before the preserved About, Education, Research, Skills, Project, Statistics and Contact sections.
- No replacement mockup/screenshot was added; existing hero and project images were retained.
- Before publishing personal links such as WhatsApp, LinkedIn, or email, replace placeholder references with addresses you want made public. Never publish private details automatically.
