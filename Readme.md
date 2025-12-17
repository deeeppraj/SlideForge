# 🚀 SlideForge  
**From prompts to presentation**

SlideForge is an AI-powered presentation builder that transforms high-level user prompts into **fully editable, export-ready PowerPoint decks** with a modern SaaS experience. Users can generate slides from intent, edit content in real time, regenerate visuals, and export polished PPTs instantly.

🧪 Example Use Cases:
Students creating quick presentations
Founders building pitch decks
Educators preparing lecture slides
Professionals generating reports or briefings

---

## ✨ Features

- 🧠 **Prompt-based Generation**  
  Generate presentations using simple inputs like title, description, tone, purpose, target audience, and slide count.

- ✏️ **Real-Time Slide Editing**  
  Edit titles, bullet points, and explanations live after generation.

- 🖼️ **AI Image Integration**  
  Automatically fetches relevant images per slide with one-click regeneration.

- 🎨 **Premium Dark SaaS UI**  
  Modern dark theme with glassmorphism, smooth loaders, and clean typography.

- 📂 **PowerPoint Export**  
  Export presentations as `.pptx` files using a custom Python layout engine.

- ⚡ **Asynchronous UX**  
  Loading indicators during generation and export for a smooth user experience.

---

## 🧩 How It Works

1. User submits high-level presentation intent  
2. Backend generates structured slide data  
3. Slides are editable in the UI and stored in global state  
4. Final deck is exported as a PowerPoint file

---

## 🛠️ Tech Stack

### Frontend
- React
- Context API (Global State)
- Axios
- Tailwind CSS

### Backend
- FastAPI
- Python
- python-pptx
- langchain
- Groq-api

### Other
- Image APIs for slide visuals
- Blob-based file streaming for exports

---


---

## 🧠 Design Highlights

- Dynamic layout control to prevent text overflow
- Font scaling based on slide density
- Fresh PowerPoint instance per export (no state leakage)
- Clean separation of generation and export logic

---

## 🚀 Getting Started

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app:app --reload

cd frontend/SlideForge
npm install
npm run dev

Export -> Workflow:
Exporting Presentations
Click Generate Presentation after filling prompts
Edit slides as needed
Click Export PPT
Download starts automatically


👨‍💻 Author
Deepraj
Built with ❤️ as a full-stack AI product prototype.
