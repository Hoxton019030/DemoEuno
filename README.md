# DemoEuno

# 分支名稱- GitFlow
+ main
+ release
+ develop
+ feature
+ hoxfix

建議可以將feature跟hoxfix的分支名稱這樣命名

> feature/subscription

> feature/mysqlmoduel

> hoxfix/Sqlsyntax


> git branch feature/subscription

> git branch feature/mysqlmoduel

這樣子在一些GUI裡面會自動幫我們排成一個階層狀的結構，方便查找

![image](https://user-images.githubusercontent.com/98711945/186551992-e9a27eba-4eba-4b31-be18-faf18b46ddad.png)

在bash裡面也可以用tab+tab的方式呈現出目前feature分支有什麼

![image](https://user-images.githubusercontent.com/98711945/186554915-e8f08f31-839d-4069-9f79-98e07dc3c88d.png)



# commit 訊息的一些想法
可以使用Angular Js開發團隊的寫法
https://github.com/angular/angular
![image](https://user-images.githubusercontent.com/98711945/186552672-75d56a92-9de8-426c-af23-bf7a5384d33c.png)

commit的標題分為以下九種

![image](https://user-images.githubusercontent.com/98711945/186552532-f7719c64-a48b-4923-bd91-3b3329166f50.png)
![image](https://user-images.githubusercontent.com/98711945/186552555-def00769-c119-4de9-9c38-2bab0de7c0bf.png)




格式

fix(core): only set input on specific instance in ComponenRef 

just something something


![image](https://user-images.githubusercontent.com/98711945/186553192-b414b621-53e4-46a7-8f09-5fe47ec92b06.png)

fix是標題，標題後可以接這次修改影響的範圍，也可以不寫，後面接上一個短的描述，描述這次的commit做了什麼事情，上述這些自數以72個字為限，因為超過就會跳到下一行了，可以在SourceTree裡打開這些設置

![image](https://user-images.githubusercontent.com/98711945/186553627-bd97ba78-b476-4d9b-98cd-2031a792407d.png)

會自動提醒是否超過

![image](https://user-images.githubusercontent.com/98711945/186553765-aa6f80aa-94e5-4342-a340-9ae706134ff3.png)


打完之後可以選擇性要不要繼續描述這次Commit更詳細的行為，比如說刪除了那些code，增加了那些功能這樣子

![image](https://user-images.githubusercontent.com/98711945/186553925-de763977-7e1f-41d4-b8c0-cfad875b8952.png)
![image](https://user-images.githubusercontent.com/98711945/186553965-d88c8ad6-ff50-4811-8f78-56562188dd6f.png)




