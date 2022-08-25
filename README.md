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


# commit 訊息的一些想法
可以使用Angular Js開發團隊的寫法

commit的標題分為以下九種

![image](https://user-images.githubusercontent.com/98711945/186552532-f7719c64-a48b-4923-bd91-3b3329166f50.png)
![image](https://user-images.githubusercontent.com/98711945/186552555-def00769-c119-4de9-9c38-2bab0de7c0bf.png)

![image](https://user-images.githubusercontent.com/98711945/186552672-75d56a92-9de8-426c-af23-bf7a5384d33c.png)


格式

fix(core): only set input on specific instance in ComponenRef 

just something something


![image](https://user-images.githubusercontent.com/98711945/186553192-b414b621-53e4-46a7-8f09-5fe47ec92b06.png)

fix是標題，標題後可以接這次修改影響的範圍，也可以不寫，後面接上一個短的描述，描述這次的commit做了什麼事情
