# 🧠 Easy Chatbot Backend Setup Guide (Command Reference)

This document walks you through every terminal command you’ll need to set up and run the backend for the Easy Chatbot project.

---

## ✅ 1. Navigate to the Backend Folder

```powershell
cd "C:\Users\YourName\Desktop\Easy Chatbot Starter Kit\backend"
```

📌 Replace `YourName` with your actual Windows username.

---

## ✅ 2. Create a Virtual Environment

```powershell
python -m venv venv
```

This creates a new virtual environment inside the `backend` folder.

---

## ✅ 3. Activate the Virtual Environment

### PowerShell (recommended):
```powershell
.\venv\Scripts\Activate.ps1
```

If you get a security error like *"running scripts is disabled"*, use this first:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```

Then activate again:

```powershell
.\venv\Scripts\Activate.ps1
```

---

## ✅ 4. Install Required Packages

```powershell
pip install -r requirements.txt
```

This installs FastAPI, LangChain, ChromaDB, OpenAI SDK, and other dependencies.

---

## ✅ 5. Create Your `.env` File

```powershell
copy .env.example .env
```

Then open `.env` in your editor and add your OpenAI API key:

```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

---

## ✅ 6. Run the Chatbot Backend

```powershell
uvicorn main:app --reload
```

You should see:

```
Uvicorn running on http://127.0.0.1:8000
```

This means your backend is running and ready to receive questions from the frontend.

---

✅ You’re now ready to test the chatbot locally!
