## LeetCode
### 🌻1_Two Sum
利用雙迴圈來找出兩個list裡面的數加起來等於target，再將它們的index將在ans這個list裡面，最後回傳ans
### 🌻7_Reverse Integer
利用str和int的概念      
先將輸入數值轉換成字串，就可以讀出他的第幾項等於甚麼，然後再用[::-1]將其數字整個倒過來，再轉換回來int          
如果遇到負號，就要先將"-"擱在一旁，再用[-1:0:-1]將其數字倒過來，而不會讀取到第0項的"-"        
注意有大小限制!!數字部分需小於2的31次方=2147483648
### 🌻27_Remove Element
讓i用迴圈的方式慢慢增加，如果 list 的第某項=目標值，list[n]=list[i]，n也慢慢遞增       
* 其實我原本寫完覺得應該是錯的，因為如果用更改數值的方式，沒更改到的地方不是就是原本的數嗎??所以我覺得蠻奇怪的!還是我腦子轉不過來?? 但算了....對了就好~
### 🌻58_Length of Last Word
利用 split 來把字串一個一個分開，再用-1去找最後一個字串，再將它的長度輸出
### 🌻344_Reverse String
原本用[::-1]的概念，在Jupyter可以用，結果不知道為什麼leetcode就不給我用......           
所以我後來就用一個交換的概念，s[m],s[n]=s[n],s[m]，m跟n一個遞增，一個遞減
