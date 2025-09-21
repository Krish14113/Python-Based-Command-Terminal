# Python Based Command Terminal

## Overview
The **Python Based Command Terminal** is a fully client-side, browser-based terminal that simulates a Linux-like environment.  
It features a **sandboxed virtual filesystem** stored entirely in your browser's `localStorage`, meaning your real computer files are never touched.  
This makes it a perfectly safe environment for **learning and experimenting** with shell commands.

The standout feature is its **AI integration with OpenRouter**.  
If you type a command that the virtual terminal doesn't recognize, it treats your input as a natural language prompt and asks an AI to generate the correct command for you, which is then executed automatically.

---

## ✨ Features
- **Sandboxed Filesystem**  
  Create, modify, and delete files and directories in a safe, virtual environment that persists between sessions.

- **Standard Unix Commands**  
  Emulates common commands like `ls`, `cd`, `mkdir`, `cat`, `rm`, `mv`, and a simulated `ps`.

- **AI Command Generation**  
  Seamlessly converts natural language prompts (e.g.,  
  _"create a new directory called 'my_project'"_) into executable shell commands.

- **Downloadable Python Tool**  
  Includes a button to download a related Python pseudo compiler for offline use.

---

## 🚀 Getting Started
This is a **single-page web application**.  
No installation is required.

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, or Edge).
3. You will be greeted by the **virtual terminal interface**.

---

## 🔑 API Key Setup (Required for AI Features)
To enable the natural language-to-command feature, you must provide your own **OpenRouter API key**.

1. **Get a Key**  
   Go to [OpenRouter.ai](https://openrouter.ai), sign up for a free account, and navigate to the **Keys** section in your account settings to create a new API key.

2. **Enter the Key**  
   Copy your new API key.  
   In the AI Virtual Terminal, paste this key into the **“OpenRouter API Key”** input box located in the top controls bar.

3. **Save the Key**  
   Click the **Save Key** button.  
   Your key will be securely saved in your browser’s local storage.  
   It is only used to communicate with the OpenRouter API and will be remembered automatically for future sessions.

---

## 🖥️ How to Use
- **Standard Commands**  
  Type `help` to see a list of all available built-in commands.  
  Use the terminal as you would a normal Linux shell.  

  Examples:
  ```bash
  mkdir test_folder
  cd test_folder
  ls
