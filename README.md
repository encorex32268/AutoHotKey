# AutoHotKey
AutoHotKey Practice


#執行程式
```
run "path"
```
```
執行skype ex:run "C:\Program Files (x86)\Microsoft\Skype for Desktop\Skype.exe"
```

#短暫等待
```
Sleep ms
```
```
休息1秒 ex:Sleep 1000
```
#輸入,鍵盤
```
Send ___
```
```
按下enter ex:Send {enter}
```
```
傳送ctrl+space ex:Send ^{space}
```
```
複製貼上 ex:Send ^c ex:Send ^v
```
```
傳送文字 ex:Send 文字
```
```
大量文字,使用剪貼簿
ex:clipboard :="文字"
clipwait 1
Send ^v 
```
