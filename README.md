## ch.10 Software Engineering

### 大綱－本章介紹

- 軟體生命週期
- 開發流程
    - waterfall 瀑布式
    - incremental models 漸進式

- 四種步驟(階段)
    - 分析 
        - procedure based
        - object-oriented
    - 設計：也是分成上面兩種
    - 實作：寫程式、軟體的品質、度量的方法
    - 測試：玻璃箱(白箱)、黑箱

``` 軟體工程會牽扯到很多文件撰寫```

- 使用者文件
- 系統文件
- 技術性的文件

### 軟體生命週期
![軟體生命週期](./img/1.png)

obsolete 過時的

Modification 調整修正

通常在 使用、修改 的階段是時間最長的

### Development Process 開發流程

不管哪種流程
都會有```分析 設計 實作 測試```這四個階段

### waterfall model 瀑布式開發

- 每個階段都全部做完 才進入下一個階段
- 就像水流一樣 因此得名
- 例如：所有的分析工作都完成時才進入設計階段
- 但在某階段出現錯誤時，是可以倒退回上一個階段，全部修完之後再進入下一階段
- 跟傳統的工程(土木、機械等等)很像

### Incremental model 漸進式開發
![軟體生命週期](./img/2.png)

x軸 時間
y軸 功能完成程度

- 例如：
Increment1完成第一個功能 (四個階段都走一遍)
Increment2完成第二個功能 (四個階段都走一遍)
．．．
- 每個階段都只完成那個increment的部分

- 是比較新的思維

```沒有哪個比較好、只有誰比較適合哪種情況```

- 小程式小團隊適合漸進式


##### 接著介紹開發流程的四個階段

#### Analysis Phase 分析階段
- 又稱為 需求工程
- 搞清楚需要什麼功能
- output: (寫著功能/需求的) 規格文件、需求規格書
- 處理 what the software will do
- 不討論 how it will be done
- (前面說過)又分成兩種做法：procedural(程序導向)的 或是oo(物件導向)的

以下將這兩個做法的analysis分開說明

##### procedural oriented Analysis 分析階段：程序導向

- 比較早出現
- 比較直覺
- 軟體由一連串的procedurals組成
- Data flow diagrams (dfd)

    - 描述資料的流向 動態的
    - 有哪些處理資料的單元
    - data被哪些procedurals處理
    - 來源、去哪、如何流動
    - 整個系統裡的procedurals也可稱為process 處理資料的單元
    
- Entity-relationship diagrams (er圖)

    - 在關聯式資料庫很常見
    - 很像是excel表單 描述欄位、資料的關係
    - 可用來描述資料的結構、靜態的關聯
    - 既然如此那就ch.12再介紹


- State diagrams (狀態圖)

    - 描述系統裡狀態的改變
    - 有events事件、刺激、
    - 可用來描述系統裡狀態的轉移
    - 舉例：電梯系統
    ![軟體生命週期](./img/3.png)
    - 停住 上移 下移 三種狀態
    - 基本的刺激 turn on/off
    - 收到request 請求 進行判斷 


##### Object-oriented analysis 分析階段：物件導向

註：人們常說的ｏｏ就是這個歐歐

- 較流行、常見、大二的系統課會再出現

- 以前介紹的流程圖也只是uml的一種、這裡介紹常用的uml圖種和觀念

- Use case diagrams（使用案例圖）

    - 從使用者的角度來看
    - 描述使用者的操作
    - 四個主要元件 system系統(灰色大框框)、use cases(紅色圓角框)、actors、relationships

- 

- 

- 

- 

- 

- 

- 

- 

- 


#### Design Phase 設計階段

- input: 需求文件
- 搞清楚需要什麼功能
- output: 設計文件
- 處理 what the software will do
- 不討論 how it will be done
- (前面說過)又分成兩種做法：procedural(程序導向)的 或是oo(物件導向)的

#### Implementation Phase 實作階段


#### Test Phase 測試階段




#### Template 文字

