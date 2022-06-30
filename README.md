import time;#--讓瀏覽器於randon time後開啟新的youtube頁面
import webbrowser;#--開啟youtube頁面用
import os;#於特定條件達成後（此處為開啟10個youtube頁面）後，關閉瀏覽器，避免電腦負擔太大
from random import randrange; #--用來設置youtube開啟之random時間

url="https://www.youtube.com/watch?v=UQ1P33qc5tg" #--可將url中的網址替換成任意合法頁面

for e in range(1000):
     # TODO: write code...
     for i in range(10):
         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1


         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(randrange(15))
         i=i+1

         webbrowser.open(url)
         time.sleep(120)
         i=i+1
         
        
         os.system("taskkill /im chrome.exe /f") #--windows用來殺掉chrome之指令
         print("for windows to kill chrome")
         os.system("killall -9 'Google Chrome'")#--mac用來殺掉chrome之指令
         print("for mac to kill chrome")
         e=e+1




         
