# W6-Proofs & Sets (絕對不重複的集合論)

## The Empty Set/建立一個數學集合
<img width="566" height="272" alt="image" src="https://github.com/user-attachments/assets/5fc5cc7c-507a-4df7-a092-218c0d54497f" />

## Adding Elements/將資料加入集合中
<img width="456" height="292" alt="image" src="https://github.com/user-attachments/assets/6194ad5e-71c0-40fd-8ec4-7575e4658094" />

## The Uniqueness Axiom/證明集合會自動拒絕重複元素
<img width="525" height="292" alt="image" src="https://github.com/user-attachments/assets/df62da0c-e800-4d0d-92a9-d1c0848c3a5e" />

## Cardinality (長度)/測量集合的基數或長度
<img width="560" height="287" alt="image" src="https://github.com/user-attachments/assets/0b764381-e316-4a68-9ca6-2bac63e2bc3b" />

## List Deduplication/利用集合清除串列中的重複項
<img width="492" height="270" alt="image" src="https://github.com/user-attachments/assets/cdf4b17e-19a3-42a6-98c0-7ffffc7de567" />

## Set Union (聯集)/合併兩個集合
<img width="510" height="287" alt="image" src="https://github.com/user-attachments/assets/8c34a037-bbcc-446a-86e0-20d6bf41ca9b" />

## Set Intersection (交集)/尋找共同元素
<img width="561" height="287" alt="image" src="https://github.com/user-attachments/assets/49f3d89f-0a65-47e9-acc4-49413c51f7a0" />

## Set Difference (差集)/從一個集合中減去另一個
<img width="587" height="287" alt="image" src="https://github.com/user-attachments/assets/8c6f58e7-d36d-41f5-a120-0af5d3711f78" />

## Symmetric Difference (對稱差集)/尋找完全不共用的元素
<img width="527" height="290" alt="image" src="https://github.com/user-attachments/assets/b4cc48c0-5894-49ba-b2dc-cccd3658b075" />

## Membership in/測試元素是否屬於該集合
<img width="602" height="266" alt="image" src="https://github.com/user-attachments/assets/4a915cc5-f200-4e2b-9530-30409c6d7db4" />

## The random Library/導入隨機數字生成
<img width="711" height="287" alt="image" src="https://github.com/user-attachments/assets/33f7c2d9-7111-4f1d-b1ea-af4723d201d3" />

## Tuples as Immutable Vectors/將座標打包為不可變的元組
<img width="552" height="267" alt="image" src="https://github.com/user-attachments/assets/149e14f2-5e3b-48dd-bb91-94ef3bd1cf14" />

## Tuples inside Sets/將 2D 座標點儲存進數學集合中
<img width="536" height="287" alt="image" src="https://github.com/user-attachments/assets/21ef98ef-7b58-4a11-95f5-6564bc4d251d" />

## The remove() Method/從集合中刪除特定元素
<img width="457" height="267" alt="image" src="https://github.com/user-attachments/assets/277d0192-c8f3-4d81-bdde-81269b73da57" />

## Iterating a Set/使用迴圈走訪無序集合的元素
<img width="517" height="282" alt="image" src="https://github.com/user-attachments/assets/ad9e41f0-75fe-41f2-9579-2627000fbacf" />

## Subsets (<)/測試一個集合是否完全包含於另一個集合內
<img width="572" height="287" alt="image" src="https://github.com/user-attachments/assets/46d959e8-9ddb-41b1-a9da-a9a265f7ca32" />

## Basics of the while Loop/根據真理條件而非範圍來進行迴圈
<img width="617" height="355" alt="image" src="https://github.com/user-attachments/assets/ec90746a-296b-42cc-9d37-920ea69fada4" />

## The Infinite Trap/理解如果條件永遠不為 False 會發生什麼事
<img width="605" height="331" alt="image" src="https://github.com/user-attachments/assets/8ad74441-9b71-44ee-bd1e-e40368a9ecfb" />

## while + Set Cardinality/持續迴圈直到集合達到特定的數學大小
<img width="635" height="311" alt="image" src="https://github.com/user-attachments/assets/6e61d523-65a2-4297-845a-661bd4239377" />

## Boolean Flag Variables/使用離散狀態變數控制複雜迴圈
<img width="626" height="332" alt="image" src="https://github.com/user-attachments/assets/95b3053c-78b5-4d16-8b5f-dd34d246ee51" />

# 核心重點
- Set:儲存不重複資料
- Tuple:儲存建立後不能修改的資料
- While Loop:只要條件成立程式就會一直執行
- 四種運算:

| 運算 | 符號 | 意義 |
|------|------|------|
| 聯集 | A \| B | 把兩個集合的元素合併 |
| 交集 | A & B | 找出兩個集合共同的元素 |
| 差集 | A - B | 找出A有、B沒有的元素 |
| 對稱差集 | A ^ B | 找出兩個集合各自有、但不共同擁有的元素 |

## 核心觀念
| 觀念 | 意義 | Python |
|------|------|------|
| Empty Set	| 空集合	| set() |
| Add | 新增元素 | .add() |
| Remove | 移除元素 | .remove() |
| Cardinality	| 集合元素數量	| len() |
| Membership | 是否屬於集合 | in |
| Subset | 子集合 | < |
| Tuple	| 不可變資料	| () |
| While	| 條件成立就重複執行 | while |
| Boolean Flag | 布林狀態控制 | True / False |

# 教學思路
情境:遊樂園會員名單、尋寶遊戲

## 第一階段:教Set
假設有兩組同學：
- A 組：小明、小華、小美。
- B 組：小美、小強、小安。

思考:
| 問題 | 對應概念 |
|------|------|
| 兩組同學全部加起來？ | 聯集 |
| 兩組都有誰？	| 交集 |
| A 組有、B 組沒有誰？ | 差集 |
| 只有其中一組有誰？ | 對稱差集 |

## 第二階段:教Tuple
假設地圖上的寶藏位於 (3, 5) ---> 這組座標就是 Tuple。
可以告訴初學者:這就像一張已經印好的座標標籤，不能隨便把上面的數字改掉。

## 第三階段:教While
假設正在玩尋寶遊戲。
- 還沒找到三個不同寶物，就繼續找。
- 找到重複的寶物，不增加種類數量。
- 找到三種不同寶物，就停止。

---> while len(unique_rolls) < 3 的概念。

# 降維說明法
- Set 就像遊樂園的會員名單，同一個人不管登記幾次，名單上只會出現一次。
- 聯集就是把兩張名單合起來。
- 交集就是找出兩張名單都出現的人。
- 差集就是找出其中一張名單獨有的人。
- Tuple 就像一張不能修改的座標標籤。
- While 則像一個一直重複執行的任務，只要條件還符合，就不會停止。
1. Set 的特色是不能有重複元素。
2. Tuple 建立後不能修改。
3. While 會一直執行，直到條件不成立或遇到停止指令。
