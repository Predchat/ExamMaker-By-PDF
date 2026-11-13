# ExamForge 🎓

AI-powered exam generator that creates exams from PDF lesson files. Works completely in your browser with no backend needed.

## Features

✨ **AI-Powered Generation**
- Generate exams from PDF lessons using AI
- Support for **Anthropic (Claude)** and **OpenRouter (100+ models)**
- Multiple question types: Multiple Choice, True/False, Short Answer

📚 **Question Bank**
- Save and manage generated exams
- Review past exams
- Export exams as text files

🎨 **Beautiful UI**
- Professional, modern design
- Light/Dark mode support
- Fully responsive for mobile & desktop
- Natural, readable fonts

📱 **Progressive Web App (PWA)**
- Install as a standalone app (no browser window)
- Works offline with cached content
- Save API keys and preferences locally

## Getting Started

### Using the Web Version

1. **Open in Browser**: https://github.com/YOUR_USERNAME/ExamForge
   - Enable GitHub Pages in repo settings
   - Access at: `https://YOUR_USERNAME.github.io/ExamForge/`

2. **Install as App** (Chrome):
   - Open the URL in Chrome
   - Click the "Install" button (address bar)
   - Runs as a standalone app!

### Setup

1. **Get an API Key**:
   - **Anthropic**: Get at [console.anthropic.com](https://console.anthropic.com)
   - **OpenRouter**: Get at [openrouter.ai/keys](https://openrouter.ai/keys)

2. **Choose Provider**:
   - Anthropic: Claude Sonnet 4, Haiku 4, Haiku 3.5
   - OpenRouter: 100+ models including GPT-4o, Gemini, Llama, etc.

3. **Upload PDF & Generate**:
   - Upload a lesson PDF
   - Select subject, difficulty, question type
   - Click "Generate Exam"
   - Answer questions and check score

## Technical Details

- **Single HTML file** - No build process needed
- **Client-side only** - Your API key never leaves your device
- **PDF.js** - For client-side PDF text extraction
- **Service Worker** - For offline support and caching
- **LocalStorage** - For persistent data storage

## Files

- `index.html` - Main application
- `manifest.json` - PWA configuration
- `service-worker.js` - Offline support & caching
- `README.md` - This file

## Privacy & Security

- 🔒 Your API keys are stored locally (localStorage) - not sent to servers
- 📄 PDFs are processed in your browser - never uploaded
- 🌐 Only API calls to your chosen provider (Anthropic/OpenRouter)
- ✅ Works completely offline (with cached resources)

## Deployment Options

✅ **GitHub Pages** (Free, recommended)
- Settings → Pages → Deploy from branch: main

✅ **Netlify**
- Connect GitHub repo → auto-deploys

✅ **Vercel**
- Similar to Netlify, very fast

✅ **Any Static Host**
- Just upload the 3 files

## Browser Support

- ✅ Chrome/Chromium (all versions)
- ✅ Firefox (all versions)
- ✅ Safari (iOS 12+)
- ✅ Edge (all versions)

## License

MIT - Free to use and modify

## Support

For issues or questions, check the code comments or create an issue on GitHub.

---

**Made with ✨ by Claude**
