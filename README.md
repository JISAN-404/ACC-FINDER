# ACC-FINDER 🔍

ACC-FINDER is a Facebook account checking tool that identifies **Valid**, **Invalid** Facebook accounts efficiently.

The tool automatically saves all available accounts into a separate text file for later use.

---

## 🚀 Features

- ✅ Detects **Valid Facebook accounts**
- ❌ Detects **Invalid Facebook accounts**
- 📂 Finds **Available Facebook accounts**
- 📝 Automatically saves available accounts
- ⚡ Adjustable speed using threads

---

## 📁 Output File

- **AVAILABLE-FB.txt**
  - Contains only available Facebook accounts
  - Saved location:
`/sdcard/AVAILABLE-FB.txt`

---

## ⚙️ How It Works

1. Run the tool  
2. Enter the **file path** of your input `.txt` file  
   - The file must contain **numbers or usernames**
3. Enter the **speed / thread count**
   - Recommended: `10–120`
   - Higher threads can be used if desired
4. The tool checks each account and categorizes them:
   - Valid
   - Invalid
5. Available accounts are saved automatically

---

## 🛠 Installation & Run

Copy and paste the following commands:

```bash
cd $HOME
rm -rf ACC-FINDER
git clone https://github.com/JISAN-404/ACC-FINDER
cd ACC-FINDER
chmod +x find
./find
```
---

## 📌 Requirements

- Android device (Termux recommended)
- Internet connection
- Basic terminal knowledge
---

## ⚠️ Disclaimer

This tool is made for **educational purposes only**.  
The author is **not responsible** for any illegal or unethical use.  
Use it at your own risk.

---

## 👤 Author

**JISAN-404** 
---

⭐ If you like this project, don’t forget to give it a **star**!
