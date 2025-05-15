# 📦 ExtRm0ver - Managed Chromebook Extension Disabler  
## **Patched on v131**  

> 🛑 **Important:** Rollback is currently possible, obviously if you wanted to do that instead you would'nt be here.

> ⚠️ **Note:** This method is currently patched as of version 131. This README is for archival or educational purposes only.

> ⚠️ **Note:** Our webhook is currently experiencing issues and is not currently functioning as intended. This will sometimes cause the exploit to not function correctly.
---

## 🚫 What Is ExtRm0ver?

**ExtRm0ver** is a simple tool designed to **temporarily disable school-managed Chrome extensions** on Chromebooks — specifically those used to monitor or restrict student activity.

It can disable extensions such as:
- GoGuardian
- Hapara
- Securly
- SEDUCA
- iBoss  
...and more.

> ⚠️ This only works until the device is restarted. Extensions will automatically re-enable after reboot.

---

## 🧰 Prerequisites

- A **Chromebook**
- Access to **Chrome DevTools**
  - **Not** Developer Mode — just DevTools (`Ctrl+Shift+I` or via URL)
> 🛑 **Important:** `Ctrl+Shift+I` may not work for some devices with different management levels.
---

## 🚀 How to Use

### 📍 Step 1: Open DevTools
Paste the following link into your address bar and press Enter:
`devtools://devtools/bundled/devtools_app.html`
> 🛑 **Important:** You *must* open this link first, or the rest of the process won’t work.

---

### 📍 Step 2: Connect to Remote DevTools Session

In a **new tab**, paste and open this link:
`devtools://devtools/bundled/devtools_app.html?experiments=true&wss=rig.ccsd.store`

You should see a page like this:

![Remote DevTools Example](https://github.com/user-attachments/assets/cfe3c7c3-b39f-4d8d-8b88-43955db42a67)

---

### 📍 Step 3: Access the Extensions Panel

1. Click the **Network** tab at the top.
2. On the left side, double-click the **grey box** surrounding the white square.
  
> You may have to hover your mouse over the square to see the box.

![Network View](https://github.com/user-attachments/assets/4e40c0e6-5a24-4c6e-a3bc-61ce85dc0062)

---

### 📍 Step 4: Manage Extensions

You should now see a screen like this:

![Extensions Panel](https://github.com/user-attachments/assets/5b6cb0a6-1cba-4478-b2ad-d7de7b8881cd)

- Click **“GForms Locked Mode (on all enrolled CBs)”**
- You'll now be able to toggle any installed extension.

---

## ♻️ Persistence (After Restart)

When your Chromebook restarts, extensions will re-enable.

To quickly repeat the process:

1. Bookmark both URLs used above:
   - Name them `1` and `2` in order.
   - Use them after reboot to get back to Step 3.

   ![Bookmark Example](https://github.com/user-attachments/assets/a76f047a-0681-4550-a030-2be3541d9e63)

2. (Optional) Bookmark the Chrome Management Extensions page and name it `Extension Disabler`.

---

## ⚠️ Disclaimer

> This tool is provided **for educational and research purposes only**.  
> - You **assume full responsibility** for using this.  
> - The author is **not liable** for any disciplinary actions, data loss, or damages caused by misuse.  
> - **Use at your own risk.**
