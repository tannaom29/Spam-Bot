Following Code Works On Any TextEditor, all you need to do is:
1. Install Python On Your Device
2. Run the following code in terminal: "pip install pyautogui"

**Make sure that you are connected through whatsapp web in order to make this code work.

Inside the Editor create a file with .py as extension:
#
#
# Start of Code

import pyautogui
import webbrowser as wb
import time

wb.get('C:/Program Files (x86)/Google/Chrome/Application/chrome.exe %s').open("web.whatsapp.com")
time.sleep(30)

for i in range(100):
    pyautogui.press("a")            #**write one character at a time**
    pyautogui.press("u")
    pyautogui.press("r")
    pyautogui.press("space")
    pyautogui.press("k")
    pyautogui.press("y")
    pyautogui.press("a")
    pyautogui.press("space")
    pyautogui.press("h")
    pyautogui.press("a")
    pyautogui.press("a")
    pyautogui.press("l")
    pyautogui.press("space")
    pyautogui.press("c")
    pyautogui.press("h")
    pyautogui.press("a")
    pyautogui.press("a")
    pyautogui.press("l")
    pyautogui.press("space")
    pyautogui.press("?")

    pyautogui.press("enter")
 
 # End of Code
 #
 #
