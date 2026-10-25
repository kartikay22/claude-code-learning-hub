# Claude Code Learning Hub

A responsive, beginner-friendly learning page inspired by the supplied Claude Code skill screenshot. It includes a landing page and seven interactive lessons on repository context, planning, permissions, reviewing diffs, testing, and publishing a hackathon project.

## Features

- Responsive layout inspired by the reference image
- Seven navigable lessons with estimated reading times
- Lesson completion tracking for the current browser session
- Accessible button states, keyboard focus styles, and reduced reliance on dependencies
- Plain HTML, CSS, and JavaScript — no build step required
- Ready for GitHub Pages

## Run locally

No package installation is needed. Open `index.html` in a browser, or serve the folder with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish to GitHub

1. Create a new **public or private** repository on GitHub. For an existing project, choose an unused repository name such as `claude-code-learning-hub`.
2. In a terminal, move into this folder and run:

```bash
git init
git add .
git commit -m "Build Claude Code Learning Hub"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/claude-code-learning-hub.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. If the repository already has a remote, check it with `git remote -v` rather than adding a second one.

## Enable GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under build and deployment, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Wait for the Pages deployment and open the URL shown in that settings page.

## Project structure

```text
claude-code-learning-hub/
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── favicon.svg
├── .gitignore
├── LICENSE
└── README.md
```

## Safety notes

This is an educational project, not an official Anthropic product. The lessons are original summaries and prompts, not a replacement for the latest official documentation. Verify commands before running them and never commit secrets or private data.

Official docs: https://docs.anthropic.com/en/docs/claude-code/overview

## License

MIT — see [LICENSE](LICENSE).
