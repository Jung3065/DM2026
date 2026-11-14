# W5-The Matrix Awakening (資料矩陣的覺醒)

## The Empty Vector/建立一維離散容器
<img width="472" height="312" alt="image" src="https://github.com/user-attachments/assets/224d7435-28fd-4957-9683-971df8d0ffc4" />

## The 2D Concept/巢狀串列建立二維空間
<img width="577" height="295" alt="image" src="https://github.com/user-attachments/assets/146ee609-da45-4b8b-b8a8-518634a57cd2" />

## Accessing 2D Elements/精準鎖定特定座標 [r][c]
<img width="447" height="292" alt="image" src="https://github.com/user-attachments/assets/4192c424-a596-40fd-bd56-40fe78e6cd54" />

## Modifying 2D Elements/改變矩陣內部的狀態
<img width="446" height="292" alt="image" src="https://github.com/user-attachments/assets/3a16b39b-ecd6-4462-8374-8c454cf66828" />

## The IndexError Boundary/理解嚴格的數學極限
<img width="567" height="267" alt="image" src="https://github.com/user-attachments/assets/885d38c4-fa94-4574-a105-0b020ec28432" />

## Matrix Height (Rows)/測量 Y 維度
<img width="527" height="267" alt="image" src="https://github.com/user-attachments/assets/d133c1ee-e1af-4363-b55f-bffb17ae7c9a" />

## Matrix Width (Cols)/測量 X 維度
<img width="550" height="267" alt="image" src="https://github.com/user-attachments/assets/ecd6e783-37ed-4d0d-a579-8971854eacef" />

## Iterating Rows/垂直走訪矩陣
<img width="567" height="282" alt="image" src="https://github.com/user-attachments/assets/b79cddaa-c1fb-4aa4-9aed-f8c269a9c71a" />

## Nested Iteration (Elements)/走訪每一個獨立座標
<img width="567" height="331" alt="image" src="https://github.com/user-attachments/assets/28f56910-70e6-4fd7-80cf-5ada4dd2cd55" />

## Formatted 2D Printing/將原始資料渲染成視覺網格
<img width="522" height="262" alt="image" src="https://github.com/user-attachments/assets/90ea837f-dfa0-4048-925c-5187ddf5e1a6" />

## List Comprehension (1D)/動態且高效地產生串列
<img width="612" height="267" alt="image" src="https://github.com/user-attachments/assets/0505ac1c-fa57-4d61-aeca-5b5c90f74a9b" />

## List Comprehension (2D)/動態產生完整矩陣
<img width="652" height="267" alt="image" src="https://github.com/user-attachments/assets/6c85561a-59f1-4ffe-8838-994ce58fe57f" />

## The Reference Trap/避免意外地將參照相乘
<img width="622" height="267" alt="image" src="https://github.com/user-attachments/assets/e6627ff6-67b9-4c7f-b711-26df77bf758c" />

## Enumerate() for Rows/在迴圈中同時追蹤索引
<img width="531" height="265" alt="image" src="https://github.com/user-attachments/assets/58b66080-76d0-4518-94ee-1d408bba9bfe" />

## Enumerate() for Cells/在迭代時萃取絕對座標
<img width="677" height="327" alt="image" src="https://github.com/user-attachments/assets/2d869ff7-4249-445a-a9f9-067c009d7625" />

## The Identity Matrix/將邏輯應用於矩陣座標
<img width="597" height="272" alt="image" src="https://github.com/user-attachments/assets/365f986e-65ad-4581-a7cb-544114160bb3" />

## Boolean Matrices/在二維中儲存二元狀態
<img width="630" height="267" alt="image" src="https://github.com/user-attachments/assets/3b678909-4fac-47ca-b62c-0be8fe64f3a4" />

## String Join/將陣列合併為乾淨的字串
<img width="476" height="271" alt="image" src="https://github.com/user-attachments/assets/c48ae98b-4122-4e00-9eb2-a5c6352692ab" />

## Flattening a Matrix/將 2D 在概念上轉換為 1D
<img width="432" height="265" alt="image" src="https://github.com/user-attachments/assets/e01345fc-41c5-41d6-b4a2-0d39d6f7de3e" />

## Validating Dimensions/檢查矩陣是否為完美的正方形
<img width="581" height="265" alt="image" src="https://github.com/user-attachments/assets/2210770e-ffcd-42b3-8257-2eae82e35023" />

# 核心重點
主要學習如何使用 Python 的 List 建立一維及二維資料結構。

## 核心觀念
| 觀念 | 意義 | Python |
|------|------|------|
| 1D List | 一維資料 | [] |
| 2D Matrix | 二維資料 | [[...], [...]] |
| Index | 索引位置 | [0] |
| Row | 列、橫向 | len(matrix) |
| Column | 欄、直向 | len(matrix[0]) |
| Nested Loop | 巢狀迴圈 | for 裡面再放 for |
| Enumerate | 同時取得索引與內容 | enumerate() |
| List Comprehension | 快速建立串列 | [...] for ... |

# 教學思路
情境:假設今天要安排教室座位

| 教學步驟 | 要講的觀念 | 生活化說明 |
|------|------|------|
| 建立座位表 | 2D Matrix | 把座位排成一個表格 |
| 找到座位 | Index | 每個座位都有自己的位置 |
| 更改座位 | 修改元素 | 有人入座就更新狀態 |
| 巡視座位 | Nested Loop | 一排一排檢查每個位置 |
| 紀錄狀態 | Boolean Matrix | 記錄座位是否有人 |

# 降維說明法
想像我們現在在一間教室，裡面有三排座位，每排有三個位置。我們用 Python 製作一張電子座位表。
每一排是一個 List，三排組合起來就是一個 Matrix。
- 我要找第二排第三個座位，就要使用座標。
- 有人坐下去了，我們就把那個位置的數字改掉。
- 老師想知道整間教室有多少人，就可以利用兩層迴圈，一排一排、一個一個座位檢查。
1. List 就像一排置物櫃。
2. Matrix 就像很多排置物櫃組合起來。
3. Nested Loop 就像逐排巡視每一個置物櫃。
