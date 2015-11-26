# 網格列表

網格列表是一般列表的替代方案，通常用於以圖像為主的資訊，因為此種列表可以給圖像提供更好的辨識度。

> [組成](#組成)  
> [操作](#操作)  
> [規範](#規範)  

## 組成
<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7VGhsOE5idWlJWXM/components_grids_usage3.png" style="max-width:50%"/>
> <p style="font-size: 12px">網格列表由框和方塊組成</p>

方塊順序可依照方塊內容做排序，例如圖片大小或文字。排序的方向為從左至右，由上而下。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7YTU2ekJPMU80MVU/components_grids_usage1.png" style="max-width:50%"/>
> <p style="font-size: 12px">瀏覽和組成方向為從左到右成反S路線</p>

如果每個方塊內需要含有更多的資訊，來提高每個方塊的獨立性，建議使用[列表](#列表)或[卡片](card.html)呈現。

方塊皆由一個主要內容和一個次要內容組成，主要內容功能是區別方塊，通常為圖片；次要內容則可能是一個操作按鈕或是文字。

方塊應以一預設的主要內容來避免沒有來源的情形。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7YzdVdmpZT3FRX1E/components_grids_content1.png" style="max-width:50%"/>
> <p style="font-size: 12px">遊覽和組成方向為從左到右成反S路線</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7MHktdTZCcWZQcjA/components_grids_content2.png" style="max-width:50%"/>
> <p style="font-size: 12px">操作按鈕放置在各角落，文字層在靠上或下</p>

## 操作
* 點擊  
不能顯示選單，而可以開啟一個新的畫面。

* 滾動  
網格列表滾動方向一般為直向，唯一可以使用橫向的是單行的圖片列表。在網格初次顯示時，最後一行應該以半格呈現，來提示滾動的方向。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7ZVpFMDhCbXlXaEk/components_grids_behavior1.png" style="max-width:50%"/>
> <p style="font-size: 12px">直向</p>

* 調整  
不建議使用拖拉方式手動排序。調整大小時，方塊會自動重新排序並填滿盡量空白。

## 規範

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzM3JBazdXUTg2Nmc/components_grids_specs1.png)
> <p style="font-size: 12px">中間分隔線寬：1 dp 或 4 dp<br>欄位高：48 dp（單行文字），68 dp（雙行文字）<br>文字大小：16 sp（單行），16sp/12sp（雙行），14sp/14sp（雙行）</p>

當方塊大小容不下所需要的字串內容時，如不調整大小，則應將文字截短。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzV1lsNXRSX0ROaTg/components_grids_specs22.png)
> <p style="font-size: 12px">內容<br>上下左間距：16 dp<br>右間距：16 dp（一般），8 dp（圖左文右）<br></p>
<p style="font-size: 12px">文字<br>字體：16 sp（單行），16sp/12sp（雙行），14sp/14sp（雙行）<br>行間空白：10 dp</p>
<p style="font-size: 12px">圖示同[系統圖示](../style/icon.html#系統圖示)

* 單行文字  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsZXRKSnJtRzRYU1E/components_grids_specs7.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsYjZqOWJGa25LVjQ/components_grids_specs12.png" style="max-width:50%"/>

* 雙行文字  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQscU9haHV6LU9SWnM/components_grids_specs15.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsd0RjRWd1bW9WY0E/components_grids_specs21.png" style="max-width:50%"/>

* 圖片  
方塊可同時佔用多個框的範圍

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsYW0xRlY4U3dOMUU/components_grids_specs4.png" style="max-width:50%"/>