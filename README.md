MangaLens 🔍

An AI-powered browser tool for translating manga and comics instantly using Google Gemini.

MangaLens is a client-side web application that allows users to upload raw manga pages, perform OCR (Optical Character Recognition), and translate Japanese text to English while preserving the reading experience.

✨ Features

Gemini AI Integration: Uses Google's Gemini 2.5 Flash/Pro models for high-accuracy translation.

Batch Processing: Translate 100+ pages automatically with a single click.

Smart Image Processing:

Color Mode: Optimized for colored comics/manhwa.

B&W Mode: Features a contrast cleaner and threshold slider to remove screentones from traditional manga.

Dynamic PDF Generation: Exports translated chapters into a PDF with auto-sizing text and side-by-side translation layout.

Privacy First: Runs entirely in the browser. Your API keys and images are processed locally or sent directly to Google's API; they never touch a third-party server.

🚀 How to Use

Get an API Key: Get a free API key from Google AI Studio.

Open the App: [Link to your live site goes here]

Upload Images: Drag and drop your raw .jpg or .png files.

Configure: Paste your API key and select the appropriate mode (Color/B&W).

Translate: Click the "Wand" icon to batch translate everything.

Download: Click "Download PDF" to get your translated chapter.

🛠️ Tech Stack

Frontend: React 18 (via CDN), Tailwind CSS

PDF Generation: jsPDF

AI Model: Google Gemini API (2.5 Flash)

📄 License

This project is for educational and personal use. Please respect copyright laws in your country regarding the translation of copyrighted material.
