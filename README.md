# ATTechnology – Company Consulting Website (FastAPI + TailwindCSS)

This is a modern, single-page website for **ATTechnology** — a strategic consulting firm. It’s built using **FastAPI (Python)** and styled with **Tailwind CSS** and **Flowbite**.

🖥️ You can run it locally — even if you’ve never used VS Code or Python before.

---

## 💡 Features

- Responsive one-page design (Home, About, Services, Career, Contact)
- Built with FastAPI (Python backend) + HTML (Jinja templates)
- Styled using Tailwind CSS (modern utility-first framework)
- Flowbite components (optional UI enhancements)
- No JavaScript frameworks required

---

## 📁 Project Structure

```
attechnology/
├── app/
│   ├── main.py               # FastAPI app entry
│   ├── templates/
│   │   └── index.html        # Single-page HTML layout
│   ├── static/
│   │   └── css/              # (Optional) extra custom styles
├── run.py                    # Starts the FastAPI server
├── README.md                 # You're reading this!
```

---

## 🔧 Requirements

You only need:

- [Python 3.9+](https://www.python.org/downloads/)
- A terminal (Command Prompt, PowerShell, Terminal, etc.)

No need for VS Code or IDEs.

---

## 🚀 How to Run the Website Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/attechnology.git
cd attechnology
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

- On **Windows**:
  ```bash
  venv\Scripts\activate
  ```

- On **Mac/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 4. Install the dependencies

```bash
pip install fastapi uvicorn jinja2
```

### 5. Run the website

```bash
python run.py
```

### 6. Visit it in your browser

Go to:

```
http://127.0.0.1:8000
```

---

## 📸 Preview

![Screenshot](https://your-screenshot-url.com/screenshot.png)

> Replace the link above with your screenshot URL or upload one to GitHub.

---

## ❓ Common Issues

- **`ModuleNotFoundError: fastapi`**  
  → You forgot to install the packages (`pip install fastapi uvicorn jinja2`)

- **Templates not found**  
  → Make sure `index.html` is inside the `app/templates/` folder

- **Page doesn’t open?**  
  → Make sure you're running `run.py` and not `main.py`

---

## 📄 License

This project is free and open-source. You can use, modify, and share it for personal or commercial use.

---

> Built with ❤️ using Python, FastAPI, and Tailwind.
