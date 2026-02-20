# 🚀 Code Studio Pro — Elite Edition

**Code Studio Pro** is a fully browser-based development environment built as a single HTML application. It provides a modern IDE experience including file management, Monaco code editor, terminal, preview, themes, extensions UI, and local encrypted workspace storage.

The project runs entirely on the client side — no backend required.

---

## ✨ Features

* 🧠 Monaco Editor integration (VS Code–like editing)
* 📁 Virtual File System (browser local storage)
* 🔐 Encrypted workspace login
* 📂 Explorer, Search, Git mock UI
* 🎨 Multiple themes (Dracula, Monokai, Nord, etc.)
* 🧩 Extension panel (UI simulation)
* 🖥 Integrated terminal (xterm.js)
* ▶ Code execution mock runtime
* 🌐 HTML live preview
* 🎯 Command palette
* 🧘 Zen mode
* ⚙ Settings panel
* 📦 Export workspace as ZIP

---

## 📂 Project Structure

```
index.html        → Main application file (complete IDE)
```

The entire application UI, logic, styles, and state management are embedded in one HTML file. 

---

## 🛠 Requirements

Since this is a pure client-side application, only the following are needed:

* Modern web browser (Chrome, Edge, Firefox recommended)
* Internet connection (for CDN libraries)

  * Monaco Editor
  * xterm.js
  * JSZip

No Node.js or server setup required.

---

## ▶ How to Run

### ✅ Method 1 — Direct Open (Recommended)

1. Download the project.
2. Open **index.html** in any modern browser.
3. The IDE will load instantly.

---

### ✅ Method 2 — Local Server (Optional)

If you want proper module loading or preview behavior:

#### Using Python

```bash
python -m http.server 8000
```

#### Using Node

```bash
npx serve .
```

Then open:

```
http://localhost:8000
```

---

## 🔐 Workspace Usage

1. Click **Sign In**.
2. Register a username and password.
3. Your workspace will be stored encrypted in browser local storage.

> ⚠ Clearing browser storage will erase workspace.

---

## 📄 Basic Workflow

### Create File

* Click **+ New**
* Enter filename with extension

### Edit Code

* Files open in Monaco editor
* Tabs support multiple files

### Run Code

* Click **Run**
* Output appears in Output/Terminal panel

### HTML Preview

* Click **Preview ↗**
* Opens rendered HTML

### Export Workspace

* Click **📦 Export**
* Downloads ZIP of all files

---

## 🎯 Keyboard Shortcuts

| Action          | Shortcut     |
| --------------- | ------------ |
| Command palette | Ctrl + P     |
| Save            | Ctrl + S     |
| Run             | Ctrl + Enter |
| Toggle terminal | Ctrl + `     |
| Zen mode        | F11          |
| Toggle sidebar  | Ctrl + B     |

---

## ⚙ Settings

Accessible via:

* Activity bar ⚙
* Status bar language click
* Command palette

Configurable:

* Theme
* Font size
* Word wrap
* Minimap
* Auto save
* Tab size
* Ligatures

---

## 📦 Libraries Used

* Monaco Editor
* xterm.js
* JSZip
* Google Fonts

---

## ⚠ Limitations

* Code execution is simulated (no real compiler runtime)
* Git panel is UI mock
* No backend persistence
* Storage limited by browser quota

---

## 💡 Possible Improvements

* Real execution via WebAssembly sandbox
* Cloud workspace sync
* Collaborative editing
* Extension API
* Package manager integration

---

## 👨‍💻 Author Notes

This project demonstrates:

* Advanced UI engineering
* Browser IDE architecture
* State management patterns
* Monaco integration
* Virtual filesystem concepts

---

## 📜 License

Use freely for learning and experimentation.

---

**Enjoy building with Code Studio Pro 🚀**
