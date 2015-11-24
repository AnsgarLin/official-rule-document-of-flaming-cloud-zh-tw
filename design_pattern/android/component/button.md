# 按鈕

按鈕有分三種類型，依照權重排列如下圖：
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7RHFUU2dFdmMtcm8/components_buttons_usage_main.png)
> <p style="font-size: 12px">權重由上至下排序，越上層權重越高</p>

在選擇將按鈕放在哪個層級時，必須要考慮以下三個因素：
* 功能性  
按鈕是否重要到必須懸浮在應用上層，使其在操作過程中不會消失
* 圖層  
依照畫面的圖層數量，決定是否需要將按鈕拉升一層，使其容易辨識
* 限制  
任何一個畫面應盡量以一種類型為主，除非有非用不可的原因

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
> <p style="font-size:  12px">碰觸<br>按鈕底色：#999999<br>透明度：20%</p><p style="font-size: 12px">按壓<br>按鈕底色：#999999<br>透明度：40%</p><p style="font-size: 12px">停用<br>文字顏色：黑<br>透明度：26%
</p>

* 容器底色為暗色系  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bEFqalRSeUJkbEU/components_buttons_main14.png" style="max-width:50%"/>
> <p style="font-size:  12px">碰觸<br>按鈕底色：#CCCCCC<br>透明度：15%</p><p style="font-size: 12px">按壓<br>按鈕底色：#CCCCCC<br>透明度：25%</p><p style="font-size: 12px">停用<br>文字顏色：白<br>透明度：30%
</p>

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFSTNhRndpWXBwRDA/components-buttons-flatbuttons.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFSTNhRndpWXBwRDA/components-buttons-flatbuttons.mp4" type="video/mp4">
</video>

### 設計規範
<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsU1A0aDJMMGhQRjQ/components_buttons_keyline1.png" style="max-width:50%"/>
> <p style="font-size: 12px">文字：全部大寫<br>
文字顏色：主題色，或與內容文字不同的顏色<br>按鈕觸控範圍高：48 dp<br>按鈕高：36 dp<br>按鈕寬：至少 88 dp（一般），64 dp （對話框）<br>左右內間距：8 dp<br>左右外間距：8 dp<br>底色：同容器底色
</p>