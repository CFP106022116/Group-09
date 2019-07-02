#Group-9
#主題
Random walk
#組員

106022218林星學
106022116江瑞軒
106022213劉醇喆

#目的
在大一下的應用數學課程中，洪在明教授提到Random walk，也推導了公式，雖然重點是學習相關的數學技巧，但是我們聯想到布朗運動在巨觀上就是一種隨機的運動，只是從一維變成三維。然而布朗運動在微觀上，是由極大量的氣體分子碰撞在目標物上，最後決定出當下瞬間的合力方向，與random walk的原因比較不一樣。因此我們希望藉由這次期末報告，利用Python模擬出粒子在經過隨機碰撞後的軌跡。

#原理
1、布朗運動：
    這裡我們碰到一個問題，由於布朗運動是由大量碰撞造成，比較像是描述隨機碰撞，而並非自主發生隨機運動，因此我們無法簡單的給定一個隨機變數，然後將這組     變數對應到前進方向；我們必須加入其他粒子，讓他們彼此碰撞，最後追蹤其中一顆的軌跡，觀察是否類似布朗運動。
2、碰撞：(我們假設皆為彈性碰撞)
    一開始在寫程式時，我們利用簡化過的碰撞公式去描述粒子經過碰撞後的行為，等到最後階段，再將碰撞的公式改成正確的，就可以順利模擬碰撞。
    

#程式步驟
1、創建粒子速度、位置矩陣(每個時間點)(每個粒子)
2、將碰撞條件及碰撞後行為加入(簡化的碰撞)
3、測試模擬程式的正確性
4、增加邊界(受限於電腦性能，無法增加粒子數，因此設立邊界，維持粒子密度)
5、給粒子初速滿足常態分布(盡量調整成類似波茲曼分布)
6、將碰撞公式轉換成正確的版本
7、最後模擬

#分工
106022218林星學
負責找原始資料，程式部分負責一開始的參數設定。討論以及給如何完成程式的建議(Debug)。製作最後的ppt。

106022116江瑞軒
程式部分負責最後的繪圖與調整以找到最好的模擬。討論以及給如何完成程式的建議(Debug)。上台presentation。

106022213劉醇喆
主要負責主要程式碼的編寫。討論以及給如何完成程式的建議(Debug)。將數學式子轉變成程式碼。



