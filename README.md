# Litogen Lite

**Litogen Lite** is a lightweight, fully browser-based lithophane STL generator.  
It allows you to generate **triangle** and **circle** lithophanes directly in your browser — no backend, no uploads, no installation.

👉 **Try Now:**  
https://erolcanulutas.github.io/Litogen-Lite/

---

## ✨ Features

- 🔺 Equilateral **triangle** lithophane generation  
- ⚪ Perfect **1:1 circle** lithophane generation  
- 🖼️ Image import and in-browser editing  
- 📐 Precise size and thickness control (mm-based)  
- 🧵 STL generation ready for 3D printing  
- ⚡ Runs fully **client-side** using Web Workers  
- 🔒 No images are uploaded — everything stays on your device

---

## 🧠 How It Works

Litogen Lite uses a client-side pipeline:

1. Image is processed in the browser  
2. Height map is generated based on brightness  
3. Geometry is built for the selected shape  
4. STL is generated using a Web Worker  
5. File is downloaded directly to your device  

No server, no API, no tracking.

---

🙌 Author

Created by Erol Can Ulutaş
If you enjoy the project or have ideas for improvements, feel free to open an issue or a pull request.
