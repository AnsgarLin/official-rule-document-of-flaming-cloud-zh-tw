# 按鈕

按鈕有分以下三種類型：    

> [懸浮式按鈕](#懸浮式按鈕)  
> [抬升式按鈕](#抬升式按鈕)  
> [平面化按鈕](#平面化按鈕)  

依照權重排列如下圖：

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7RHFUU2dFdmMtcm8/components_buttons_usage_main.png)
> <p style="font-size: 12px">權重由上至下排序，越上層權重越高</p>

在選擇將按鈕放在哪個層級時，必須要考慮以下三個因素：
* 功能性  
按鈕是否重要到必須懸浮在應用上層，使其在操作過程中不會消失
* 圖層  
依照畫面的圖層數量，決定是否需要將按鈕拉升一層，使其容易辨識
* 限制  
任何一個畫面應盡量以一種類型為主，除非有非用不可的原因

## 懸浮式按鈕
懸浮式按鈕為權重最高的按鈕，通常使用為需要常駐的按鈕，其代表的功能為當前畫面的主要功能，且無法由其他的當前畫面的物件代表，所以一個畫面最多只有一個。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7S2NiZlNhcDUxSTA/patterns_actions_fab_content2.png" style="max-width:50%"/>
> <p style="font-size: 12px">此畫面主要用途為新增檔案，任何其他物件都不具有新增功能</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7WHhJcEFEVDdjM0k/patterns_actions_fab_content1.png" style="max-width:50%"/>
> <p style="font-size: 12px">此畫面主要用途為點擊圖片，所以不需要懸浮式按鈕</p>

### 動畫
跟懸浮式按鈕本身有關的動畫有分以下三種：

* 轉場

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsWm9PdVplYzZvNTg/components-buttons-fab-behavior_03_xhdpi_001.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsWm9PdVplYzZvNTg/components-buttons-fab-behavior_03_xhdpi_001.mp4" type="video/mp4">
</video>

> <p style="font-size:  12px">畫面轉變時，如所代表的功能不同，則需要一個動畫提示；如果相同，則移動到新的位置即可</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsMGF1M0lwX2NEOHc/components-buttons-fab-behavior_05_xhdpi_009.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsMGF1M0lwX2NEOHc/components-buttons-fab-behavior_05_xhdpi_009.mp4" type="video/mp4">
</video>

> <br><p style="font-size:  12px">按鈕應該獨立於畫面的轉場動畫外</p>

* 選單

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-ajMzVHp3VzJ4UkU/components-buttons-fab-transition_toolbar_02.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-ajMzVHp3VzJ4UkU/components-buttons-fab-transition_toolbar_02.mp4" type="video/mp4">
</video>

> <p style="font-size:  12px">按鈕可以轉變成一個工具列</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-MnVVYmJTcTBoSGs/components-buttons-fab-transition_scrolltoolbar_02.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-MnVVYmJTcTBoSGs/components-buttons-fab-transition_scrolltoolbar_02.mp4" type="video/mp4">
</video>

> <p style="font-size:  12px">滾動可以還原按鈕</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsZHRMSzRFTXhoMnM/patterns_actions_fab_actions10.png" style="max-width:50%"/>
> <p style="font-size: 12px">由懸浮式按鈕轉變成的工具列，必須要放類型相關的功能</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3TmpnUHVKRV9DU0E/components-buttons-fab-transition_speeddial_02.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3TmpnUHVKRV9DU0E/components-buttons-fab-transition_speeddial_02.mp4" type="video/mp4">
</video>

> <p style="font-size: 12px">懸浮式按鈕也可轉變成數個小按鈕，且懸浮式按鈕將留在畫面中，並轉為關閉圖示</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6GnvA6rl3tYWEZGZFBuc1RxMEk/components_fab_flyouts_do.png" style="max-width:50%"/>
> <p style="font-size: 12px">小按鈕的數量至少2個，至多6個</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B1PhAWhtrRTrUy1EQlFoWmJZSE0/patterns_actions_fab_actions6.png" style="max-width:50%"/>
> <p style="font-size: 12px">相同的，由懸浮式按鈕轉變而來的小按鈕，也要具備與內容直接相關的功能</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-TjBicTdvQjg4M1E/components-buttons-fab-transition_card_02.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-TjBicTdvQjg4M1E/components-buttons-fab-transition_card_02.mp4" type="video/mp4">
</video>

> <p style="font-size: 12px">如需要多餘6個以上的功能，或是要顯示圖文選項，則可將懸浮式按鈕轉變成選單列</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B1PhAWhtrRTrQWdBMWF1aXpJb1U/patterns_actions_fab_actions2.png" style="max-width:50%"/>
> <p style="font-size: 12px">選單列將包含一個工具列，即可處理多功能的情況</p>

* 形變

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-c0UwMFAyQU5Jb1U/components-buttons-fab-transition_morph_02.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-c0UwMFAyQU5Jb1U/components-buttons-fab-transition_morph_02.mp4" type="video/mp4">
</video>

> <p style="font-size: 12px">懸浮式按鈕可以轉變成一個物件，並插入當前畫面</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-RWVHZjYybnlDeUE/components-buttons-fab-transition_fullscreen_02.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-RWVHZjYybnlDeUE/components-buttons-fab-transition_fullscreen_02.mp4" type="video/mp4">
</video>

> <p style="font-size: 12px">懸浮式按鈕可以轉變成一個全新的畫面，也因此並不能中斷動畫</p>

### 規範
按鈕必須為圓形且平面化：

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B1PhAWhtrRTrOHBsN0xtTFJ5aEE/patterns_actions_fab_qualities5.png" style="max-width:50%"/>
> <p style="font-size: 12px">圓形且平面</p>

中央圖示必須要是正面意義：
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B1PhAWhtrRTrWktOTnVaYk1TaU0/patterns_actions_fab_qualities1.png)
> <p style="font-size: 12px">新增、最愛、探索和導航等</p>

依照情境有分成兩種大小：

* 一般  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7dkNVa080Ykd0ejg/patterns_actions_fab3.png" style="max-width:50%"/>
> <p style="font-size: 12px">直徑：56 dp<br>圖示：24 dp，同[系統圖示](../style/icon.html#系統圖示)

* 縮小  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7dkNVa080Ykd0ejg/patterns_actions_fab3.png" style="max-width:50%"/>
> <p style="font-size: 12px">直徑：40 dp<br>圖示：同一般

## 抬升式按鈕
抬升式按鈕為權重次高的按鈕，通常使用在畫面之中：

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsMF8xdDNDNUc0Zk0/components_buttons_main7.png" style="max-width:50%"/>
> <p style="font-size: 12px">抬升效果可比平面化按鈕更凸出於畫面之中

### 狀態
依照情境可分以下兩種：

* 容器底色為亮色系  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7WlduMk1kbTRzQWc/components_buttons_main15.png" style="max-width:50%"/>
> <p style="font-size:  12px">停用<br>文字顏色：黑<br>不透明度：26%</p><p style="font-size:  12px">按鈕底色：黑<br>不透明度：12%
</p>

* 容器底色為暗色系  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7UTh2dExpSlRVWVU/components_buttons_main16.png" style="max-width:50%"/>
> <p style="font-size:  12px">碰觸<br>按鈕底色：600</p><p style="font-size: 12px">按壓<br>按鈕底色：700</p><p style="font-size: 12px">停用<br>文字顏色：白<br>不透明度：30%
</p><p style="font-size: 12px">按鈕底色：白<br>不透明度：12%
</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFRmZDbzdkSEp0ZEk/components-buttons-raisedbuttons.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFRmZDbzdkSEp0ZEk/components-buttons-raisedbuttons.mp4" type="video/mp4">
</video>

> <p style="font-size:  12px">運用實例</p>

### 設計規範
<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsU1A0aDJMMGhQRjQ/components_buttons_keyline1.png" style="max-width:50%"/>
> <p style="font-size: 12px">文字：全部大寫<br>
文字顏色：白<br>按鈕底色：500<br>按鈕觸控範圍高：48 dp<br>按鈕高：36 dp<br>按鈕寬：至少 88 dp<br>左右內間距：8 dp<br>左右外間距：8 dp
</p>

## 平面化按鈕
平面化按鈕為權重最低的按鈕，通常使用在三種地方：

* 對話框  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsWVJfOVpiVHYtZ00/components_buttons_main9.png" style="max-width:50%"/>
> <p style="font-size: 12px">詳細請查看[對話框]()

* 置底按鈕  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7Ukt1TFRVUlgxY1k/components_buttons_keyline2.png" style="max-width:50%"/>
> <p style="font-size: 12px">如果應用需要一個長駐的按鈕，除了使用懸浮按鈕，也可以使用置底按鈕</p>

* 卡片  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsTDEwRlFpUmZtVm8/components_buttons_main11.png" style="max-width:50%"/>
> <p style="font-size: 12px">詳細請查看[卡片]()

### 狀態
依照情境可分以下兩種：

* 容器底色為亮色系  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7SnA4Umw3S0pfNWs/components_buttons_main13.png" style="max-width:50%"/>
> <p style="font-size:  12px">碰觸<br>按鈕底色：#999999<br>不透明度：20%</p><p style="font-size: 12px">按壓<br>按鈕底色：#999999<br>不透明度：40%</p><p style="font-size: 12px">停用<br>文字顏色：黑<br>不透明度：26%
</p>

* 容器底色為暗色系  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bEFqalRSeUJkbEU/components_buttons_main14.png" style="max-width:50%"/>
> <p style="font-size:  12px">碰觸<br>按鈕底色：#CCCCCC<br>不透明度：15%</p><p style="font-size: 12px">按壓<br>按鈕底色：#CCCCCC<br>不透明度：25%</p><p style="font-size: 12px">停用<br>文字顏色：白<br>不透明度：30%
</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFSTNhRndpWXBwRDA/components-buttons-flatbuttons.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFSTNhRndpWXBwRDA/components-buttons-flatbuttons.mp4" type="video/mp4">
</video>

> <p style="font-size:  12px">運用實例</p>

### 設計規範
<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsU1A0aDJMMGhQRjQ/components_buttons_keyline1.png" style="max-width:50%"/>
> <p style="font-size: 12px">與抬升式按鈕大致相同，除了以下項目：<br>
文字顏色：主題色，或與內容文字不同的顏色<br>按鈕底色：同容器底色<br>按鈕寬：至少 88 dp（一般），64 dp （對話框）</p>