# HOLON OS 教育訓練手冊
### CH1 軟體介面介紹

<img src="homepage.png"  width="450px" />

1. 訊息列表
1. 製程流程圖
1. 3D環境互動介面
1. 智慧感測元件整合
1. 製程工單與運行狀態
1. 製程參數與工單列表

### CH2 權限系統

為保障資訊安全性，軟體內共有四種權限身份，您可以為不同使用者定義不同身份。
* **身份與權限**

|  等級  |   0   |   1   |   2   |  Max  |
|-------|-------|-------|-------|-------|
| 更改密碼 |   x   |   o   |   o   |   o   |
| 更改工單參數 |   x   |   o   |   o   |   o   |
| 更改工單設定 |   x   |   x   |   o   |   o   |
| 更改模塊參數 |   x   |   x   |   o   |   o   |
| 設定模塊連線 |   x   |   x   |   x   |   o   |
| 設定TCP伺服器 |   x   |   x   |   x   |   o   |


### CH3 建立製程

* **功能模塊**

|圖示|說明|圖示|說明|
|----|----|----|----|
|<img src="function block/Init.png"  width="250px" />|系統初始化模塊，流程的起始點。|<img src="function block/Finish.png"  width="250px" />|系統完成模塊，流程的結束點。|
|<img src="function block/QString.png"  width="250px" />|字串模塊，使用者輸入字串訊息，如產品、執行程序名稱等。|<img src="function block/Timer.png"  width="250px" />|背景計時執行模塊，可啟動多組多執行緒，並設定執行頻率。|
|<img src="function block/SelectWorkSheet.png"  width="250px" />|工單選取模塊，系統會依照待執行工單中，選擇最適合的工單。|<img src="function block/MySQLBlock.png"  width="250px" />|SQL資料庫模塊，讀取與更新SQL資料庫中資訊。|
|<img src="function block/CallRobot.png"  width="250px" />|機器人程序執行模塊，啟動機器人執行目標程序，確認程序執行完成後，將執行權往下傳遞。|<img src="function block/RobotSetData.png"  width="250px" />|機器人暫存參數設定模塊，依據製程參數設定介面中設定的工單數據，傳遞更新資訊至機器人暫存器。|
|<img src="function block/RobotViewerSync.png"  width="250px" />|機器人虛實同步模塊，將機器人位置、角度與狀態資訊同步至虛擬環境中，模擬窗格的機器人將與實機同步。|<img src="function block/PathPlanning.png"  width="250px" />|機器人路徑規劃模塊，機器人依當前位置為起始點，規劃路徑至終點，過程中依據最短路徑、姿態最適路徑與無碰撞路徑。|  
  
* **連線方式**

以Max等級身份進入軟體後，您可以對模塊連線設定進行修改。
|圖示|說明|
|----|----|
|<img src="function block/Init.png"  width="250px" />|123|

在製程流程圖區塊中，點選**Load Blocks**，即可看到畫面顯示所有功能模塊。  



### CH4 機械手臂連線

* **連線設定**

### CH5 建立工單

* **工單設定**
* **參數設定**
* **建立排程**

### CH6 開始加工
