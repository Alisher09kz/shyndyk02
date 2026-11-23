# Шындық – AI фактчекер (Vercel)

Файлдар:
- `index.html` – сайт (бұрынғы дизайн сақталды)
- `api/check.js` – серверлік функция (Gemini кілті осында қорғалған)
- `vercel.json` – функцияның жұмыс уақыты

Қажетті Environment Variables (Vercel → Settings → Environment Variables):
- `GEMINI_API_KEY` – міндетті (aistudio.google.com → Get API key)
- `GEMINI_MODEL` – міндетті емес (әдепкі: gemini-flash-latest)
- `TAVILY_API_KEY` – міндетті емес (интернеттен іздеу үшін, tavily.com)

Өзгертуден кейін міндетті түрде Redeploy жасаңыз.
