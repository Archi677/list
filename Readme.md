# 🛒 List — Shopping List Manager

> A clean, lightweight, and fully client-side shopping list app.
> Built completely on a phone by a 10th-grade student. 📱✨

[![Made with HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Made with CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=for-the-badge&logo=github)](https://archi677.github.io/list/)
[![Mobile Built](https://img.shields.io/badge/Built%20on-Phone-blueviolet?style=for-the-badge&logo=android)](https://github.com/Archi677/list)
[![License](https://img.shields.io/badge/License-Open%20for%20Educational%20Use-lightgrey?style=for-the-badge)](https://github.com/Archi677/list)

**Author:** Archisman Sakhari  
**Under the name:** **Vanta-Forge**  
**Repo:** [Archi677/list](https://github.com/Archi677/list)  
**Live Demo:** [https://archi677.github.io/list/](https://archi677.github.io/list/)

---

## 📑 Table of Contents

1. [About the Project](#-about-the-project)
2. [Why This Project Exists](#-why-this-project-exists)
3. [Features](#-features)
4. [Usage](#-usage)
5. [Project Structure](#️-project-structure)
6. [Tech Stack](#️-tech-stack)
7. [How It Works](#-how-it-works)
8. [Roadmap](#-roadmap)
9. [Contributing](#-contributing)
10. [Code of Conduct](#-code-of-conduct)
11. [FAQ](#-faq)
12. [Acknowledgements](#-acknowledgements)
13. [About the Developer](#-about-the-developer)
14. [Contact](#-contact)
15. [License](#-license)

---

## 📖 About the Project

**List** is a simple yet powerful shopping list application that runs entirely in your browser — no servers, no databases, no sign-ups. Everything is handled client-side, making it fast, private, and easy to use.

This project was **built completely on a phone** by **Archisman Sakhari**, a Class 10 student, proving that great things can be created with limited tools and a lot of passion. 🚀

The app is intentionally minimal: one HTML file, a handful of styles, and vanilla JavaScript. There is no build step, no package manager, and no framework. You can open `index.html` and the app just works.

---

## 💡 Why This Project Exists

Most shopping list apps are either bloated with ads, require an account, or send your data to a server. **List** was created to solve a simple problem:

- You need a shopping list.
- You want it now.
- You don't want to sign up, install anything, or share your data.

Because the app is fully client-side, your list stays in your browser. Nothing is transmitted anywhere. It's a tool that respects your privacy by design.

It's also a personal milestone: a complete, working, deployed web application built entirely from a mobile device. This README documents that journey and makes the project easy to use, copy, and learn from.

---

## ✨ Features

### Core Features
- ✅ **Fully Client-Side** — No backend required; runs entirely in your browser.
- ✅ **Shopping List Management** — Add, view, and manage your shopping items effortlessly.
- ✅ **Lightweight & Fast** — Minimal dependencies for a snappy experience.
- ✅ **Single-File App** — The entire app lives in a single `index.html` file.
- ✅ **Offline-Friendly** — Once the file is downloaded, it works without an internet connection.
- ✅ **No Sign-Up Required** — Open the page and start using it immediately.
- ✅ **Privacy-First** — No tracking, no analytics, no data leaves your device.

### Developer & Deployment Features
- ✅ **GitHub Pages Hosted** — Instantly accessible online via GitHub Pages.
- ✅ **CI/CD Ready** — Automated deployment via GitHub Actions workflow (`.github/workflows`).
- ✅ **Versioned Releases** — Old versions preserved (`index(old).html`) for reference.
- ✅ **Mobile-Built** — Developed and tested entirely on a mobile device.
- ✅ **Zero Build Step** — No bundlers, no compilers, no `npm install` needed.
- ✅ **Easy to Fork** — Copy the repo, enable Pages, and you have your own live version.

### Planned / Possible Features
- 🔜 **Persistent Storage** — Save your list between browser sessions (e.g., via `localStorage`).
- 🔜 **Item Check-Off** — Mark items as bought.
- 🔜 **Multiple Lists** — Create and switch between different shopping lists.
- 🔜 **Export / Import** — Save your list as a file and load it later.
- 🔜 **Dark Mode** — A theme toggle for low-light environments.
- 🔜 **Drag-and-Drop Reordering** — Prioritize items by dragging.

---

## 🚀 Usage

There are **three easy ways** to use this project. Pick the one that fits your needs.

### 1️⃣ Use the Hosted GitHub Page (Recommended)

Simply open the live hosted version in your browser:

👉 **[https://archi677.github.io/list/](https://archi677.github.io/list/)**

No installation required — just open and start listing!

**Steps:**
1. Open the link above in any modern browser (Chrome, Firefox, Safari, Edge).
2. Start adding your shopping items.
3. Bookmark the page for quick access later.

This is the fastest way to use the app. It always serves the latest version from the `main` branch.

---

### 2️⃣ Copy / Fork the Repository

Want to customize it or host your own version? Forking gives you a full copy of the repository under your own GitHub account.

**Steps:**
1. Visit the repo: [https://github.com/Archi677/list](https://github.com/Archi677/list)
2. Click the **Fork** button (top-right) to create your own copy.
3. In your fork, go to **Settings → Pages**.
4. Under **Source**, select the branch (usually `main`) and the root folder (`/`).
5. Click **Save**. GitHub will build and deploy your site.
6. Your app will be live at `https://<your-username>.github.io/list/`.

**Or clone it locally:**

```bash
git clone https://github.com/Archi677/list.git
cd list
```

Then open `index.html` in any browser. You can also serve it with a simple static server:

```bash
# Python 3
python -m http.server 8000

# or Node.js (if you have npx)
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

### 3️⃣ Download the Latest `index.html` File

Prefer to keep it offline or host it yourself on another platform? The entire app is a single HTML file, so you can download it and run it anywhere.

**Steps:**
1. Go to the repo: [https://github.com/Archi677/list](https://github.com/Archi677/list)
2. Click on **`index.html`**.
3. Click the **Raw** button (or the **Download** icon).
4. Save the file as **`index.html`**.
5. Open it in any modern browser — that's it! 🎉

**Tips:**
- You can rename the file if you like, but keep the `.html` extension.
- You can copy it to a USB drive, email it to yourself, or host it on any static server (Netlify, Vercel, Surge, etc.).
- Because it's self-contained, it works offline once downloaded.

> 💡 **Note:** Because the app is a single self-contained HTML file, you can also copy it to a USB drive, host it on any static server, or share it directly.

---

### 🧰 Troubleshooting Usage

| Problem | Likely Cause | Solution |
|--------|--------------|----------|
| Page is blank | Opened the wrong file | Make sure you opened `index.html`, not `index(old).html` |
| Styles look broken | File was saved incorrectly | Re-download the raw `index.html` and open it directly |
| GitHub Pages shows 404 | Pages not enabled or wrong branch | Check **Settings → Pages** and ensure the correct branch/folder is selected |
| Changes don't appear after fork | GitHub Pages build delay | Wait a minute and refresh; check the **Actions** tab for build status |
| App doesn't work offline | Opened from a URL | Download the file locally and open it from your file system |

---

## 🗂️ Project Structure

```
list/
├── .github/
│   └── workflows/        # GitHub Pages deployment workflow
├── index.html            # Main application (latest version)
├── index(old).html       # Previous version (kept for reference)
└── README.md             # This file
```

### File-by-File Breakdown

- **`.github/workflows/`** — Contains the GitHub Actions workflow that automatically deploys the app to GitHub Pages whenever changes are pushed to the main branch.
- **`index.html`** — The main application. This is the file you open in a browser. It contains the HTML structure, CSS styles, and JavaScript logic in a single file.
- **`index(old).html`** — A previous version of the app, preserved for reference. Useful for comparing changes or rolling back.
- **`README.md`** — Documentation for the project (this file).

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| Structure | **HTML5** | Semantic markup for the app's UI |
| Styling | **CSS3** | Layout, colors, typography, responsiveness |
| Logic | **JavaScript** | Interactivity, list management, DOM updates |
| Hosting | **GitHub Pages** | Free static hosting directly from the repo |
| Automation | **GitHub Actions** | Automated deployment on push |
| Version Control | **Git** | Tracking changes and collaboration |

### Why No Framework?

The project intentionally avoids frameworks and build tools. Benefits:

- **Zero setup** — No `npm install`, no config files.
- **Portable** — One file runs anywhere.
- **Educational** — Easy to read and learn from.
- **Fast** — No bundle to download or parse.
- **Resilient** — No dependency updates or breaking changes.

---

## ⚙️ How It Works

At a high level:

1. The browser loads `index.html`.
2. The embedded CSS styles the page.
3. The embedded JavaScript handles user interactions:
   - Reading input from the user.
   - Updating the list in the DOM.
   - (Optionally) storing state in the browser.
4. Because everything is client-side, no network requests are made after the initial page load.

### Data & Privacy

- **No servers** — The app does not send data anywhere.
- **No accounts** — There is nothing to sign up for.
- **No tracking** — No analytics or third-party scripts are included.
- **Local only** — Any state is kept in your browser (and may be lost on refresh unless persistence is added).

If persistence is added in the future, it will likely use the browser's `localStorage` API, which stores data locally on your device.

---

## 🗺️ Roadmap

This is a living list of ideas. Contributions are welcome!

### Short-Term
- [ ] Add persistent storage via `localStorage`.
- [ ] Add a "clear list" button.
- [ ] Improve mobile responsiveness.
- [ ] Add basic input validation and empty-state messaging.

### Medium-Term
- [ ] Mark items as "bought" with a checkbox.
- [ ] Support multiple lists (e.g., Groceries, Hardware, Party).
- [ ] Add drag-and-drop reordering.
- [ ] Add a dark mode toggle.

### Long-Term
- [ ] Export/import lists as JSON or text.
- [ ] Optional sync via a user-provided backend.
- [ ] Progressive Web App (PWA) support for installability.
- [ ] Internationalization (i18n) for multiple languages.

> Have an idea? Open an issue on GitHub and let's discuss it.

---

## 🤝 Contributing

Contributions are welcome and appreciated! Whether it's a bug report, a feature suggestion, or a pull request, your input helps make this project better.

### How to Contribute

1. **Fork** the repository.
2. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** — keep them focused and well-described.
4. **Test** by opening `index.html` in a browser.
5. **Commit** with a clear message:
   ```bash
   git commit -m "Add: short description of your change"
   ```
6. **Push** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request** against the `main` branch of the original repo.

### Contribution Guidelines

- Keep changes small and focused.
- Follow the existing code style (plain HTML/CSS/JS).
- Update the README if your change affects usage or features.
- Be respectful and constructive in discussions.

### Reporting Bugs

When reporting a bug, please include:

- A clear description of the problem.
- Steps to reproduce it.
- The browser and device you're using.
- Screenshots if possible.

---

## 📜 Code of Conduct

This project follows a simple principle: **be kind and constructive**. Harassment, discrimination, or disrespectful behavior will not be tolerated. Everyone is welcome to contribute regardless of experience level, background, or identity.

---

## ❓ FAQ

**Q: Do I need to install anything?**  
A: No. The app is a single HTML file. Just open it in a browser.

**Q: Is my data sent to a server?**  
A: No. Everything runs in your browser. No data is transmitted.

**Q: Does it work offline?**  
A: Yes, if you download `index.html` and open it locally. The hosted version requires an internet connection to load initially.

**Q: Can I use this for my own project?**  
A: Yes, it's open for personal and educational use. Please credit the original author.

**Q: How do I update my forked version?**  
A: Sync your fork with the upstream repo via GitHub's "Sync fork" button, or pull changes locally.

**Q: Why is there an `index(old).html` file?**  
A: It preserves a previous version of the app for reference and rollback.

**Q: Can I contribute if I'm a beginner?**  
A: Absolutely. Beginner-friendly contributions are encouraged.

**Q: Who built this?**  
A: Archisman Sakhari (Vanta-Forge), a Class 10 student, built it entirely on a phone.

---

## 🙏 Acknowledgements

- Thanks to the open-source community for inspiration and tools.
- Thanks to GitHub for free hosting via GitHub Pages.
- Thanks to everyone who tries the app, shares feedback, or contributes.
- Special thanks to anyone who believes that you don't need expensive hardware to build something useful.

---

## 👨‍💻 About the Developer

**Archisman Sakhari** (aka **Vanta-Forge**) is a **Class 10 student** who built this entire project **on a phone** — from writing the code to deploying it. This project is a testament to curiosity, dedication, and the belief that you don't need expensive hardware to build something useful.

When not coding, he's likely exploring new ideas, learning web development, and building projects under the **Vanta-Forge** name.

---

## 📬 Contact

Have feedback, ideas, or just want to say hi? Reach out:

- 📧 **vantaforgecodes@gmail.com**
- 📧 **buildsaurora@gmail.com**

Feel free to open an **issue** or **pull request** on the [GitHub repo](https://github.com/Archi677/list) as well!

---

## 📄 License

This project is open and available for personal and educational use. Please credit the original author if you build upon it.

If you're unsure whether your use case is allowed, reach out via the contact emails above.

---

<p align="center">
  Made with ❤️ on a phone by <b>Vanta-Forge</b>
</p>
