# 🚀 Multi URL Opener & Link Extractor - Chrome Extension

A lightweight and powerful Chrome extension to help you open multiple URLs at once and extract links from selected paragraphs effortlessly.

---

## ✨ Features

- **Open Multiple URLs**  
  Paste a list of URLs and open them all in new tabs with a single click.

- **Extract Links from Selected Text**  
  Select any paragraph or block of text on a webpage, extract all the links inside it, and save them for later.

---

## 📂 Project Structure

```
├── manifest.json
├── popup.html
├── popup.css
├── popup.js
├── content.js
├── background.js
└── icons/
    └── icon.png
```

| File           | Purpose |
|----------------|---------|
| `manifest.json` | Chrome extension settings |
| `popup.html`   | Extension popup UI |
| `popup.css`    | Popup styling |
| `popup.js`     | Handle opening URLs |
| `content.js`   | Extract links from selected text |
| `background.js`| Manage context menus and background logic |
| `icons/`       | Extension icon assets |

---

## 🚀 How to Install (for Development)

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/multi-url-opener.git
   ```
2. Open **Chrome** and go to:  
   `chrome://extensions/`

3. Enable **Developer Mode** (top right).

4. Click **Load unpacked** and select the project folder.

5. The extension will now appear in your browser toolbar!

---

## 🛠 How to Use

### Open Multiple URLs
- Click on the extension icon.
- Paste multiple URLs separated by a newline.
- Click **"Open URLs"** to open all links in new tabs.

### Extract Links from Selected Text
- Select any paragraph or block of text on a webpage.
- Right-click and choose **"Extract Links"** from the context menu.
- The extracted links are saved and can be viewed/opened from the popup.

---

## 📄 Permissions

This extension uses the following Chrome permissions:

- `tabs` – To open multiple tabs.
- `storage` – To save extracted links.
- `contextMenus` – To create a right-click option for extracting links.
- `activeTab` – To access the currently active tab.

---

## 📢 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to [open an issue](https://github.com/your-username/multi-url-opener/issues) or submit a pull request.

---

Would you also like a shorter **"Minimal README"** version if you want something lighter? 🚀  
Or should I also help you write a `LICENSE` file if you don't have one yet?