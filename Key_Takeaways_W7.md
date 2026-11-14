# W7-函數與八方關係 (Relations & Functions)

## Defining a Function/將程式碼封裝成可重複使用的區塊
<img width="542" height="292" alt="image" src="https://github.com/user-attachments/assets/a67f4b4b-0e1c-4234-a27b-764d7bcf9570" />

## Function Parameters/將離散變數傳入函數中
<img width="547" height="291" alt="image" src="https://github.com/user-attachments/assets/9d93f536-7418-4cd4-baa7-c887d1af25e1" />

## Return Values/輸出嚴格的數學結果
<img width="601" height="286" alt="image" src="https://github.com/user-attachments/assets/b27766ee-9919-4ead-9823-1064fd023fc7" />

## Multiple Parameters/將多個輸入映射至單一輸出
<img width="622" height="282" alt="image" src="https://github.com/user-attachments/assets/3f4176a1-bf2f-454d-b65e-629a8628dfce" />

## Default Parameters/提供備用的數學狀態
<img width="592" height="335" alt="image" src="https://github.com/user-attachments/assets/470cf53c-154c-4cad-afd3-74afb2112490" />

## Local vs Global Scope/理解數學邊界(作用域)
<img width="602" height="342" alt="image" src="https://github.com/user-attachments/assets/a9b88255-0034-43dc-8dd3-e6cf421b7a25" />

## Type Hints/嚴格定義預期的定義域
<img width="547" height="296" alt="image" src="https://github.com/user-attachments/assets/9bbd9805-670c-4685-9ec2-29ca734f4285" />

## The Greater-Than Relation/評估二元關係
<img width="642" height="315" alt="image" src="https://github.com/user-attachments/assets/e391214f-8d63-4925-8567-ac05516a8a1a" />

## Bounding Limits (Max)/將數值限制在最大上限
<img width="612" height="287" alt="image" src="https://github.com/user-attachments/assets/3ca72eb9-602c-4e20-bd04-346f3eb9d416" />

## Bounding Limits (Min)/將數值限制在最小下限
<img width="572" height="290" alt="image" src="https://github.com/user-attachments/assets/97e7f169-2f8b-48f0-beca-81bd5bcedccf" />

## Cartesian Coordinates Concept/將絕對座標點傳入函數
<img width="622" height="317" alt="image" src="https://github.com/user-attachments/assets/c27d0d4f-8113-4111-af68-e0ba2b3a79a7" />

## Relative Offsets (dx, dy)/理解空間中的 Delta (變化量)
<img width="562" height="267" alt="image" src="https://github.com/user-attachments/assets/e47a44bf-6ad1-4aea-9e8d-11e74cc1c4f2" />

## Adding Offsets/將變換向量應用於一個點上
<img width="612" height="316" alt="image" src="https://github.com/user-attachments/assets/1db27054-a26a-41df-846c-0ce645b2080e" />

## Absolute Value (Distance)/找出數字的絕對量值
<img width="552" height="295" alt="image" src="https://github.com/user-attachments/assets/b39188c5-b765-4fd8-9597-c16f188cf706" />

## 1D Neighbor Relation/在一維直線上尋找相鄰的點
<img width="516" height="267" alt="image" src="https://github.com/user-attachments/assets/ba78f28b-08bf-47b3-bf4e-7aead3d056b3" />

## The Nested Offset Generator/使用迴圈產生 2D 偏移組合
<img width="575" height="292" alt="image" src="https://github.com/user-attachments/assets/d89d198b-b81a-4401-bccb-55deaa6849b3" />

## Filtering the Center/從偏移量中移除原點
<img width="617" height="267" alt="image" src="https://github.com/user-attachments/assets/fd30ba13-eaf3-4835-bf30-28856f36636c" />

## Function Returning a Tuple/同時輸出多個離散數值
<img width="592" height="292" alt="image" src="https://github.com/user-attachments/assets/48b4b88d-476b-4ec0-b625-ec721f63d281" />

## Function Returning a List/輸出一個陣列的評估結果
<img width="670" height="270" alt="image" src="https://github.com/user-attachments/assets/a19fc478-320b-4b82-9c5d-f9c566a0cc89" />

## Docstrings in Functions/在程式碼內記錄數學假設
<img width="602" height="320" alt="image" src="https://github.com/user-attachments/assets/43e08c4b-72da-4e20-8396-b1e53cbb9d27" />

# 核心重點

## 第一部分:Function
- 定義函數。
- 傳入參數。
- 回傳結果。
- 預設參數。
- 區域變數與全域變數。
- 型別提示。

## 第二部分:Coordinate
- 絕對座標。
- 相對位移。
- 座標加法。
- 絕對值。
- 鄰居位置。
- 產生二維偏移組合。

## 核心觀念
| 觀念 | 意義 | Python |
|------|------|------|
| Function | 函數 | def |
| Parameter | 參數 | x |
| Argument | 實際傳入的值 | 5 |
| Return | 回傳結果 | return |
| Default Parameter | 預設參數 | y=2 |
| Scope | 變數作用範圍 | Local / Global |
| Type Hint | 型別提示 | : int |
| Coordinate | 絕對座標 | (x, y) |
| Offset | 相對位移 | (dx, dy) |
| Neighbor | 鄰居位置 | x-1, x+1 |

# 教學思路
情境:假設要設計一個可以移動的遊戲角色

## 第一階段:教Function
告訴初學者:
我們有一台自動販賣機，只要按下某個按鈕，就能執行指定工作。函數就是這個按鈕，你不用每次都重新寫一次完整程式，只要呼叫它就可以。

| 生活概念 | Python |
|------|------|
| 按鈕名稱 | 函數名稱 |
| 投入的金額 | Parameter |
| 按下按鈕 | 呼叫函數 |
| 販賣機吐出飲料 | Return |

## 第二階段:教座標
假設遊戲角色目前位於 (5, 5)。

告訴初學者：
- 絕對座標：角色現在站在哪裡。
- 相對位移：角色準備移動多少。
- 新座標：原本的位置加上移動量。

## 第三階段:教鄰居
假設角色站在一個九宮格的正中央。

周圍有八個位置：
- 上方。
- 下方。
- 左方。
- 右方。
- 左上。
- 右上。
- 左下。
- 右下。

---> 這就是2D Offset Generator。

# 降維說明法
- 函數就像一台小機器，你把資料放進去，它就會幫你完成工作。例如輸入 5，函數可以幫你算出平方 25。
- 座標就像地圖上的地址，告訴我們現在在哪裡。
- 位移則像走路，你原本站在某個位置，再往左走一步，就會得到新的位置。

如果要知道附近有哪些格子，我們就可以利用兩層迴圈，把周圍所有可能的位置列出來。
但要記得排除自己所在的中心位置，因為自己不是自己的鄰居。
1. Function 是可以重複使用的小工具。
2. 座標代表位置，Offset 代表移動量。
3. 二維鄰居有八個方向，不包含自己。
