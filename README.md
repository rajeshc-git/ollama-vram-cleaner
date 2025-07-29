# 🧠💨 Ollama Memory Unloader

⚡ **Free Up System Memory (RAM) and GPU VRAM** Instantly by Unloading Ollama Models ⚡

🚀 Whether you're running low on resources or just want to keep your system snappy, this lightweight tool lets you **unload inactive Ollama models** to save memory and VRAM. Perfect for developers, ML enthusiasts, and anyone juggling multiple models!

---

## 🧩 Features

✅ One-click unloading of models  
✅ Frees up both **System RAM** and **GPU VRAM**  
✅ CLI & Script-friendly  
✅ Lightweight – no bloat  
✅ Works seamlessly with Ollama-installed models  

---

## 🔧 How It Works

This tool interacts with the Ollama runtime and ensures that any idle or loaded models are **safely unloaded** from both system memory and GPU, giving you back your resources for other tasks.

---

## 📦 Installation

```bash
git clone https://github.com/rajeshc-git/ollama-vram-cleaner.git
cd ollama-vram-cleaner
# Optional: create venv
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
🚀 Usage
🖥️ Command Line
bash
Copy
Edit
python unload.py
You’ll see a list of loaded models and confirmation once they’re successfully unloaded.

🔒 Safe to Use
✅ Doesn't delete or corrupt models
✅ Simply unloads from memory, just like closing a tab
✅ Re-load anytime using your regular Ollama commands

🌍 Cross-Platform
🪟 Windows

🍎 macOS

🐧 Linux

🛠 Requirements
Python 3.7+

Ollama properly installed and configured

🙌 Contributions Welcome
Found a bug? Have a feature request? PRs and issues are always welcome!

🧙‍♂️ Maintainer
Made with ❤️ by Rajesh

🧼 Keep It Clean. Keep It Fast.
“Unload the unused. Unleash the speed.” ⚡
