# 💸 TippyTip - Smart Tip Calculator

A production-ready tip calculator with AI bill scanning, currency conversion, and real-time data from multiple free APIs.

## ✨ Features

### 📸 AI Bill Scanning
- Camera capture or gallery upload
- Tesseract.js OCR extracts amounts automatically
- Detects subtotal, tax, and total
- Drag & drop support

### 💵 Tip Calculation
- Quick tip buttons (10-25%) + custom slider
- Service quality rating with suggested tips
- Round up/down to nearest dollar
- Split bill among up to 50 people

### 💱 Currency Converter
- 15+ currencies supported
- Real-time exchange rates
- Swap currencies instantly
- Popular rates dashboard

### 🌍 Location-Aware
- Auto-detects your country
- Sets appropriate currency & tip defaults
- Shows local tipping culture info
- Current weather display

### 📊 History & Insights
- Save all calculations
- Spending analytics
- QR code sharing
- Export & share options

---

## 🔌 Powered by Free APIs

| API | Purpose | Auth |
|-----|---------|------|
| [Tesseract.js](https://tesseract.projectnaptha.com/) | OCR/Receipt scanning | None |
| [ExchangeRate-API](https://www.exchangerate-api.com/) | Currency conversion | None |
| [IP-API](https://ipapi.co/) | Geolocation | None |
| [Open-Meteo](https://open-meteo.com/) | Weather data | None |
| [Quotable](https://quotable.io/) | Inspirational quotes | None |
| [QRServer](https://goqr.me/api/) | QR code generation | None |

---

## 🚀 Quick Start

```bash
# Just open in browser
open index.html

# Or serve locally
python -m http.server 8000
# Visit http://localhost:8000
```

---

## 📱 Install as App (PWA)

### iOS/Android
1. Open in browser
2. Tap Share → "Add to Home Screen"

### Desktop
1. Open in Chrome/Edge
2. Click install icon in address bar

---

## 🎨 App Tabs

| Tab | Features |
|-----|----------|
| 🧮 Calculator | Scan receipts, manual entry, tip selection, bill splitting, round options |
| 💱 Convert | Currency converter, live rates, weather, tipping culture, quotes |
| 📜 History | Saved calculations, spending insights, totals |
| ⚙️ Settings | Theme toggle, default tip %, app info |

---

## 🚀 Deploy to Vercel

### Option 1: Via Website (Easiest)
1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com) → "Add New Project"
3. Import your repository
4. Click "Deploy" - done!

### Option 2: Via CLI
```bash
npm i -g vercel
vercel
vercel --prod
```

### Auto-Deploy
Every push to GitHub triggers automatic deployment.

---

## 📁 File Structure

```
tip-calculator/
├── index.html          # Main app
├── manifest.json       # PWA manifest
├── service-worker.js   # Offline support
├── vercel.json         # Vercel config
├── icons/              # App icons
└── images/             # Graphics
```

---

## 🔒 Privacy

- No account required
- All data stored locally in browser
- No tracking or analytics
- Works offline
- No personal data collected

---

## 📊 Technical Details

- **Size**: < 1 MB
- **Dependencies**: Zero (vanilla JS)
- **Browser Support**: All modern browsers
- **Mobile**: iOS & Android
- **Offline**: Fully functional via Service Worker

---

## 📄 License

MIT - Free to use and modify.

---

**Built with vanilla HTML/CSS/JS + Free Public APIs** 💸
