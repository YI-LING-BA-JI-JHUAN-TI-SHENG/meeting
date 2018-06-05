# meeting 紀錄

## 107.05.24
+ 畫地圖
+ 虛實整合的誤差
+ 測速度

## 107.05.17
+ 看實驗室

## 107.05.10
+ tcp udp
+ 用非同步達到同步效果
+ 哪些公司
+ 相中(錯字)
+ 整合異質的溝通方式，缺乏共通溝通介面，預期未來走向
+ 目的，機器人協同合作系統
+ tf整理
+ 機器人網路監督即控制介面
+ 無人旅宿服務系統
+ 虛實給東西都會動
+ 中央控制什麼功能
+ 送餐、被子用
+ 派遣最近的機器人
+ 架構系統有什麼元件畫出環境，用ros的架構的
+ 流程圖是否空閒由機器人自己判斷，空閒再去中央控制查詢地點，記錄機器人空閒狀態
+ 是否在機器人記錄狀態？
+ 架構>情境流程圖
+ 記錄真實各元件的版本
+ 下載的機器人內容有什麼東西
+ catkin make
+ 網頁怎麼控制機器人
+ cp qrtest指令
+ navigation rviz截圖
+ navigation改進的文件

## 107.05.03
+ 哪些元素
+ world,幾個機器人幾個QRcode
+ room 服務：從客房帶到位置
+ guide 服務：從當前位置或起點帶到位置
+ 版本控制

## 107.04.26
+ tf tree, tf的欄位
+ 只需要寫yanl不需要pgm
+ laser scanner圖片截錯
+ 機器人重心，輪胎加大，穩定
+ 雷射打的距離調小
+ 迷宮牆壁距離加大
+ 轉太大力，速度太小
+ topic的更新速度
+ 接相機再去訂閱gazebo裡面的相機
+ 網頁訂閱barcode
+ plugin跟nodelet
+ zbar workspace的相依套件

## 107.04.19
+ gazebo uvc cam
+ [x] qr旋轉讀取
+ robot state joint state 到 tf 流程
+ navi stack圖的點線面，每個方塊的說明
+ world 不是 map，機器人掃描後才是map
+ amcl （課本144）避障？
+ manager controller跟一般node差別
+ 機器人一開始的座標導致map建置歪掉，base link 往上移動
+ 改laser cam的方式，改哪個檔案哪一行，或是課本哪一頁
+ 建置完map之後要重新開啟gazebo
+ 點在非直線的地方，或global map
+ 網頁上看圖
+ 不同機器人的navi需要不同黑盒子（？
+ gazebo建好map後在放到實際

## 107.04.12
+ map 不連續 長期
+ launch type
+ odometry
+ rviz 直接看機器人
+ navigation
+ 執行順序
+ qr code 新產生方式
+ becon

## 107.03.29
+ nodelet
+ blender
+ 防火牆

## 107.03.19
+ 硬體清單
+ path planning
+ .cpp .so在哪
+ rrbot/camera 哪個機器人的哪個相機
+ 步驟跑什麼指令
+ 找圖片誤差
+ odom跟畫面關係
+ 相機collision
+ sdf mesh 架構
+ ros qrcode
+ 為何用qr code
+ 多臺
+ 前進卡頓
+ 情境

## 107.03.12
+ roslauch解除方式
+ js偵測放開
+ 直接include sdf
+ 顯示收到topic
+ mesh兩個桌子

## 107.01.25
+ 不管進度如何都要做投影片
+ 0.195
+ parent link "name"
+ 物件長寬高
+ 圖上表示長度
+ 座標軸
+ xacro

## 106.01.04
+ rv v.s. ga
+ 流程圖2，3章
+ word
+ http
+ origin流程

## 106.11.30
+ 同台機器使用port分辨
+ container docker
+ graph截圖
+ 三種語言都學，找其他版本
+ 利用同樣功能來快速學習
+ actionlib多看
+ 外層包一個查看參數為何再決定用傳統try. catch或是actionlib，較彈性的程式
+ launch編寫
+ code review comment
