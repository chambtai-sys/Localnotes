# 📑 Localnotes

**A professional, lightweight, localhost notepad for humans.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

Localnotes is a minimalist, local-first notepad application that runs on your local machine. It focuses on privacy, speed, and a clean writing experience with full Markdown support.

## ✨ Features

- **📂 File Management**: Create, edit, and delete notes directly on your filesystem.
- **🚀 Real-time Preview**: Live Markdown rendering as you type.
- **💾 Auto-save**: Never lose a word; notes save automatically while you write.
- **🔍 Fast Search**: Find your notes instantly with the sidebar search.
- **🌙 Dark Mode**: A sleek, zinc-dark interface for late-night coding/writing sessions.
- **🔗 Zero Build Step**: Run it anywhere with just Python and Flask.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/chambtai-sys/Localnotes.git
   cd Localnotes
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```

4. **Open in browser**:
   Navigate to `http://localhost:5000`.

## 📁 Project Structure

```text
Localnotes/
├── notes/          # Your markdown files live here
├── templates/      # UI HTML files
├── app.py          # Flask Backend
├── README.md       # Project documentation
└── requirements.txt # Python dependencies
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
