# 🌸 Daily Target Planner

Welcome to Daily Target Planner — a simple app to help you set daily goals and jot down your reflections easily.  

---

## How It Works

- Run the Python script `problem1.py` (or the executable if you have it).  
- When you run it the **first time**, it **automatically adds itself to your Windows Startup folder** by creating a small batch file there.  
- This means the app will open **automatically every time you start your PC** — no extra setup needed!  
- You can then enter your daily goals and notes and save them.  

---

## How to Use

1. **Run `problem1.py`** by double-clicking it (or run `problem1.exe` if you have the executable).  
2. On the first run, the app will set itself to open at startup automatically.  
3. Write your goals and reflections for the day.  
4. Click **Save Today’s Plan** to save your entry as a text file.  
5. To view previous days’ plans, select a date from the dropdown and click **Show Entry**.

---

## Where Your Data is Saved

All your daily plans are saved as text files inside the `DailyTargets` folder created in the same directory as the script.  

---

## Requirements

- Python 3.x installed on your PC (if running `.py` file).  
- Tkinter library (comes bundled with Python by default).  
- Or just use the `.exe` built with PyInstaller for no-install hassle.

---

## Optional: Build Your Own Executable

To build your own `.exe` file from the Python script, use:

```bash
pyinstaller --onefile --windowed problem1.py
