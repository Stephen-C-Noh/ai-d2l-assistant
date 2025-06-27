
# Project Proposal: AI-Powered Web Assistant for D2L (Brightspace)

## Project Overview

The AI-Powered Web Assistant aims to enhance the learning experience on D2L (Brightspace) by leveraging OCR technology and AI to extract, summarize, and provide contextual information from course materials. This tool will help students access summaries, examples, practice questions, and educational videos directly from their course content.

## Objectives

1. **Content Extraction**: Capture and extract text from embedded PDFs, DOCX, and PPTX files in D2L.
2. **User Interaction**: Provide options for summaries, examples, practice questions, and video links.
3. **Web Search Integration**: Use Google Search API to fetch relevant examples, questions, and videos.
4. **User-Friendly Display**: Present results in a split-screen web app for easy reference alongside D2L.

## Features

- **Screen Content Detection**: Capture visible screen content from D2L.
- **OCR Integration**: Extract text from images using Tesseract.js or Google Vision API.
- **AI Processing**: Summarize content and generate practice questions using OpenAI API.
- **Web Search**: Fetch examples, questions, and videos using Google Custom Search API.
- **Responsive UI**: Display results in a clean, split-screen-friendly web app.

## Tech Stack

- **Frontend**: React, TypeScript
- **Backend**: Node.js (Express) or Python (Flask/FastAPI)
- **OCR**: Tesseract.js (browser) or Tesseract (Python)
- **AI/NLP**: OpenAI API or HuggingFace Transformers
- **Search**: Google Custom Search API
- **Browser Extension**: JavaScript (Manifest v3)
- **Deployment**: Vercel (frontend), Render/Railway (backend)

## Roadmap

### Phase 1: MVP Foundation (Weeks 1–3)
- Set up project structure (frontend, backend, extension).
- Build Chrome Extension to capture visible tab screenshot and send image to backend.
- Integrate OCR (Tesseract.js or Google Vision API) to extract text from screenshot.
- Add Summarization (OpenAI API) to summarize extracted text.

### Phase 2: Core Features (Weeks 4–6)
- Add UI options for Summary, Examples, Practice Questions, and Video Links.
- Integrate Google Search API to fetch examples, questions, and videos.
- Build React app to display results in a split-screen-friendly layout.

### Phase 3: UX & Performance (Weeks 7–8)
- Improve OCR accuracy with image preprocessing.
- Enhance UI/UX with floating sidebar or draggable window.
- Optimize API usage with text chunking and caching.

### Phase 4: Testing, Deployment & Feedback (Weeks 9–10)
- Cross-browser testing (Chrome, Edge).
- Deploy web app (Vercel/Netlify) and backend (Render/Railway).
- Package Chrome Extension for installation.
- Collect feedback from users.

## Timeline

| Phase | Duration | Focus |
|-------|----------|-------|
| Phase 1 | Weeks 1–3 | OCR + Summarization |
| Phase 2 | Weeks 4–6 | Search + UI Options |
| Phase 3 | Weeks 7–8 | UX + Accuracy |
| Phase 4 | Weeks 9–10 | Testing + Deployment |

## Cost Analysis

| Component | Estimated Cost | Notes |
|-----------|----------------|-------|
| OCR Engine | Free (Tesseract) or ~$20/month (Google Vision API) | Tesseract is local and free; cloud APIs are more accurate. |
| Frontend (Web App) | Free (React, HTML/CSS) | Hosting may cost if using services like Vercel or Netlify. |
| Backend (API, Processing) | ~$5–$25/month | Use Node.js or Python Flask. Host on Render, Railway, or Heroku. |
| Google Search API | $5–$20/month | Based on usage (100 free queries/day). |
| Browser Extension (for screen capture) | Free | Built with JavaScript. |
| Video Hosting/Embedding | Free | YouTube API is free with limits. |
| **Total (Monthly)** | **$10–$50** | Depending on scale and API usage. |

## Conclusion

This AI-powered web assistant for D2L aims to significantly enhance the learning experience by providing quick access to summaries, examples, practice questions, and educational videos. With a clear roadmap, manageable costs, and a focus on user experience, this project is both ambitious and feasible for student developers.

