# Voice-Command-Shopping-Assistant# 
🛒 VoiceShop – AI-powered Shopping List  

VoiceShop is a smart shopping list app that lets you **add, remove, and manage items with your voice**.  
Powered by the **Web Speech API** for voice recognition and **Gemini AI** for intelligent item parsing, the app makes shopping effortless and interactive.  

---

## 🚀 Features  

- 🎙️ **Voice Control** – Add or remove items hands-free.  
- 🧠 **AI Parsing** – Detects item name, quantity, and category automatically.  
- ✅ **Smart List Management** – Check off items as you shop or remove them instantly.  
- 💡 **AI Suggestions** – Recommends related or seasonal items you may need.  
- 📱 **Responsive UI** – Clean design with Tailwind CSS and animations.  
- 🔒 **Local Storage** – Saves your last shopping list securely in the browser.  

---

## 🛠️ Tech Stack  

- **Frontend:** HTML, CSS (Tailwind), JavaScript  
- **AI:** Gemini API  
- **Voice Recognition:** Web Speech API  
- **Storage:** LocalStorage  

---

## 📖 How It Works  

1. Speak a command like:  
   - `"Add 3 apples to the list"`  
   - `"Remove 1 packet of sugar"`  
   - `"Clear the list"`  

2. Your voice is converted to text using **Web Speech API**.  
3. The text is sent to **Gemini AI**, which extracts:  
   - Item name  
   - Quantity  
   - Category (e.g., Produce, Dairy, Pantry)  
4. Items are displayed in the shopping list UI.  
5. You can check off completed items or delete them with one click.  

---

## 📦 Installation & Setup  

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/voiceshop.git
   cd voiceshop
