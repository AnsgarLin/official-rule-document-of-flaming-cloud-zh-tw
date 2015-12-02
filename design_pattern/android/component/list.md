# 列表

列表用於呈現一連串內容連續的資料，且可依照方塊內容做排序。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsTEYtcnczU3J5ZEU/components_lists_behavior1.png" style="max-width:50%"/>

> [方塊組成](#方塊組成)
> [操作](#操作)
> [規範](#規範)

## 方塊組成

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7TmRJenRtUVZFLUk/components_lists_usage2.png" style="max-width:50%"/>
> <p style="font-size: 12px">列表由行和方塊組成</p>

使用相同的風格，運用結構上的編排來提升每一筆資訊的辨識度，以及提示各項細節的重要程度。

一般來說，較重要的資訊會擺在左邊，最不重要的擺在右邊。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsSnBGdWd3WDhPUE0/components_lists_usage3.png" style="max-width:50%"/>
> <p style="font-size: 12px">在信箱中，寄件者的大頭像和內容比起時間還要重要</p>

相同的，能進行的操作也依照其對應的功能重要性，分成主要操作和次要操作，並由左到右編排。

在整個列表中，所有的主要操作和次要操作都是相同的。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bTlwblZleHIwU1U/components_lists_content2.png" style="max-width:50%"/>
> <p style="font-size: 12px">在信箱中，寄件者的大頭像和內容比起時間還要重要</p>

如果文字內容超過三行，使用[卡片](icon.html)代替；如果主要內容是圖片，使用[網格列表](grid_list.html)


## 操作
* 點擊  
可以開啟一個新的畫面，但某些操作如刪除、播放和選擇等，因為會立刻被執行，所以不會再跳出任何選單。

* 滾動  
列表僅供垂直滾動

* 滑動
列表中每一個選項應有一致的滑動動作

* 更新
列表下拉啟動更新。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsUkpNWUx6NFI4clE/patterns-swipetorefresh-behavior_do_xhdpi_009.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsUkpNWUx6NFI4clE/patterns-swipetorefresh-behavior_do_xhdpi_009.mp4" type="video/mp4">
</video>

> <p style="font-size:12px"> 圖示會持續顯示到讀取完成，或是使用者進入其它頁面。同時使用者依然可以滾動列表</p>

## 規範
主要操作會佔滿大部分空間，因此通常不會只是一個圖案；相反的次要操作通常以圖片表示。

避免在每個選項都放上次要操作的圖示，降低視覺上的干擾。但如星星此類[控制器](control.html)則可，因為其以開關狀態顯示有用的資訊。

* 副標  
使用色彩鮮明的副標可以協助劃分列表內容

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7eThvY2hXZ2JNdkk/components_subheaders1.png" style="max-width:50%"/>
> <p style="font-size: 12px">欄高：48 dp<br>左間距：16 dp<br>字型：Roboto Medium<br>字體：14 sp<br></p>
> <p style="font-size: 12px">文字顏色：黑或主題色<br>不透明度：54 %（非主題色），100 %（主題色）<br></p>

如果有浮動式按鈕，則因與文字對齊

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsMEtuWm42b2lSRkk/components_subheaders4.png" style="max-width:50%"/>
> <p style="font-size: 12px">左間距：72 dp</p>

* 單行

> <p style="font-size: 12px">列表上間距：8 dp（沒有標頭），0 dp（有標頭）</p>
> <p style="font-size: 12px">內容左右間距：16 dp</p>
> <p style="font-size: 12px">圖示 <br>上下間距：12 dp（系統圖示），8 dp（大頭圖） </p>
> <p style="font-size: 12px">文字<br>字體：16 dp<br>左間距：16 dp（左無圖），72 dp（左有圖）<br>上下間距：16 dp（左無圖或系統圖示），20 dp（左大頭圖）</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7Y1FsdElhSlJ1WEU/components_lists_keylines_single2.png" style="max-width:50%"/>
> <p style="font-size: 12px">欄位高：48 dp</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7eUpZcXJRODJvMXc/components_lists_keylines_single5.png" style="max-width:50%"/>
> <p style="font-size: 12px">欄位高：48 dp<br></p>

> <p style="font-size: 12px">圖示同[系統圖示](../icon.html#系統圖示)

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bzEta2VMeTQ5QTg/components_lists_keylines_single8.png" style="max-width:50%"/>
> <p style="font-size: 12px">欄位高：56 dp

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7T2pKUG0teEQycTA/components_lists_keylines_single11.png" style="max-width:50%"/>
> <p style="font-size: 12px">欄位高：56 dp</p>
> <p style="font-size: 12px">右圖示<br>左右間距：16 dp<br>其他同[系統圖示](../style/icon.html#系統圖示)

* 雙行

> <p style="font-size: 12px">列表上間距：8 dp（沒有標頭），0 dp（有標頭）</p>
> <p style="font-size: 12px">欄位高：72 dp<br>內容左右間距：16 dp</p>
> <p style="font-size: 12px">圖示 <br>直徑：24 dp（系統圖示），40 dp（大頭圖）<br>上下間距：24 dp（系統圖示），16 dp（大頭圖）</p>
> <p style="font-size: 12px">文字<br>字體：16 dp（第一行），14 sp（第二行）<br>行間空白：4 dp<br>左間距：16 dp（左無圖），72 dp（左有圖）<br>上間距：20 dp<br>下間距：16 dp</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7UkNZZk02N3BYazg/components_lists_keylines_two2.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7RTJvc2pWMnFvQTg/components_lists_keylines_two5.png" style="max-width:50%"/>
> <p style="font-size: 12px">圖示同[系統圖示](../icon.html#系統圖示)

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7Tm9ZQmFCZzlITkE/components_lists_keylines_two7.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7NkI5bzU3Y3BQQzg/components_lists_keylines_two10.png" style="max-width:50%"/>
> <p style="font-size: 12px">右圖示同[系統圖示](../icon.html#系統圖示)

* 三行

> <p style="font-size: 12px">列表上間距：8 dp（沒有標頭），0 dp（有標頭）</p>
> <p style="font-size: 12px">欄位高：88 dp<br>內容左右間距：16 dp</p>
> <p style="font-size: 12px">圖示 <br>直徑：24 dp（系統圖示），40 dp（大頭圖）<br>上間距：16 dp<br>下間距：48 dp（系統圖示），32 dp（大頭圖）</p></p>
> <p style="font-size: 12px">文字<br>字體：16 dp（第一行），14 sp（第二三行）<br>行間空白：4 dp<br>左間距：16 dp（左無圖），72 dp（左有圖）<br>上下間距：16 dp</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3N216V0Y1MXQ1TmM/components_lists_keylines_three2.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Xzd5UnFOQVdNS28/components_lists_keylines_three5.png" style="max-width:50%"/>
> <p style="font-size: 12px">圖示同[系統圖示](../icon.html#系統圖示)

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3VksyR0lhS0FqWE0/components_lists_keylines_three7.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3aVU4MlFJUjBXRms/components_lists_keylines_three10.png" style="max-width:50%"/>
> <p style="font-size: 12px">右圖示同[系統圖示](../icon.html#系統圖示)

