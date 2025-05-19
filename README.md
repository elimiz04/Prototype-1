Sure! Here's a **step-by-step guide** you can include in your `README.md` or share with another user so they can easily run and experience your **Speech Highlight** project on their own machine.

---

# 🛠️ Step-by-Step: How to Run the Speech Highlight Project

Follow these instructions to view and interact with the project locally using **Visual Studio Code** and **Google Chrome**.

---

## ✅ Requirements

Before you begin, make sure you have the following installed:

1. **[Visual Studio Code](https://code.visualstudio.com/)**
2. **[Google Chrome](https://www.google.com/chrome/)**
3. **Debugger for Chrome Extension** in VS Code:

   * In VS Code, go to the **Extensions** tab (or press `Ctrl+Shift+X`)
   * Search for **"Debugger for Chrome"**
   * Click **Install**

---

## 📁 1. Open the Project in VS Code

* Download or clone the project files.
* Open the folder in **Visual Studio Code**.

---

## ⚙️ 2. Set Up the Launch Configuration

1. Inside VS Code, open the `.vscode` folder (create it if it doesn't exist).
2. Inside `.vscode`, create a file called `launch.json`.
3. Paste the following configuration into `launch.json`:

```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "chrome",
      "request": "launch",
      "name": "Open Epilogue fast speed.html",
      "file": "c:\\Users\\YOUR_USERNAME\\PATH\\TO\\Epilogue fast speed.html"
    }
  ]
}
```

> 🔁 **Replace** the file path (`c:\\Users\\YOUR_USERNAME\\...`) with the **actual path** to your `Epilogue fast speed.html` file on your system.

---

## 🚀 3. Launch the Project

1. In VS Code, go to the **Run and Debug** tab (left toolbar, or press `Ctrl+Shift+D`).
2. From the dropdown at the top, choose:
   **"Open Epilogue fast speed.html"**
3. Click the **green play button** ▶️ or press `F5`.

Chrome will open the HTML file in a new browser tab.

---

## 🗣️ 4. Use the Speech Highlight

* Click the **"▶️ Start Audio"** button.
* Listen to the audio narration.
* Watch the **highlighting** sync word-by-word with the speech.

---

## 🔄 5. Restart or Stop

If you want to **replay the narration**:

* Refresh the browser tab.
* Click the **Start Audio** button again.

To stop the speech mid-way:

* Close the tab or hit **Stop Debugging** in VS Code.

---

## 📝 Notes

* For the best experience, use **Google Chrome**.
* Speech highlighting relies on the **Web Speech API** – some browsers may not support all features (like `onboundary` events).
* You can adjust the pitch, rate, or text directly in the HTML file.
