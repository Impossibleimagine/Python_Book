# Python_Book
from 0 to 0.1 Python learning
# Python

## Get Start!(install)
How to start?
要怎麼開始寫python
首先你要先安裝python到你的電腦
step1
到[python官網](https://www.python.org/)<--小力點我
![](https://i.imgur.com/DATvkRE.png)

step2
找一下Download(下載)這個關鍵字在哪
![](https://i.imgur.com/IsBD80H.png)

step3
會看到上面寫Download for Windows，如果你是Windows系統的人圖一那個圈起來的地方給他點下去
使用Mac電腦(蘋果)的人點圖二綠色圈起來那邊，然後點圖三圈起來那邊(其實在Python Releases for macOS裡面的選項都能點，這邊代表的是python各種版本的載點)
![](https://i.imgur.com/dm0euY2.png)圖一🔼

![](https://i.imgur.com/3C1g8SM.png)圖二🔼

![](https://i.imgur.com/2mPYIm9.png)圖三🔼
如果你不會按按鈕，這邊提供任意門
[Windows用戶](https://www.python.org/downloads/windows/)
[MacOS用戶](https://www.python.org/downloads/macos/)


step4
正常來說會開始下載一個檔案
![](https://i.imgur.com/rjylMa7.png)

step5
下載完打開後就一直按下一步就安裝完成了!!!

step6(這邊我使用的編輯器是Visual Stdio Code)
一樣先到[官網](https://code.visualstudio.com/)<--小力點我
![](https://i.imgur.com/YXhRBMF.png)

step7
如果你是Windows系統的就點那個藍藍的地方(中間的不是上面的)
如果你是MacOS系統的就點旁邊的勾勾(?，然後選stable那個藍勾勾
![](https://i.imgur.com/Yg3wzZ6.png)Windows看上面
################挖系分隔線################
![](https://i.imgur.com/6toerOn.png)
![](https://i.imgur.com/tbJ3Z37.png)Mac看上面

step8
點完就開始下載，然後一樣一直按下一步就完工了!!!

如果說你出了一堆問題，那就~~別寫了~~
可以利用線上的環境去執行程式，但是線上的環境只能讓你看到執行完的狀況，存檔的部分可能要另外想辦法，盡量不要用線上的環境拉，除非你很急著要寫python或是測試一些小東西，否則建議安裝好在電腦上。
[線上環境](https://www.programiz.com/python-programming/online-compiler/)

## Get Start!(Usage)
載好VScode和Python後就可以開始寫囉!
先打開VScode
![](https://i.imgur.com/cQjJf5x.png)
先忽略右下角，那邊在更新套件，畫面應該如圖片那樣。
接下來點左邊那排東東最上面那個檔案總管
![](https://i.imgur.com/BTkDZGI.png)
你可以按開啟資料夾選擇你要放python程式碼的地方(資料夾)
Ps.可以先在桌面空白處按右鍵新增資料夾，然後選擇那個資料夾
選擇完後畫面應該是這樣(我的資料夾名叫Python)
![](https://i.imgur.com/squw1IJ.png)

![](https://i.imgur.com/91NPdFi.png)
第一個是新增檔案，點了之後會叫你輸入檔案名稱，名稱後面加上.py他就會自動判斷成python檔案囉(左邊圖案變成蛇蛇)
EX.
![](https://i.imgur.com/ILCUbba.png)
按Enter就成功建立檔案囉(haha.py)我也不知道為什麼會有超連結==
可以到你放python程式碼，也就是一開始選的那個資料夾裡面看，會出現你剛剛新增的檔案。
就可以開始寫python程式囉，記得寫完要按ctrl+s這樣才會存檔喔
寫完後去左邊那排東東點方塊那個**搜尋run code**安裝第一個
這邊我已經安裝好了，你們的畫面應該是出現一個install的藍色按鈕，按下去安裝
![](https://i.imgur.com/4F0GKBf.png)

載好後把那個安裝的分頁先關掉，回到剛剛寫code的地方
![](https://i.imgur.com/bcpeI6Z.png)
按右上角那個三角形，選"在終端機中執行Python檔案"
下面出現的視窗就是你程式執行的結果了

完結灑花(333

這邊也順便介紹一下使用線上環境的方法:
![](https://i.imgur.com/wG75Byc.png)
點開網址後應該是出現這個畫面(廣告是什麼我就不知道了(X )
左半部是你寫程式的部分，寫完後你按Run就會執行，並且顯示在右邊，右邊可以進行輸入互動等等...
阿然後我的畫面是黑的是因為我調成深色模式
![](https://i.imgur.com/O8KSbw9.png)
另外
左邊那排可以選擇其他語言，從上到下是Python/C/C++/Java
![](https://i.imgur.com/LFgLDUC.png)


## 資料型態
電腦存著很多資料，當然需要一個分類方式，這就是為什麼有這些資料型態
### 整數(int)
整數
Ex:
:::info
123
321
456
:::

### 浮點數(float)
有小數點的數字
Ex:
:::info
1.2
2.3
3.333
:::

### 字串(string)
文字，注意數字也可以是字串型態!!!
只要被放在兩個"裡面，電腦就會認定裡面的資料是字串，運算方式也會不一樣，下面細說。
Ex:
:::info
"Hello World!"
"Hello"
"world!"
"中文"
"123"
:::
### 布林值(bool)
這個型態只有兩種可能的值，就是對和錯(真和假)，用來存放邏輯結果的一種型態，例如我要存放3>7的結果，我就會用bool來存，可想而知3>7這個敘述是錯誤的
Ex:
:::info
True
False
:::
### 有順序，可變動的列表(List)
Ex:
:::info
[123,234,1,2,3]
["helo","world","ahoy!"]
:::

### 有順序，不可變動的列表(Tuple)
Ex:
:::info
(123,234,1,2,3)
("hello","world!","wryyyy")
:::

### 集合->無順序(set)
Ex:
:::info
{123,234,1,2,3}
{"hello","world!","A"}
:::

### 字典(類似C++的STL map) (Dictionary)
Ex:
:::info
{"apple":"蘋果","mywife":"雷姆"}
:::
## 基本輸入輸出(input(),print)
### 輸出(print)
python輸出語法為print(變數或是值)
例如我能:
```python=
a = 123
print(a)
print(123)
print("sssss")
```
輸出就是顯示在你的結果畫面上。
### 輸入(input())
基本的python輸入方法
python是用input()這個函式去做輸入的操作
input()函式小括號裡面可以放，也可以不放參數，裡面的參數是用來提示使用者輸入的，例如我寫input("請輸入姓名")，程式執行後的結果會先跳出請輸入姓名，這邊對你的輸入並不會造成任何影響，只是單純提示你這格要輸入什麼，為什麼需要使用者輸入?
程式語言就是人類跟電腦溝通的語言，你當然需要跟電腦說話，而不是只看電腦自己執行輸出而已。
這邊特別注意一點!!!
**input()函式預設輸入資料的型態是字串**
以下舉一個例子:
```python=
num = input("請輸入數字")
print(num/2)
#output:
#error
```
會發現發生錯誤了，因為你把輸入的值存到num這個變數，num這時候的型態是字串，即便你輸入數字，程式執行到第二行的時候會印出你輸入數字除以二，看似正常但你有沒有發現字串string和整數int是不能做運算的，因此跳出錯誤。
要修正這個問題很簡單，就是在輸入後把輸入值轉成整數。
看code
```python=
num = input("請輸入數字")
num = int(num)
print(num/2)
#input:
#4
#output:
#2

```
還是很難理解的人可以去下面的醬汁看詳細介紹。
[醬汁source](https://ithelp.ithome.com.tw/articles/10212286)

## 運算子

### 數字

"+"  加
"-"  減
"\*" 乘
"/"  除
"//" 整數除法
"\**" 做次方(n\**0.5就是對n開根號)
"%"  餘數

```python=
x = 3
x = x + 1
print(x) #這時候x的值是4，因為程式會先做右邊再把答案放到左邊的變數
#output:
#4
```

上面的 x = x + 1 可以縮寫成 x += 1

## 字串運算
### 拼接兩個字串用+
```python=
s = "Hello" + "World!"
print (s)
#output:
#Hello World!
```
也可以寫成這樣
```python=
s = "Hello" "World!"
print(s)
#output:
#Hello World!
```
### 跳脫字元\(印出")
```python=
s = "hell"o"
print(s)
#error
```
會發現這樣寫跳錯誤，原因就是電腦只讀到"hell"，這時候就要把l和o之間的那個"的效果去掉，只要在前面加上\就可以了(如下)
```python=
s = "hell\"o"
print(s)
#output:
#hell"o
```
### 換行符號\n(不想要所有文字都擠在一行) 
```python=
s = "hello\nWorld!"
print(s)
#output:
#Hello
#World!
```
或是這樣寫
```python=
s = """hello
World!"""
print(s)
#output:
#Hello
#World!
```
用三個引號就可以直接在裡面按Enter換行

### 乘法
```python=
s = "rero!"
ss = s * 3
print(ss)
#output:
#rero!rero!rero!
```

### 取得字串中某個字元(string[index]):
```python=
s = "nekopara"
#    01234567  對應的位置(index)，從0開始
print(s[2])
#output:
#k
```

### 取得字串中一段子字串(string[begin(include):end(not include)]):
```python=
s = "nekopara"
#    01234567  對應的位置(index)，從0開始
print(s[2:4])
#output:
#ko
```
**begin**不填就是從0開始到end
**end**不填就是begin到最後一個



## 有序列表的基本運算
### 取列表中的值
```python=
l = [12,23,34,56,78]
print(l[0])
#output:
#12
```
其實用法跟字串差不多
這邊特別提到刪除某段元素的方法
```python=
l = [12,23,34,56,78]
print(l)
l[1:3]=[]
print(l)
#output:
#[12, 23, 34, 56, 78]
#[12, 56, 78]
```
這邊刪除了index1到index3(不包含)，也就是23,34(index(1~2))這兩個元素，因此l這個list從[12, 23, 34, 56, 78]變成[12, 56, 78]

### 取得列表長度len(列表名稱)
```python=
l = [12,23,34,56,78]
lenth = len(l)
print(lenth)
#output:
#5
```

### 加法
```python=
l = [12,23,34,56,78]
print(l)
l = l+[33,44]
print(l)
#output:
#[12, 23, 34, 56, 78]
#[12, 23, 34, 56, 78, 33, 44]
```

### 乘法
```python=
l = [12,23,34,56,78]
print(l)
l = l*2
print(l)
#output:
#[12,23,34,56,78]
#[12,23,34,56,78,12,23,34,56,78]
```

### 修改某索引的元素值
有一個列表l = [12,23,34,56,78]
如果要直接修改第一項，也就是l[0]的話可以直接打l[0]=某數
要注意!!這樣寫會直接蓋掉原本l[0]的值
**只有List可以進行這個操作，Tuple這樣做會錯誤，因為Tuple不能變動**
```python=
l = [12,23,34,56,78]
print(l)
l[0] = 69
print(l)
#output:
#[12, 23, 34, 56, 78]
#[69, 23, 34, 56, 78]
```
可以看到l[0]的值被替換成69了，原本的12也不見了

### 多層列表
在列表裡面放列表，取值的話就用兩個[]，例子如下:
```python=
l = [[123,456,789],[234,567,890]]
print(l)
print(l[0])
print(l[0][2])
#output:
#[[123, 456, 789], [234, 567, 890]]
#[123, 456, 789]
#789
```
可以看到第二行輸出l這個列表裡面index[0](第一項)的列表[123, 456, 789]。
第三行則是輸出在第一項列表中的index[2](第三項)的元素值789。
倘若第一項列表中的第三項又是一個列表，想一想會輸出什麼?

這邊出個小題目
```python=
l = [[123,456,789],[234,567,890]]
l[0][0:2] = [5,5,5]
print(l[0])
#output:
#猜猜看是什麼?
```
:::spoiler 答案
[5,5,5,789]
:::


## 集合、字典的基本運算
### 判斷某資料是否在集合中(元素 in 集合)or(元素 not in 集合)
```python=
s1 = {6,3,4,2,9}
print(3 in s1)
print(87 in s1)
print(3 not in s1)
print(87 not in s1)
#output:
#True
#False
#False
#True
```
這邊有一個集合s1，我想知道3和87是否在集合中，所以我用in這個語法去檢查。
3是有的，所以會輸出True
87不在集合中，所以會輸出False
not in 就是檢查3和87是不是不在集合中
3是有在集合中的，所以"3不再集合中"這個敘述是錯誤的，因此輸出False
87確實不在集合中，因此輸出True

### 交集(集合1&集合2)
```python=
s1 = {6,3,4,2,9}
s2 = {2,3,4,6,1}
s3 = s1&s2
print(s3)
#output:
#{2, 3, 4, 6}
```
我想知道s1和s2的交集(兩個集合中有那些元素是重複的)，所以我用&這個語法去把他們交集的集合存在s3，很明顯的，s1和s2交集(重複的元素)有2,3,4,6這四個元素。

### 聯集(集合1|集合2)
```python=
s1 = {6,3,4,2,9}
s2 = {2,3,4,6,1}
s3 = s1|s2
print(s3)
#output:
#{1, 2, 3, 4, 6, 9}
```
聯集(兩個集合中所有元素，不會重複)，聯集要用|這個語法。

### 差集(集合1-集合2)
```python=
s1 = {6,3,4,2,9}
s2 = {2,3,4,6,1}
s3 = s1 - s2
print(s3)
#output:
#{9}
```
差集(從s1中刪去和s2重複的元素)，在這邊可以看到s1和s2重複的元素有2,3,4,6，因此s1和s2做差集的運算後會得到~~6~~,~~3~~,~~4~~,~~2~~,9，只剩下{9}，

### 反交集(集合1^集合2)
```python=
s1 = {6,3,4,2,9}
s2 = {2,3,4,6,1}
s3 = s1 ^ s2
print(s3)
#output:
#{1, 9}
```
反交集(兩個集合中不重複的元素)，s1和s2重複的元素有2,3,4,6，把兩個集合都扣掉這些元素剩下的就是反交集的集合元素了，s1扣完剩下{9}，s2扣完剩下{1}，最後s1^s2的結果就是{1,9}。

### 拆解字串成集合set()
```python=
s = set("apple")
print(s)
#output:
#{'l', 'e', 'p', 'a'}
```
這邊把apple拆成一個集合，集合的特性就是不會重複元素，所以最後輸出a,p,l,e，這邊的順序是隨機出現的，每次編譯都會有不同結果。

### 字典(key-value key值配對value)
字典型態的寫法:{"key1值" : "key1值對應到的值","key2值" : "key2值對應到的值",...}
對應到的值可能是字串、整數...等等，不一定只是數字。
```python=
d = {"ahoy!":"寶鐘瑪琳","peko!":"兔田配可拉","A":"噶嗚·古拉"}
print(d["A"])
#output:
#噶嗚·古拉
```
這邊我想印出字典d中key值為A對應到的值，可以看到輸出是噶嗚·古拉。

### 判斷字典中是否存在某key值(in / not in)
注意!!這邊只能判斷key值，無法判斷key對應到的值
```python=
d = {"ahoy!":"寶鐘瑪琳","peko!":"兔田配可拉","A":"噶嗚·古拉"}
print("peko!" in d)
print("Watame" in d)
print("寶鐘瑪琳" in d)
#output:
#True
#False
#False
```
這邊我在字典d中找是否有key值為peko!，答案是有的，因此輸出True
然後我找是否有Watame，答案是沒有，因此輸出False
最後我找是否有**key值**為寶鐘瑪琳，會發現雖然有對應到的值裡面有寶鐘瑪琳，但是key值中並沒有，因此輸出False
not in 就不多說了，上面有說明。

### 刪除字典中元素(del 字典名稱["key值"])
```python=
d = {"ahoy!":"寶鐘瑪琳","peko!":"兔田配可拉","A":"噶嗚·古拉"}
print(d)
del d["peko!"]
print(d)
#output:
#{'ahoy!': '寶鐘瑪琳', 'peko!': '兔田配可拉', 'A': '噶嗚·古拉'}
#{'ahoy!': '寶鐘瑪琳', 'A': '噶嗚·古拉'}
```
這邊我刪掉了"peko!"這個key值以及他對應到的值"兔田配可拉"。

### 字典生成式(字典名稱 = 變數 : 變數 for 變數 in 列表)
```python=
d = {i:i*i for i in [2,3,4]}
print(d)
#output:
#{2: 4, 3: 9, 4: 16}
```
這邊程式的邏輯很簡單，先看右半邊"for i in [2,3,4]"，就是說i要分別帶入2,3,4這三個數進去，進去哪裡呢?進去前面的i:i\*i，帶入後就能得到2:4,3:9,4:16，這樣一個字典就生成出來囉!

## 流程控制：if 判斷式(if ,elif , else)
### 基本語法、結構
```python=
if 條件1:
    執行敘述(條件1True時執行)
elif 條件2:
    執行敘述(條件2True時執行)
elif 條件3:
    執行敘述(條件3True時執行)
else:
    執行敘述(上面都條件都沒True時才會執行)
```
規則:
elif可以無限多個，也可以0個
else只能有1個或是0個
if可以獨立存在，elif和else必須對應到if，不能單獨存在
if、elif條件後面記得打":"，並且在下一行縮排(四個空白或是按一下Tab鍵)
else就是第一個if沒True(False)，接下來的elif也都沒True(False)的情況下才會去執行else，就是剩下的情況，你可以決定剩下的情況要執行什麼敘述，也可以什麼都不做(不加else)。
![](https://i.imgur.com/4Mx0WvU.png)


### if的各種可能一(if)
```python=
score = input()
score = int(score)
if score > 60:
    print("Pass!")
#input:
#61
#output:
#Pass!
```
這邊輸入了一個整數，並且存在score這個變數裡，使用者輸入61，第二行把輸入轉成整數，因為input預設輸入是字串(詳情看上面[#基本輸入](https://hackmd.io/WUL5MPOPR6KE1b4iw6hygQ?view#%E5%9F%BA%E6%9C%AC%E8%BC%B8%E5%85%A5input))，第三行在判斷score(使用者輸入)有沒有大於60，如果有就執行以下縮排程式碼
這邊我輸入了61，因為61>60這個敘述是對的(True)，所以程式會執行第四行，也就是印出"Pass!"這個字串。
```python=
score = input()
score = int(score)
if score > 60:
    print("Pass!")
#input:
#59
#output:
#
```
這次我輸入59，一樣存在score裡面，然後在第三行的時候因為59>60這個敘述是錯誤的(False)，因此程式不會執行第三行，也就是不印出"Pass!"，最後程式就結束了，什麼都沒印出來。
### if的各種可能二(if-elif)
```python=
score = input()
score = int(score)
if score > 60:
    print("Pass!")
elif score < 40:
    print("bad!")
#input:
#61
#output:
#Pass!
#input:
#39
#output:
#bad!
#input:
#50
#output:
#
```
這邊前四行都跟可能一一樣就不贅述了，後面多了elif就是說當你第一個條件沒達成(False)的時候，再去檢查elif的條件，如果有達成(True)就執行以下縮排程式碼，沒有的話(False)不執行
理解程式碼後再看我的輸入輸出。
我一開始輸入61，會先在第三行達成，就印出"Pass!"，這時候考考你，程式會執行到第五行elif的地方嗎?答案是不會，**因為elif只會在if沒達成時才會執行到**。
第二次，我輸入了39，39>60是False，所以就往下面的elif看，第四行會直接跳過，這時候39<40是True，所以執行以下縮排程式碼，也就是第六行，印出bad!
第三次，我輸入50，50>60是False，所以就往下面的elif看，第四行會直接跳過，50<40是False，第六行跳過，程式結束什麼都不印。
### if的各種可能三(if-elif-else)
```python=
score = input()
score = int(score)
if score > 60:
    print("Pass!")
elif score < 40:
    print("bad!")
else
    print("???")
#input:
#61
#output:
#Pass!
#input:
#39
#output:
#bad!
#input:
#50
#output:
#???
```
這邊前六行、前兩筆輸入都跟上面邏輯一樣，直到第七行出現else，else就是當以上的敘述都沒達成(False)時，執行以下縮排程式碼。
這邊第三筆輸入50剛好能讓上面if-elif都為False，這時候就會執行else以下縮排程式碼，也就是印出"???"。
這邊還有一點要補充，中間elif可以放無限個，有點像濾網一樣，一層一層過濾，最後沉到最下面的就是else的部分。
### if的各種可能四(if-else)
```python=
score = input()
score = int(score)
if score > 60:
    print("Pass!")
else
    print("???")
#input:
#61
#output:
#Pass!
#input:
#39
#output:
#???
#input:
#50
#output:
#???
```
這邊就如同我上述濾網的比喻一樣，中間沒有elif，當你輸入的數字不大於60，就會直接沉到最底，也就是else的部分，輸出"???"。
最後補充一點，學過其他語言的人可能會知道switch結構，在Python中是沒有switch-case這種結構的寫法，當然你要用奇葩的寫法寫出來也不是不可能實現。

## 函式
什麼是函式?
函式就像是一台機器，你放入一些東西--->得到新的東西
通常函式後面都有一個小括號()，裡面會放資料(參數)，至於放什麼資料、要放幾個就看這個函式的使用方法，也有可能不放任何東西。
舉例來說:max()函式是一個你放入兩個變數，就能幫你得出較大那個
```python=
a = 6
b = 9
max(a,b)
#output:
#
```
會發現為什麼都沒東西出現，原因就是你沒有把結果印出來，程式確實執行了max()函式，但是沒有print出來，很多人都會問說:我明明用這個函式了，怎麼都沒效果，那有可能你沒有把結果存在變數或是直接印出來。

修正一下
```python=
a = 6
b = 9
print(max(a,b))
#output:
#9
```
或是把它的結果存在變數(result)裡
```python=
a = 6
b = 9
result = max(a,b)
print(result)
#output:
#9
```

## 迴圈基礎 for、while
什麼是迴圈呢?
試想今天你要輸出一個字串Hello，你會怎麼寫
```python=
print("Hello")
#output:
#Hello
```
很簡單對吧!
這時候請你輸出10個Hello，怎麼寫?
```python=
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
#output:
#Hello
#Hello
#Hello
#Hello
#Hello
#Hello
#Hello
#Hello
#Hello
#Hello
```
是不是覺得複製貼上而已很簡單?
其實有更好的寫法，這時候就需要使用到迴圈了
### 基本語法、結構
#### while
```python=
while 條件(布林值):
    當條件為True時執行敘述
```
當程式執行到while時，會先檢查while後面的條件是否為True
是(True)的話-->執行敘述
否(False)的話-->跳過，就像if條件為False時不執行以下縮排程式碼
糖炒栗子
```python=
n = 1
while n<5:
    print(n)
    n = n+1
#output:
#1
#2
#3
#4
```
這邊程式碼就是設定n的初始值是1
當n<5這個敘述是True的時候(也就是n小於5的時候)，印出n，然後n加1
為什麼只到4而已?因為當n加到5的時候，n<5的敘述就不成立就不會印出n，迴圈就會跳到迴圈外。


while會一直執行到條件為否(False)為止，所以請注意不能一直讓條件為True，會進入無限迴圈，你的程式就會永遠停不下來。
```python=
n = 1
while n<5:
    print(n)
#output:
#1
#1
#1
#1
.
.
.
.
.
.
```
當你少加了n=n+1會發生什麼事?
你的while會一直觸發導致程式陷入無限迴圈，所以在使用while的時候要特別注意**終止條件**，以免程式陷入無限迴圈。
終止條件通常寫在while後面或是while裡面寫一個if
```python=
n = 1
while n<5:
    print(n)
    n = n + 1
```
or
```python=
n = 1
while True:
    if n<5:
        print(n)
    n = n + 1
```
上下兩個都是一樣的意思，不過大家會比較喜歡上面那種寫法。

#### for
基本結構就是
```python=
for 變數 in 字串或是串列:
    敘述
```
這樣寫你的變數就像是一隻百變怪，每次迴圈執行到這行的時候依序變成那個寶可夢。
炒栗子
```python=
pokemon_ball = ["皮卡丘","三地鼠","巴大蝶","素利柏"]
for Ditto in pokemon_ball:
    print(Ditto)
#output:
#皮卡丘
#三地鼠
#巴大蝶
#素利柏
```

    
