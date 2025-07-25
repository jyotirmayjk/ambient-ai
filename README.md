# OpenAI Query Extension

A Chrome extension that integrates OpenAI's GPT-3.5-turbo API into your browsing experience. Query AI about any selected text or images on web pages.

## 🌟 Features

- **Text & Image Queries**: Right-click on selected text or images to ask AI questions
- **Popup Interface**: Quick access through extension popup for general queries
- **Secure API Key Storage**: Keys stored securely in Chrome's sync storage
- **Real-time Responses**: Modern dialog boxes appear directly on web pages

## 🚀 Installation

### Prerequisites
- Google Chrome browser
- OpenAI API key ([Get one here](https://platform.openai.com/))

### Steps
1. Clone this repository
2. Open Chrome → `chrome://extensions/` → Enable "Developer mode"
3. Click "Load unpacked" → Select the extension folder
4. Click extension icon → Enter your OpenAI API key → Save

## 📖 Usage

### Method 1: Popup Interface
1. Click extension icon in toolbar
2. Enter query → Click "Submit Query" or press Enter

### Method 2: Context Menu (Recommended)
1. **Text**: Select text → Right-click → "Ask about selected text"
2. **Images**: Right-click image → "Ask about this image"
3. Enter question → Click "Ask AI"

### Keyboard Shortcuts
- **Enter**: Submit query
- **Escape**: Close dialog

## 🔧 Technical Details

- **Manifest V3**: Latest Chrome extension standard
- **Model**: GPT-3.5-turbo with 0.7 temperature
- **Security**: API keys stored locally, no data collection
- **Permissions**: storage, contextMenus, activeTab, scripting

## 📁 Files

```
├── manifest.json    # Extension config
├── popup.html/js    # Popup interface
├── content.js       # Web page integration
├── background.js    # Background service
└── styles.css       # Styling
```

## 🐛 Troubleshooting

**"API key not found"** → Save your API key in the popup  
**"Content script not ready"** → Refresh the page  
**"API request failed"** → Check API key and internet connection

## ⚠️ Disclaimer

Requires OpenAI API key and will incur costs based on usage. Review OpenAI's pricing before use.

---

**Happy AI-powered browsing! 🚀**
