https://github.com/ct-code/sea/releases/download/v4.0.0/CodeTantra.SEA-arm64-4.0.0.dmg

```
import pyperclip 
import pyautogui
import time

def process_clipboard():
    clipboard_content = pyperclip.paste()
    print("Clipboard Content:", repr(clipboard_content))
    lines = clipboard_content.split("\n")
    print("Lines:", lines)
    for line in lines:
        line = line.strip()  # Remove leading and trailing whitespace, including tabs
        if line:  # Check if line is not empty after stripping
            pyautogui.write(line, interval=0.00001) 
            pyautogui.press("enter")
            time.sleep(0.00000001)

time.sleep(4)
process_clipboard()
```

https://drive.google.com/file/d/1NW5zu7Eq5ncAIENNXzDzD2vhiPaEelaT/view?usp=sharing


https://drive.google.com/file/d/1nJ8n2fHULg9iOkwKzNCahxprjE8cGgHU/view?usp=drive_link


https://drive.google.com/drive/folders/1_NIl31uIPjENdi8lAo8upXtyKgPrSVHr?usp=sharing
