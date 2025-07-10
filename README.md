1. **Install Frontend Dependencies**

```bash
cd frontend
npm install
npm run dev
```

2. **Install Backend Dependencies**

```bash
cd ../backend
npm install
node server.js
```

3. **Configure Environment Variables**

Create `.env` files for both `frontend` and `backend` as needed. Include:

* MongoDB URI
* JWT Secret
* Gemini AI API Key

---

## 👀 How the AI Works

The recommendation system uses **Gemini AI** to analyze user input based on **mood**, **genre preference**, and **recent watch history**. It responds with personalized movie suggestions that feel more human than just trending/popular filters.

---
