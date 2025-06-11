## 🚀 How to Use

### 1. 🔧 Setup Backend (Render.com)

1. Go to [https://render.com](https://render.com)
2. Create a new Web Service
3. Connect this `/backend` folder to your repo or upload manually
4. Use the provided `render.yaml`
5. Set an environment variable:  
   `OPENAI_API_KEY=your-openai-api-key`
6. Deploy! Copy your backend URL (e.g. `https://your-backend.onrender.com`)

---

### 2. 💬 Customize Your Chatbot

- Open `backend/docs/sample.txt`
- Replace the content with your own (portfolio, product info, etc.)
- Redeploy the backend to update your chatbot’s knowledge

---

### 3. 🖥️ Use the Frontend

1. Open `frontend/chatbot.js`
2. Replace the API URL in the `fetch()` call with your Render URL
3. Open `index.html` in a browser — your chatbot is live!

---

### 4. 💡 Try Questions Like:

- “What is the history of surfing in Hawaii?”
- “Who is Duke Kahanamoku?”
- “What is big wave surfing?”
- “What do Hawaiian surfboards look like?”

---

## ✅ Tech Used

- HTML / CSS / JS
- OpenAI API
- LangChain + FastAPI
- ChromaDB vector store
- Render.com for hosting

---

## 🙏 License

MIT License — free to use, share, or remix.
