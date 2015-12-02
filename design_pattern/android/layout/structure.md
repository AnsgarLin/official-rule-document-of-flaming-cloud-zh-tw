# 結構
Google官方對於物件的擺放有制定一套規範，並且依照平台又細分成手機、平板和桌面。由於本文件是以手機為主，因此以下篇幅僅限於手機部份，如需其他部分的詳細說明，請查看官網的[指標及關鍵線](http://www.google.com/design/spec/layout/metrics-keylines.html)和[結構](http://www.google.com/design/spec/layout/structure.html)。

> [Google 官方結構模板](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B0J8hsRkk91LSGI2MmtqdFNEMG8/Layout_Mobile_Whiteframe.ai)

## 基本單元
所有物件都會沿著8dp為基本單位的參考線來做區隔，而工具列則是以4dp為基本單位。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsc0tpMGdyWDh2OUE/layout_metrics_baseline3.png" style="max-width:50%"/>

## 區塊佈局
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7T0hfM01sSmRyTG8/layout_structure_regions_mobile.png)
> <p style="font-size: 12px">手機版各區塊佈局總覽</p>

### 系統列（System bar）
位於畫面最上方，用於顯示提示、時間和電力等有關系統的目前狀況。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsLUFLM2xkRElVM2s/layout_structure_system_status1.png" style="max-width:50%"/>
> <p style="font-size: 12px">高：24dp</p>

底色預設為比主題色稍重的實體色，詳細可參考[顏色](../layout/color.html)，也可以是半透明的黑或白，如下二圖：

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsLWE2REc4RnVuTWc/layout_structure_system_color2.png" style="max-width:50%"/>
> <p style="font-size: 12px">顏色：黑<br>不透明度：20%</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B8v7jImPsDi-RmR0RU9hc1MzWGc/layout_structure_system_color6.png" style="max-width:50%"/>
> <p style="font-size: 12px">顏色：白<br>不透明度：70%</p>

### 導覽列（Android navigation bar）
可能為實體按鍵，或為虛擬按鍵，並固定於畫面下方，含有退出、回到桌面和應用概觀。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7RWpaeTZqTmlYOHc/layout_structure_system_android1.png" style="max-width:50%"/>
> <p style="font-size: 12px">高：48dp（虛擬按鍵）</p>

底色預設為黑色，也可以是半透明的黑或全透明，如下二圖：

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bl93YnVqdWE3NGM/layout_structure_system_android4.png" style="max-width:50%"/>
> <p style="font-size: 12px">顏色：黑<br>不透明度：不定</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7S2tTVjBjcUNEM00/layout_structure_system_android6.png" style="max-width:50%"/>
> <p style="font-size: 12px">不透明度：100%</p>

### 工具列（Toolbar）
工具列可以泛指任何在畫面或是物件上方，擺放按鈕的區塊。在這只討論屬於應用主程式的工具列，也可以稱為應用列。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7RTFrbmpoWjRrY00/layout_structure_appbar_structure1.png)
> <p style="font-size: 12px">左側：Nav icon、Title 和 Filter icon<br>右側：Action icons、Menuicon<br>各部分在應用欄的擺放位置是固定的。
</p>

各部分說明如下：
* 導覽圖示（Nav icon）  
可用於開啟側邊欄、退回上一頁或是退出應用。
* 標題（Title）  
顯示應用名稱、畫面標題或是篩選條件。
* 篩選器圖示（Filter icon）  
在標題為篩選條件時顯示，可開啟一所有其他篩選條件的列表。
* 功能圖示（Action icon）  
用於顯示與應用或當前畫面相關的功能。
* 選單圖示（Menu icon）  
在功能圖示過多，或其重要性不高時，可以略縮成單一圖示，必要時再以列表開啟其他選項。

一般來說，所有應用欄的圖示顏色和標題相同，但也可以用不同的顏色提高辨識度。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQselRDRFlzNkI0SFE/layout_structure_appbar_structure7.png" style="max-width:50%"/>

工具列其他物件的階層排列有以下四種：

* 上層

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B9PCOJnbdRP6NVBZNXNqTi1EekU/layout_principles_papercraft_toolbars4.png)
> <p style="font-size: 12px">工具列永遠高於物件</p>

* 同層  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B9PCOJnbdRP6NVBZNXNqTi1EekU/layout_principles_papercraft_toolbars4.png)
> <p style="font-size: 12px">工具列與物件並列，用於物件是由工具列產生的時候</p>

* 下層  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B9PCOJnbdRP6NVBZNXNqTi1EekU/layout_principles_papercraft_toolbars4.png)
> <p style="font-size: 12px">工具列永遠低於物件</p>

* 同層至上層  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B9PCOJnbdRP6NVBZNXNqTi1EekU/layout_principles_papercraft_toolbars4.png)
> <p style="font-size: 12px">工具列等於或高於物件，通常用於物件是由工具列產生時，在物件滾動後移至上層</p>

開啟選單時的圖層時，選單不可以將工具列上的功能隔開，因此工具列會進行壓縮，並將圖示集中到左或右邊。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B9PCOJnbdRP6elVJaFhzQ3lKems/layout_principles_papercraft_toolbars2.png" style="max-width:50%"/>

佈局數值可分以下三個情境：

> <p style="font-size: 12px">文字<br>字體：20sp（一般），24sp（延伸）</p>
> <p style="font-size: 12px">左右間距：16dp<br>圖示上下間距：16dp<br>標題左間距：72dp<br>標題上間距：20dp（一般），82sp（延伸）<br>標題下間距：16dp（一般），26sp（延伸）</p>

* 預設  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsLUFJUnFlRHVhUVU/layout_structure_appbar_metrics1.png" style="max-width:50%"/>
> <p style="font-size: 12px">高：56dp（直）、48dp（橫）</p>

* 延伸  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsSDBhX3BwSURRc1U/layout_structure_appbar_metrics3.png" style="max-width:50%"/>
> <p style="font-size: 12px">延伸應用欄時，高度為預設的高加上延伸的高度</p>

* 輸入  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsTW1zb2x5WWg5cDA/layout_structure_appbar_metrics5.png" style="max-width:50%"/>
> <p style="font-size: 12px">主要輸入欄位：80dp（直）、72dp（橫）<br>輸入欄位兼具：8dp（直）、0dp（橫）<br>次要輸入欄位：72dp（直）、64dp（橫）<br>次要輸入欄位下空白：16dp（直）、8dp（橫）</p>

### 內文區塊（Content area）
各個區塊的高度必須要和螢幕寬達成一定比例，官方建議的比例表如下圖：

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7ZjBCVzdPOENpT28/layout_metrics_ratiokeylines1.png" style="max-width:50%"/>
> <p style="font-size: 12px">如寬為 360dp，則3:2對應的高為 240dp</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsS1RKNFQtdy1sYkU/layout_metrics_ratiokeylines2.png" style="max-width:50%"/>
> <p style="font-size: 12px">套用實例</p>

## 滾動模式

內文區塊在滾動時，會引發畫面結構的轉變，主要分有以下幾種模式：

* 狀態列和工具列  
狀態列可決定是否和工具列一起向上推移或是固定在畫面頂端。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsR1lZQUxtWFRFMEU/patterns-scrolling-techniques_standard_appbar_xhdpi_004.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsR1lZQUxtWFRFMEU/patterns-scrolling-techniques_standard_appbar_xhdpi_004.mp4" type="video/mp4">
</video>
> <p style="font-size: 12px">狀態列固定在畫面頂端</p>

* 狀態列、工具列和延伸空間
狀態列固定在畫面頂端，工具列可決定是否與延伸空間一起上移。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsRTM1M1lCWWZiN2c/patterns-scrolling-techniques-flexible_space_xhdpi_003.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsRTM1M1lCWWZiN2c/patterns-scrolling-techniques-flexible_space_xhdpi_003.mp4" type="video/mp4">
</video>
> <p style="font-size: 12px">工具列與狀態列一起固定在畫面頂端</p>

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQscXNQY3dNdVlYeTQ/patterns-scrolling-techniques_flex_space_image_xhdpi_003.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQscXNQY3dNdVlYeTQ/patterns-scrolling-techniques_flex_space_image_xhdpi_003.mp4" type="video/mp4">
</video>
> <p style="font-size: 12px">工具列與延伸空間一起上移，且圖片漸變成主題色</p>

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsRVpzZG0zZGVNSXM/patterns-scrolling-techniques_flex_space_overlap_xhdpi_003.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsRVpzZG0zZGVNSXM/patterns-scrolling-techniques_flex_space_overlap_xhdpi_003.mp4" type="video/mp4">
</video>
> <p style="font-size: 12px">工具列和延伸空間一開始在內文底下，在上移後換到內文以上</p>

## 觸控單元
為了平衡圖示的清晰度和實用性，觸控應該至少48dp見方。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7eEVhSW1nVjBrZnM/layout_metrics_touchtarget1.png" style="max-width:50%"/>
> <p style="font-size: 12px">即使圖示大小不同，其觸控範圍相同</p>


