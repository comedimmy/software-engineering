# 南華大學軟體工程-期末報告
11124213 張芮瑜 11124235 吳易軒
# 如何展示你的架構 - "4+1"視圖

「4+1」視圖是對邏輯架構進行描述，最早由 Philippe Kruchten 提出，他在1995年的《IEEE Software》上發表了題為《The 4+1 View Model of Architecture》的論文，引起了業界的極大關注，現在是軟體設計的結構標準 - 百度百科
總的來說，只要你去做匯報/寫PPT，你總是要畫一兩個視圖的。

4代表了4種視圖，1表示基於某一個場景，結合4種視圖進行說明。

## 邏輯視圖（Logical View）
設計的對象模型，改成了用UML來表示。
![Logical View](https://github.com/user-attachments/assets/b498029a-a6e0-4869-b6eb-a208a6cb2e38)
邏輯視圖｜設計的對象模型

## 過程/進程視圖（Process View）
捕捉設計的並發和同步特徵。這個圖有點抽象，主要需要表現出線程、進程之間的關係。
![Process View](https://github.com/user-attachments/assets/0c787ebc-fd37-4de9-8ebc-4864c4a6b53d)
過程/進程視圖

## 物理視圖（Physical View）
描述了軟體到硬體的映射，反映了分佈式特性。你的物理網路如何搭建。
![Physical View](https://github.com/user-attachments/assets/b19ac0c1-73c2-4aa8-9445-1b14ba6d6cbf)
物理視圖

## 開發視圖（Development View）
描述了在開發環境中軟體的靜態組織結構。包含哪些功能模組。
![Development View](https://github.com/user-attachments/assets/2d83e92d-37c3-4a66-b5a2-639bea92503c)
開發視圖
