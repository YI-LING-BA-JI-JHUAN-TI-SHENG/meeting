# meeting 紀錄

## 107.06.21
+ frame
  + 預設時狀態map,odom,footprint同一點
  + 初始時狀態odom相對map
  + 移動後狀態footprint相對odom
  + odom,map初始化後都固定不動
  + odom是機器人初始位置宣告，所以可以相對map移動
  + 移動後要看footprint
  + navigation時會看footprint自動回推到相對map
  + 四大frame都會存在，不用amcl時odom不會接上map
  + footprint應該接odom跟map
  + 但有限制，避免錯亂
  + 所以footprint-\>odom-\>map
  + joint有斷開是合理的
  + 利於省略中間的機構或材料
  + same frame
  + child的origin參考同frame的joint
+ model robot作其他投影片
+ material name gazebo 修改測試
+ 投影片修改: xacro寫法，不是urdf
+ 執行時一定要有urdf，所以macro會自動轉換成urdf
+ [relative mesh](https://answers.ros.org/question/263308/is-it-possible-to-use-relative-path-for-mesh-filename-in-urdf/)
+ navigation
  + sensor transforms 是為了要知道sensor位置
  + 寫出客製化的部分
+ goal reach的判斷方式
+ 投影片修改: map不等於world file,也不等於map frame
+ 用多台車寫成一台車
+ [x] 投影片修改: .js, .min.js差別

## 107.06.07
+ 機器人換位置時要navigatuon要改什麼檔案
+ 不換位置出現錯誤重新跑gmapping就可以解決不用改位置
+ 中央控制完成
+ 教學：
    + rosbridge
    + navigation
    + 訂閱發佈的用法src
    + master用bridge溝通

## 107.05.24
+ 畫地圖
+ 虛實整合的誤差
+ 測速度

## 107.05.17
+ 看實驗室

## 107.05.10
+ tcp udp
+ - [x] 用非同步達到同步效果
+ - [x] 哪些公司
+ - [x] 相中(錯字)
+ 整合異質的溝通方式，缺乏共通溝通介面，預期未來走向
+ - [x] 目的，機器人協同合作系統
+ tf整理
+ 機器人網路監督即控制介面
+ 無人旅宿服務系統
+ 虛實給東西都會動
+ 中央控制什麼功能
+ - [x] 送餐、被子用
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
