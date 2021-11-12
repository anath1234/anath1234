import pyautogui as pg
Import time
time.sleep(10)
txt=open('animals.txt', 'r')
 a="saben is a"
 for i in txt:
    pg.write(a+' '+i)
    pg.press('Enter')
