# 書籤

書籤用於將資訊內容做大方向的分類，並可快速的在分類間切換。

> 

以下有幾個是在使用書籤要注意的事項：
* 僅供大方向  
書籤只能用於大方向的分類。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQscExOcHhfYUdNZlE/components_tabs_usage_example1.png" style="max-width:50%"/>

* 類別分明  
書籤的內容必須要只屬於單一主題，且避免類別間需要進行比較。

* 左右滑動  
不要在顯示分類內容的畫面中，使用需要左右滑動的物件，因為滑動在此畫面定義為切換類別。

* 單行  
書籤應以單行呈現。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsTTdvazhjTHlsWjg/components_tabs_usage_example5.png" style="max-width:50%"/>

* 單層  
書籤的深度只有一層，不含有子書籤。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsVmowR3NUVWoxVWs/components_tabs_usage_example3.png" style="max-width:50%"/>

* 風格單一  
使用全文字或是全圖示來代表每一個書籤。

* 標題行數  
最多兩行，在第二行進行截短。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3WFR6bnJvaG9wclk/components_tabs_usage_content1.png" style="max-width:50%"/>

## 類型
* 固定式  

用於書籤量比較少的情況，書籤會直接攤平在畫面上，協助使用者快速切換。  
<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsNHMyNDg1YWtVcHM/components_tabs_typesoftabs_mobile1.png" style="max-width:50%"/>
> <p style="font-size: 12px">在畫面中左右滑動切換</p>

* 滾動式  

用於書籤量較多的情況，且使用者不用在意書籤之間的關係。
<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src=http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsY1JuWnJGSHpiQkE/components-tabs-typesoftabs_scrollable_tabs_01_xhdpi_003.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsY1JuWnJGSHpiQkE/components-tabs-typesoftabs_scrollable_tabs_01_xhdpi_003.mp4" type="video/mp4">
</video>

## 規範
> <p style="font-size: 12px">書籤<br>高：48 dp（圖或文字），72 dp（圖文）</p>
> <p style="font-size: 12px">文字<br>字型：Roboto Medium<br>字體：14 sp（單行），12 sp（雙行）<br>左右間距：至少 12 dp<br>上間距：18 dp（單行），12 dp（雙行）<br>下間距：20 dp（單行），12 dp（雙行）<br>顏色：白或[強調色](../style/color.html#強調色)（選取），白（未選取）<br>不透明度：100 %（選取），70 %（未選取）<br>

> <p style="font-size: 12px">指示符<br>高：2 dp<br>顏色：白或[強調色](../style/color.html#強調色)

* 固定式

> <p style="font-size: 12px">書籤<br>預設寬：螢幕寬 / 書籤量
<br>最大寬：264 dp<br>最小寬：72（小螢幕），160 dp（大螢幕）<br>高：48 dp（圖或文字），72 dp（圖文）</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsR0pYZkJlYUUzZ3c/components_tabs_usage_specs1.png" style="max-width:50%"/>
> <p style="font-size: 12px">純文字，規範如上述</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsS1lGVXlPdXVzRFk/components_tabs_usage_specs9.png" style="max-width:50%"/>
> <p style="font-size: 12px">圖示<br>同[系統圖示](../style/icon.html#系統圖示)<br>上下間距：12 dp

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQscktCWWFUUld2U1E/components_tabs_usage_specs7.png" style="max-width:50%"/>
> <p style="font-size: 12px">圖示<br>同[系統圖示](../style/icon.html#系統圖示)<br>上間距：14 dp<br>下間距：10 dp
> <p style="font-size: 12px">文字<br>下間距：16 dp

* 滾動式

> <p style="font-size: 12px">書籤<br>預設寬：根據內容決定
<br>最大寬：264 dp 或螢幕寬減 56 dp<br>最小寬：72（小螢幕），160 dp（大螢幕）<br>高：48 dp（圖或文字），72 dp（圖文）</p>
<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsQ2l2R1lSU0hzZkE/components_tabs_usage_specs11.png" style="max-width:50%"/>
> <p style="font-size: 12px">起始點：72 dp（與標頭相同），其餘和固定式相同</p>
