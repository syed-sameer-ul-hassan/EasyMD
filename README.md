🚀 EasyMD

«A block-based README builder built with Tauri + React.
Create beautiful, structured Markdown files visually — no formatting headaches.»

---

📸 Preview

«(Add screenshots here later)»

---

✨ Features

- 🧱 Block-based editing (no raw Markdown writing)
- 🔀 Drag & drop sections
- 👀 Live preview (GitHub-style rendering)
- 🗂 Project dashboard with history
- 📦 Export to "README.md"
- 🖼 Image upload & management
- 🎨 Clean dark mode UI (Linear-inspired)

---

📊 Development Timeline

gantt
    title EasyMD 4-Week Development Timeline
    dateFormat  YYYY-MM-DD

    section Foundation (Week 1–2)
    Project Setup        :a1, 2026-05-01, 3d
    Data Models          :a2, after a1, 4d
    UI Layout            :a3, after a2, 5d

    section Core Features (Week 3)
    Block System         :b1, after a3, 3d
    Drag & Drop          :b2, after b1, 2d
    Markdown Compiler    :b3, after b2, 2d

    section Advanced (Week 4)
    Dashboard & History  :c1, after b3, 3d
    Templates            :c2, after c1, 2d
    Image Handling       :c3, after c2, 2d
    Export System        :c4, after c3, 2d

    section Release
    Testing              :d1, after c4, 2d
    UI Polish            :d2, after d1, 2d
    Documentation        :d3, after d2, 1d
    Release v1.0.0       :milestone, after d3, 1d

---

🧠 Tech Stack

Frontend

- React + TypeScript
- Tailwind CSS
- Zustand (state management)
- dnd-kit (drag & drop)
- tiptap (rich text editor)
- react-markdown

Backend

- Tauri v2 (Rust)

---

🏗 Architecture

- Sections (Blocks) → Modular content units
- Zustand Store → Centralized state
- Markdown Compiler → Converts blocks → Markdown
- Preview Engine → Real-time rendering

---

📦 Installation

git clone https://github.com/your-username/easymd.git
cd easymd
npm install
npm run tauri dev

---

🖥 Supported Platforms

- Windows
- macOS
- Linux

---

📁 Project Structure

src/
 ├── components/
 ├── store/
 ├── utils/
 ├── types/
 └── pages/

---

🎯 Roadmap (Post v1.0)

- 🤖 AI block generator
- ✍️ Content rewriting
- 🔗 Auto badge suggestions
- 📊 README analytics
- 🌐 Cloud sync

---

🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch
3. Commit your changes
4. Open a Pull Request

---

📄 License

MIT License

---

⭐ Support

If you like this project, give it a star ⭐

---