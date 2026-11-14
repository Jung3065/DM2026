# W8-排列組合與死亡機率 (Combinatorics & Probability)

## Basic Counting (The Accumulator)/使用迴圈計算發生次數
<img width="622" height="312" alt="image" src="https://github.com/user-attachments/assets/0756b216-7d51-4273-b9e9-ac844a72b219" />

## Python's .count() Method/使用內建方法計算 1D 陣列
<img width="587" height="265" alt="image" src="https://github.com/user-attachments/assets/89ec05db-ef56-4d8e-8671-5f2dcef35899" />

## Counting in 2D/從巢狀結構中萃取計數
<img width="525" height="317" alt="image" src="https://github.com/user-attachments/assets/ac62bc8f-4390-4c28-a172-2a098bad7436" />

## The Factorial Function (n!)/計算一個集合的排列數
<img width="545" height="311" alt="image" src="https://github.com/user-attachments/assets/e5f758b1-3090-439b-841a-b087bd14305f" />

## Permutations P(n, k)/選擇並排列子集
<img width="577" height="315" alt="image" src="https://github.com/user-attachments/assets/332393d4-518b-4e3b-b675-a9556d0f6300" />

## Combinations C(n, k)/選擇順序不重要的子集
<img width="681" height="310" alt="image" src="https://github.com/user-attachments/assets/83461525-1a2a-4b1f-b94f-257c4c3c4717" />

## Basic Probability Ratio/計算古典機率 P(E)
<img width="646" height="290" alt="image" src="https://github.com/user-attachments/assets/17080499-e34e-4b29-bf17-7ed5e68f5b9d" />

## Percentage Formatting/將小數渲染成人類易讀的百分比
<img width="577" height="287" alt="image" src="https://github.com/user-attachments/assets/9d8e7b34-5d5a-4948-8262-9c92babe12f0" />

## Complementary Probability/計算 1 - P(E)
<img width="562" height="275" alt="image" src="https://github.com/user-attachments/assets/fe2cbd71-8b89-462f-a76a-2ab8f1b644e9" />

## Dynamic Probability Update/隨著狀態空間縮小更新機率
<img width="592" height="307" alt="image" src="https://github.com/user-attachments/assets/8aa5f56f-cdd5-4715-bdda-09d717ccedb3" />

## Independent Events/將機率相乘
<img width="562" height="267" alt="image" src="https://github.com/user-attachments/assets/3a26dcea-4e0d-4f4f-ab18-8ea09f0f1aee" />

## Sum Rule vs Product Rule/OR 加法 與 AND 乘法
<img width="512" height="265" alt="image" src="https://github.com/user-attachments/assets/60c0a434-0de4-472e-b2b4-3ff065078cfb" />

## Expected Value (期望值)/計算平均預期結果
<img width="597" height="287" alt="image" src="https://github.com/user-attachments/assets/7bb9aeb3-72c9-4e98-975f-3929d9dc2242" />

## Zip Function (Pairing)/將兩組離散資料結合
<img width="600" height="287" alt="image" src="https://github.com/user-attachments/assets/4992e349-b2a5-4b75-8731-c432d7de9086" />

## Frequencies with Dictionaries/將獨立狀態映射至計數。
<img width="527" height="310" alt="image" src="https://github.com/user-attachments/assets/efb0f31e-784a-4760-89cd-06ad0f8df55a" />

## Generating Itertools Combinations/窮舉列出所有組合狀態
<img width="587" height="315" alt="image" src="https://github.com/user-attachments/assets/49e83c3d-e16e-4b5d-9bed-b02209f37c60" />

## Generating Permutations/窮舉列出所有排列狀態
<img width="562" height="307" alt="image" src="https://github.com/user-attachments/assets/dc19cf4e-e3cd-434b-850c-489ea332be14" />

## Probability of 2 Independent Mines/結合地雷的機率
<img width="891" height="261" alt="image" src="https://github.com/user-attachments/assets/34ccbbee-de14-4b6f-a318-69310a3a39bd" />

## The Max Probability Logic/決定最危險的板塊
<img width="512" height="265" alt="image" src="https://github.com/user-attachments/assets/e1f7635d-bfec-4ff1-a039-5dd0fa6651f9" />

## Boolean Masking (Counting True)/高效加總布林評估結果
<img width="592" height="290" alt="image" src="https://github.com/user-attachments/assets/bc8fe628-c6b6-46f1-b626-a98276c46dc3" />

# 核心重點
- Counting（計數）：計算某件事情發生幾次。
- Factorial（階乘）：計算所有物品的排列方式。
- Permutation（排列）：選擇物品，而且順序重要。
- Combination（組合）：選擇物品，而且順序不重要。
- Probability（機率）：計算某個事件發生的可能性。
- Expected Value（期望值）：計算長期平均預期結果。

## 核心觀念
| 觀念 | 意義 | Python |
|------|------|------|
| Accumulator | 累加計數 | += |
| Count | 計算出現次數 | .count() |
| Factorial | 階乘 | math.factorial() |
| Permutation | 排列 | math.perm() |
| Combination | 組合 | math.comb() |
| Probability | 機率 | 目標數 / 總數 |
| Complement | 補事件 | 1 - P(E) |
| Independent Events | 獨立事件 | 機率相乘 |
| Expected Value | 期望值 | 數值 × 機率 |
| Dictionary | 字典 | {key: value} |
| Zip | 配對資料 | zip() |
| Itertools | 排列組合工具 | itertools |

# 教學思路
情境:設計一款簡單的尋寶遊戲

## 第一階段:計數
先準備一張地圖，裡面有安全格、地雷格。

問初學者:「這張地圖裡面到底有幾個地雷？」

這時候就使用：
- for
- count()
- +=
- sum()

讓他們知道電腦可以幫忙統計資料。

## 第二階段:排列與組合
假設有三個寶物 A、B、C。現在要挑兩個。

問:「如果先拿 A 再拿 B，跟先拿 B 再拿 A，算不算同一種？」
- 如果不一樣，就是排列。
- 如果一樣，就是組合。

## 第三階段:機率
假設地圖總共有 81 格，其中 10 格有地雷。

問:「如果隨便選一格，有多大的機率踩到地雷？」

讓初學者自己理解：P(地雷)=10/81 ---> 這就是機率。

## 第四階段:獨立事件與期望值
問:「如果連續玩兩次，每次都有 50% 機率成功，兩次都成功的機率是多少？」

答: 0.5*0.5=0.25

然後再帶入期望值:「如果遊戲成功可以得到 10 元，失敗會扣 1 元，長期平均會得到多少？」

讓他們理解期望值不是保證獲得的金額，而是平均預期結果。

## 第五階段:整合程式
最後可以讓初學者觀察：
- Dictionary：記錄每種結果出現次數。
- itertools：列出所有可能的選擇。
- max()：找出最高風險。
- sum()：統計符合條件的資料。
這樣就能把前面學過的程式技巧串起來。

# 降維說明法
想像我們現在正在玩一款尋寶遊戲。地圖裡有安全格，也有地雷格。
- 計數 ---> 我們知道地圖上總共有幾個地雷
- 我們要挑選寶物，就會遇到排列和組合的問題。
- 拿取順序有差別，就是排列；不在乎順序，就是組合。
- 機率 ---> 我們想知道踩到地雷的可能性
- 連續發生兩件互相獨立的事情，就可以把兩個機率相乘。
- 期望值 ---> 計算遊戲長期下來平均能得到多少獎勵
1. 排列看順序，組合不看順序。
2. 機率就是目標結果除以所有可能結果。
3. 期望值是長期平均的預期結果，不代表每次實際結果。
