# Walkthrough Creator 🎯

**Turn static screenshots into gamified, interactive lessons.**

[![Status](https://img.shields.io/badge/Status-Live-success)](https://shangle.me/Walkthrough-Creator/)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local-green)](https://shangle.me/Walkthrough-Creator/app.html)

[**Launch Editor**](https://shangle.me/Walkthrough-Creator/app.html) | [**View Website**](https://shangle.me/Walkthrough-Creator/)

---

## 🚀 What is this?

**Walkthrough Creator** is a single-page web application that lets you build interactive software tutorials in minutes. 

Most walkthrough tools require monthly subscriptions, browser extensions, and user accounts. This tool does not. It runs entirely in your browser, saves no data to any server, and exports your finished tutorial as a single, standalone HTML file that you can email, host, or share anywhere.

## ✨ Features

* **🖱️ Gamified Interaction:** Users don't just read; they do. They must find and click the correct interface elements to advance, reinforced by instant feedback and animations.
* **📦 Single-File Export:** The entire walkthrough (images, logic, and styles) is compiled into one \`walkthrough.html\` file. No dependencies, no backend required.
* **🔒 Privacy First:** 100% Client-side. Your screenshots and captions never leave your device.
* **⚡ Zero Bloat:** No signups. No database. No tracking cookies.
* **📱 Mobile Responsive:** The editor and the exported tutorials work great on desktops, tablets, and phones.

## 🛠️ How it Works

1.  **Upload:** Drag and drop your interface screenshots into the editor. We automatically compress them for web use.
2.  **Interact:** Click anywhere on the image to place a "Hotspot". Add a caption to guide your user.
3.  **Export:** Click the button to download your standalone HTML file.

## 💻 Tech Stack

* **Core:** Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN)
* **Icons:** FontAwesome
* **Architecture:** Single Page Application (SPA) with in-browser DOM injection for exports.

## 🏃‍♂️ Running Locally

Because this project uses no backend, you don't need \`npm\`, \`node\`, or \`docker\`.

1.  Clone the repo:
    \`\`\`bash
    git clone https://github.com/shangle/Walkthrough-Creator.git
    \`\`\`
2.  Navigate to the folder:
    \`\`\`bash
    cd Walkthrough-Creator
    \`\`\`
3.  Open \`app.html\` in your browser.

## 🤝 Contributing

This tool is designed to be simple and maintainable. If you have ideas for new features (like branching paths or different export themes), feel free to open a PR!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
