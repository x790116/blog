# 2108-10-22(二) 呂毅 CSM Day1

終於開啟了第一篇寫部落格的計畫

先前參加了 CSD, DevOpsDays 2018, 公司內部 AWS 教育訓練

都是上課很認真, 下課很天真 (~~誤~~)

希望日後都可以將心得補起來... 吧 

##### 這次就先由連續四天 CSM+CSPO 的心得來記錄

##### 希望可以每天課後紀錄, 持續交付 ~~(富奸退散)~~

---
在課堂一開始, 呂毅老師就告訴我們一個很重要的觀念
> #### 如何將上課的內容內化, 並帶回團隊甚至影響公司, 是一大重點！

我想這個觀念應該要讓每一個參與 Scrum 相關認證的人都謹記在心

因為往往看到很多人都是為了拿認證而拿認證

但是看了一些案例, 才發現時真正的高手都是 **藏在民間**
> #### 意思就是必須經過不斷的練習與實務上的應用, 才能真正將這些方法落實
  
## 扯遠了... 接下來我們來回顧一下第一天的一些內容與練習

---

首先是學員問題, 下面我先將我自己提出的問題給列出
> 写下您对参加这个课程的目标发给我，我们也会在课程开始时分享。
```
1. 如何更了解 Scrum 更落實 Agile 相關精神, 但卻又不會不小心被框架給綁架？
2. 如何有效的召開一個好的回顧會議 (Retro), 並讓每個人都能有所收穫並持續進步改善？
3. 究竟是專職的 Scrum Master 較好？抑或是團隊成員兼任 Scrum Master 有幫助？
4. 如何利用 Scrum 甚至是 Kanban 落實在團隊之中, 尤其是運維團隊？
5. Scrum Master 相關的軟技能該如何被量化？如何呈現出他的價值？
```

接下來的是其他同學提問較有印象的部分
```
1. Scrum 有 Deadline 這樣會不會衝突？
   > 同學... Scrum 有 Timebox 的概念... 所以也有 Deadline 呀...
    
2. 開發的目標太大, 請問要如何應對與調整
   > 在接下來的 Sprint Planning & Sprint Backlog 會提到

3. 一個 Scrum Master 面對提問時如何有耐心不要說出答案?
   > 這或許不是個問題, 你要當作你自己也不知道問題的答案
   > 又或者說, 你認為的這個答案真的是正確的嗎？
    
4. 公司的組織一直在變動, 導致 Scrum Team(SM+PO+Team) 一直變怎辦？
   > 理想上 Scrum Team 的成員是盡量不要一直變動
   > 因為就是需要這個成熟的 Team 來適應不斷變動的需求與市場
   > 但如果一直變動, 考驗的就是 SM 重塑團隊凝聚力的地方了
```
---
### Scrum Master 的職責
1. Coach Team
2. Coach PO
3. Facilitate(引導) - ***這也是最重要的！***
4. No answers, just questions.

### 而常常聽到 Scrum 還有 Agile(敏捷) ,兩者的關係是...？ 
> ## Scrum is one of Agile Engineering Practice
> 又或者說
> ## Scrum is a Framework, it implement Agile
---
# Origin of Scrum
1. The New, New Product Development Game*
   > 用新的方式, 來開發新的產品
2. Iterative, Increamental Development, Timeboxes
   > 迭代(週期性), 增量式的軟體開發, 並且有時間限制(Deadline) 
3. Lean 的精神
   > 精實(Lean) 是 TOYOTA 生產線的其中一個方法論
   
   > 以前生產車子都是每個組件大量生產, 專職分工
   > 訂一部車要2個月才能拿到, 但實際上在生產你車子的時間只有2天
   
   > Cycle Time 的概念
   
   > Kanban 也是 Lean 方法論的其中一個實踐
   
   > Poppendieck 夫婦 將 TOYOTA 的 Lean 落實在軟體開發 

   > David J. Anderson 將 TOYOTA 的 Kanban 落實在軟體開發

# Scrum 框架的概念
### Team 有能力可以在 Timebox 內去交付 Shippable Product
### 並且可以在 Cross-Functional 中做到 Self-Organized
---
# 下面開始講述如何用 Scrum 去落實 Agile

我簡單用一張圖帶過
![](https://ppt.cc/fs6RYx@.jpg)

> 主要是在講述產品開發黃金鐵三角

> 以及敏捷宣言與 Scrum Practice 的關係
---
# Inspect & Adapt 
這一段主要講述 Goal 目標的訂定, 以終為始的概念 

> ### Scope 不是你該糾結的問題, 定好目標, 關注目標
> ### Scope 不能變是因為你沒有在關注價值 (Impact Mapping)

## Cycle 縮小, Feedback 加快
> Task -> PBI      
> => Coach Team

> PBI -> Inspect  
> => Coach PO

筆記：

1. PSPI : Potentially Shippable Product Increment
2. PBI : Product Backlog Item ( Item 層級)
3. Task : 就是團隊拆分的小黃卡片( Task 層級)

Team 關注於 Task 層級的迭代優化, 也須往上關注 Item 層級的交付

PO 關注 Item 層級的迭代優化, 也須往上關注 Inspect 層級的目標

![](https://ppt.cc/fdpzPx@.jpg)

---
## 在 Sprint 中, PBI No Change, but Task Can Changes.

### 由 Why -> What -> How 三個層級去拆解任務
> 來人啊, 上圖！
![](https://ppt.cc/fgitOx@.jpg)

### 額外再加碼問題與名言
1. PO & Team 到底誰該寫 PBI(Product Backlog Item) ?
   > 一起寫阿...
2. 一個晚了的 Project, 再加人進去只會更晚...
3. Agile : 靈活性響應變化
---
# 松鼠漢堡的故事...

> 公開, 透明, 風險

> 最直接的風險承擔者, 應該要是決策的人
---
# MLBTix 的 Practice 練習

> Risk Uncertainty

> Requirement Understanding

> User Involvement

> Cash flow => Security

> Time Schedule 

---
# DoD (Definition of Done)
### 這是 Team 與 PO 之間的約定

## Not done backlog items should not be demo-ed
> ### 沒做完的半成品不該拿出來 ~~丟人現眼~~ 展示 
> ### 這件事是 Scrum Master 的職責
> 

Done 分成兩個導向： 產品導向 與 過程導向 
---

最後是講述 Sprint Planning & Sprint Backlog 的部分

有點累了.... 明天再繼續吧 XD