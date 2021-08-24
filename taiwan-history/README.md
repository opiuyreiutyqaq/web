# Taiwan history

* project: 台灣發展史
* what I learned in the project:
    1. 簡易操作: 包含使用 icon(加入書籤列也會顯示), 引用 google font, 嵌入 google map
    2. 知道一些 CSS default styling
    3. [google chart](https://developers.google.com/chart/interactive/docs/gallery/linechart)
    4. 了解 box-sizing 
    5. nav bar: 此次主要練習目標, 並使用兩種不同的 nav bar 練習

## nav bar

1. 將 padding 設定在 ```li```: 僅有文字為 anchor tag
2. 將 padding 設定在 ```a```: 不只文字, 連外面框框處也會是 anchor tag
    * 問題點: inline element 的上下 padding 即使設定了也不會有效用
    * sol: li 設定為 flex container, a 為 flex item

## RWD

未進行 RWD 優化的檔案位於 noRWD folder

1. 排版: 右半邊圖表在螢幕縮小時可以變成位於左半邊的下面
    * 利用 flex 設定 flex wrap 與 basic, 當 basic 不滿足時會自動換行
2. nav bar 縮小時可以應對
    * media query