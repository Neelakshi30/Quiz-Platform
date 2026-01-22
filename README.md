# 🎯 Console Quiz Application in C (KBC Style)

A feature-rich console based quiz game written in C for Windows.  
The program loads questions from a file, allows users to navigate between them, answer or modify responses, and calculates the final score with prize money. It also includes a colorful UI and an animated LED-style **WELCOME** banner.

---

## 🚀 Features

- 📂 Loads questions from external file (`ques.txt`)
- 🎨 Colored console interface (Windows API)
- ⏮ Previous / ⏭ Next question navigation
- ✏️ Answer & modify answers anytime
- 🔢 Jump directly to any question number
- 🧠 Stores user responses
- 🧮 Auto evaluation at submission
- 💰 Prize money calculation
- 📊 Result summary (Correct / Wrong / Total Prize)
- 🔴 LED style animated scrolling **WELCOME** board
- 🧹 Input validation & safe memory handling

---

## 🛠 Technologies Used

- Language: **C**
- Compiler: GCC / MSVC (Windows)
- Libraries:
  - `stdio.h`
  - `stdlib.h`
  - `string.h`
  - `windows.h`
  - `conio.h`
  - `ctype.h`
 This program is **Windows-only** because it uses `windows.h` and `conio.h`.
## 📁 File Structure

