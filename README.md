# 十八啦 coding dojo

## 活動內容

+ 已 piar programming 形式進行，一組 7 分鐘
  + 一位 driver (輸入程式碼的人)，一位 navigator (審查程式碼的人)
  + 下一輪時 navigator 變成 driver 跟下一個 navigator 再變成一組
+ 採自願排隊上台輪流 pair
+ 本次 coding dojo 採用的題目是 [十八啦](https://zh.wikipedia.org/wiki/%E5%8D%81%E5%85%AB%E4%BB%94) 

## 活動目標

+ 上台膽量
+ 不是做完，是從別人身上偷學一些思考及技巧

## 活動規則

+ 要寫測試
+ 有紅燈時要先修測試
+ 有紅燈時不能重構
+ 要寫 production code 要有測試
+ 每一輪時間到的時候至少要可以編譯

##十八拉遊戲需求

+ 兩個玩家比較點數大小
+ 需要輸出結果
  + 輸出格式範例
    + 一方勝利，Andy win, because of [6,6,4,3]
    + 平手，draw
+ 骰子規格
  + 每一個骰子點數 1 - 6 點
+ 玩家一次可以拿到四個骰子
  + 輸入範例：[1,1,2,3]
+ 骰子組合
  + 一色
    + [1,1,1,1],[2,2,2,2],[3,3,3,3],[4,4,4,4],[5,5,5,5],[6,6,6,6]
  + 十八啦
    + [1,1,6,6], [2,2,6,6],[3,3,6,6],[4,4,6,6],[5,5,6,6]
  + N 點，兩個骰子點數相同，剩餘骰子總和為 N 點，且不能有三個骰子相同
    + [1,1,2,3] -> 5點 (o)
    + [1,1,1,3] -> (x)
  + 無點
    + 四個骰子都不相同，或三個骰子相同

 