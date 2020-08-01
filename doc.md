
## exe文件添加图标

>pyinstaller -F -w -i G:\projects\proj2_raspberryPi\tasks\task8_youget\icon.ico  main.py

## GUI左上角图标



## 任务栏图标
import ctypes    
ctypes.windll.shell32.SetCurrentProcessExplicitAppUserModelID("myappid")  

