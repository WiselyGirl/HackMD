<style>
    h2 {
        /* text-align: center;  */
        height: 30px;
        font-size: 18px;
        font-weight: bold;
        color: rgb(0, 96, 149);
        background-color: rgb(220, 245, 255);
/*         background-color: rgb(0, 96, 149); */
    }
    h3 {
        font-size: 16px;
        font-weight: bold;
        color: rgb(0, 96, 149);
    }
    h4 {
        font-size: 14px;
        font-weight: bold;
        color: rgb(0, 149, 96);
    }
</style>

# 簡介
Python 搜集、整理資料，建立視覺化報表，例：投資理財、市場調查、關鍵字行銷、商品比價、資產配置、NBA比賽數據…數據分析。




# 安裝 IDE
## 官網版
### 步驟
開啟官網：https://www.python.org/
![](https://hackmd.io/_uploads/rJfGZpf-p.png)

![](https://hackmd.io/_uploads/SJ1U-TfZp.png)



## ANACONDA 版
- 在 ANACONDA 有很多開發環境，如 Spyder、Jupyter notebook…等



### 步驟
開啟官網：https://www.anaconda.com/
下載安裝程式
![](https://hackmd.io/_uploads/SyHFzafZT.png)

![](https://hackmd.io/_uploads/BJ8hQpG-T.png)



安裝好執行Anaconda

![](https://hackmd.io/_uploads/SkvU2CfW6.png)

![](https://hackmd.io/_uploads/HkvBnRfWa.png)

![](https://hackmd.io/_uploads/BJkveJQbT.png)


<br><br>




## 執行 IDE Spyder
![](https://hackmd.io/_uploads/r1SgWJ7ba.png)


## IDE Spyder 程式簡介

### 修改字型、顏色…等環境設定

![](https://hackmd.io/_uploads/BJuyzkQZT.png)

![](https://hackmd.io/_uploads/S1d5mJmZa.png)




### 自訂視窗

![](https://hackmd.io/_uploads/ryAsmMVb6.png)

![](https://hackmd.io/_uploads/r1uKLM4-p.png)

<br><br>














### 撰寫時常用功能

![](https://hackmd.io/_uploads/B1OImmVbT.png)

- 執行程式 F5<br>
  不會執行中斷和偵錯

- 下斷點<br>
 ![](https://hackmd.io/_uploads/HJDVvGNbp.png)

 
 
 






#### 關於 IPython Console 窗格
![](https://hackmd.io/_uploads/SkVAH74-p.png)

- 程式執行完 會顯示「In [#]:」<br>
![](https://hackmd.io/_uploads/ByW2v7NWa.png)

  
- 偵錯模式執行 Ctrl+F5<br> 
  ![](https://hackmd.io/_uploads/SJZNxXNWp.png)




















<br><br><br><br><br><br>
# 進入程式
## 註解
- 單行註解於前面加一個「# 」
- 多行註解以三個「'''」(單引數)或「"""」(雙引號)包起來
```javascript=
# 這是單行註解

'''
這是多行註解
abc
'''

"""
這是多行註解
123
"""
```




## 型態 Type


### 數值  Int(整數)、float(浮點數)、bool(布林值)


### 字串  str
- 用「'」(單引號)或「"」(雙引號)包起來
- 多行可用三個「'」(單引號)或「"」(雙引號)包起來
```javascript=
x ='abc'

print (x)

# 多行 三個「'」(單引號) 示範
x =''' 
ABC
DEF
GHI
JKL
'''
print (x)

# 多行 三個「'」(雙引號) 示範
x =""" 
ABC
DEF
GHI
JKL
"""
print (x)

print (type (x))
```
<b>結果</b>
![](https://hackmd.io/_uploads/rJVK0X4-a.png)


### 序列  List(串列)、tuple(數組)


### 集合  set


### 對映  dict(字典)


## 型態相關函數
### type() 查變數型態
```javascript=
x = 10
print (type (x))
```
結果
![](https://hackmd.io/_uploads/ry6DaQ4W6.png)
<br><br>







