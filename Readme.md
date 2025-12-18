# 🚀 SlideForge  
**From prompts to presentation**

SlideForge is an AI-powered presentation builder that converts high-level user prompts into **fully editable, export-ready PowerPoint decks** with a modern SaaS experience. Users can generate slides, edit content in real time, regenerate visuals, and export polished PPTs instantly.

🔗 **Live Demo:** https://slide-forge-frontend.vercel.app/

🧪 Example Use Cases:

Students creating presentations quickly
Founders building pitch decks
Educators preparing lecture slides
Professionals generating reports

---

## ✨ Features

- 🧠 **Prompt-based Generation**  
  Generate presentations using title, description, tone, purpose, audience, and slide count.

- ✏️ **Real-Time Editing**  
  Edit titles, bullet points, and explanations after generation.

- 🖼️ **AI Image Integration**  
  Auto-fetch relevant images with one-click regeneration.

- 🎨 **Modern Dark SaaS UI**  
  Clean dark theme with smooth loaders and premium styling.

- 📂 **PowerPoint Export**  
  Export decks as `.pptx` files using a custom Python layout engine.

- ⚡ **Async UX**  
  Loading states for generation and export ensure smooth interaction.

---

## 🧩 How It Works

1. User submits presentation intent  
2. Backend generates structured slide data  
3. Slides are editable in real time  
4. Final deck is exported as a PowerPoint file  

---

## 🛠️ Tech Stack

**Frontend**
- React
- Context API
- Axios
- Tailwind CSS

**Backend**
- FastAPI
- Python
- python-pptx
- LangChain
- Groq API

**Other**
- Image APIs
- Blob-based file streaming

---

## 🧠 Design Highlights

- Layout control to prevent text overflow
- Font scaling based on slide density
- Fresh PPT instance per export
- Clean separation of generation and export logic

---

## 🚀 Getting Started

```bash
cd Backend
pip install -r requirements.txt
uvicorn app:app --reload

cd Frontend/SlideForge
npm install
npm run dev
