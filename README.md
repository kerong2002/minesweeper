# minesweeper
踩地雷2.0
遊玩方式:
以所選取該點，開始掃雷，場上數字是以它為中心的九宮格，標示炸彈的數量，
例:
```py
💣 💣 2
💣 4  2
1   2 💣
```
數字4周圍的九宮格含有四顆炸彈，所以中間標示數字為4  
**目標**: 不要踩到任何炸彈，除去非炸彈的位置，即可獲得勝利  
          不插旗幟，點完全圖非炸彈位置，也視為勝利  
高度:9格  
寬度:9格  
炸彈數量:10顆  
編寫程式:python tkinter    
![image](https://github.com/kerong2002/minesweeper/blob/main/minesweeper.PNG)  
 
#2023/04/21 更新  
====
功能補齊:  
1.滑鼠左鍵開啟該方塊  
2.滑鼠右鍵插下旗幟(第二次取消插旗)  
3.menu菜單(可刷新new game和離開)  
4.笑臉可以刷新  
5.踩地雷贏了會變臉  
6.踩到炸彈會哭臉  
7.踩到的那顆炸彈會顯示不同顏色  
8.插錯旗幟(插到不是炸彈的位置)會打X  
 
#2023/04/22 更新  
====
功能補齊:  
1.滑鼠中鍵特殊擴散(前替是點擊該點數字周圍有相對應數量的旗幟數)   
2.時間不會有停止計算狀況  
3.炸彈數量除錯  
4.贏了會自動插旗幟且炸彈數量會顯示0  
 
#2023/04/23 更新  
====
功能補齊:  
1.數字顏色  
2.旗幟顏色    
3.字體大小和位置調整  
4.場地顏色  
5.按鈕浮起  
6.笑臉按鈕調整位置  
7.menu菜單的help更新
8.按鈕大小調整
 
#2023/04/23 v2.0 pro版本  
====
功能調整:
1.新增滑鼠游標會在笑臉上有不同圖標  
2.提供關卡難度選擇  
3.easy模式為9*9的大小(10顆地雷)  
4.normal模式16*16的大小(40顆地雷)  
5.更正easy的視窗大小  
6.更正整個視窗的按鈕安排與大小  
7.除去舊有的Button and Label  
 
#2023/04/24 v3.0  
====
功能改進:  
1.三種難度選擇  
2.新增hard模式，30*16的大小(99顆炸彈)  
3.炸彈、笑臉和計時位置修改  
4.視窗大小調整  
5.重新制定按鈕大小  
6.menu字體調整  
發現問題:  
1.建置場地的速度過慢(演算法耗時)  (尚未修正)  
2.左右建尚未建置功能   (已改善)
 
#2023/04/24 v3.1  
====
小功能改進:   
1.炸彈bug測試  
2.模式菜單改進  
 
#2023/04/24 v3.2    
====  
小功能改進:
1.配置數字作些許調整    
2.左右鍵功能加入  
3.修改做鍵鍵觸發規則  
 
#2023/04/24 v3.3    
====  
功能改進:    
1.按鈕位置加上外框  
2.建置和刷新button調整寫法(加速)  
3.新設定按鈕調為跟外框做調整，填滿整個外框  
4.調整視窗大小  
5.smile和Label位置調整  
