# 🧩 Multiple Window 3D Scene using Three.js

This project demonstrates a **3D scene rendered using [Three.js](https://threejs.org/)** with **multi-window management** capabilities.

Built for developers and enthusiasts to explore advanced techniques in window synchronization and 3D graphics rendering in web browsers.

---

## 🚀 Features
- Render 3D cubes using **Three.js**.
- Manage multiple browser windows dynamically.
- Synchronize window data using **LocalStorage**.
- Real-time update of objects based on window position and size.

---

## 🛠 Project Structure
| File | Purpose |
|:-----|:--------|
| `index.html` | Entry point HTML file loading the scripts. |
| `main.js` | Main logic for initializing Three.js scene and rendering. |
| `WindowManager.js` | Class to manage window information and synchronization. |
| `three.r124.min.js` | Minified Three.js library. |

---

## 🔥 How to Run Locally

1. **Install Python** (if not installed):  
   [Download Python](https://www.python.org/downloads/)

2. **Navigate to project directory** using PowerShell or Command Prompt:
   ```bash
   cd "E:\WEB DEV\multiple window\multipleWindow3dScene-main"
   ```

3. **Start a local HTTP server**:
   ```bash
   python -m http.server 8000
   ```

4. **Open your browser** and visit:
   ```
   http://localhost:8000
   ```

✅ You will see the 3D scene rendered in the browser.

---

## 📷 Screenshots

![Preview of 3D scene](Screen_Recording1.gif)

---

## 📚 Technologies Used
- [Three.js](https://threejs.org/) — 3D rendering library
- JavaScript (ES6 Modules)
- HTML5
- LocalStorage API (for window management)

---

## 📝 License
This project is open-sourced under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙏 Acknowledgments
- Thanks to the Three.js community for amazing documentation and examples.
- Inspired by experimental multi-window graphics demos.

---

## 📢 Important Notes
> Always serve this project via a **local server** (`http://localhost:8000`) and **not by directly opening `index.html`** to avoid CORS and module loading issues.
