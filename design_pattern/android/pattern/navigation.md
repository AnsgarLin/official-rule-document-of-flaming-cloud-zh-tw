# 導覽

導覽在應用中引導使用者瀏覽不同畫面，所以應用的結構必須根據內容和目標任務進行組織。

將重點的路徑和功能放置於書籤或是側邊欄。或是將不重要的功能放置於較不顯眼的位置。

## 設計
導覽會根據應用中的內容而不同，所以為了決定適合的導覽方式，必須要定義好以下幾點：
* 目標使用者
* 基本操作

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cE9LOFJEemtORVU/inventory.png)
> <p style="font-size: 12px">基本操作應盡量詳盡</p>

接著依照以下幾個步驟進行導覽流程設計：

* 篩選權重  
決定各個操作的權重，讓導覽路徑和介面著重在較重要的功能。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3ejYzcGo1QVJWcms/prioritize.png)
> <p style="font-size: 12px">順序可以可以再依照需求做更動</p>

* 使用路徑  
決定使用者在應用中的操作路徑，並將最常被使用的路徑視為最重要的導覽路徑。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3UGRCRU1aUTJCNG8/sequence.png)

* 細項切分  
將使用路徑上的操作，切分成更細微的操作

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3NGhzcTdPZHVyNzQ/deconstruct.png)

## 層級
導覽的層級關係分為以下幾種：

* 首頁  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3SzVoODlnQXZ6MmM/patterns_navigation_hierarchy_home.png" style="max-width:50%"/>

* 母子  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3X2w3Rm1JM1lGblE/patterns_navigation_hierarchy_parent-child.png" style="max-width:50%"/>
> <p style="font-size: 12px">單向向下</p>

* 平行切換  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3SmxZMEgzeWZVdDQ/patterns_navigation_hierarchy_siblings.png" style="max-width:50%"/>
> <p style="font-size: 12px">畫面可在同層級中切換</p>

* 集合

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Z2NNQTNTb25LYjA/patterns_navigation_hierarchy_collections.png" style="max-width:50%"/>

* 連結

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dTE0LVd4SVdZekE/patterns_navigation_hierarchy_links.png" style="max-width:50%"/>

## 型態
* 嵌入式  
應用沒有過多的子畫面，且大多功能可以在主頁面完成。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3VTk0QjZOVUxFY1k/patterns_navigation_patterns_embedded1.png" style="max-width:50%"/>

* [書籤](../component/tab.html)  
用於需要長滑動切換的畫面。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3TEMxQ3BmVmFEQXc/patterns_navigation_patterns_tabs1.png" style="max-width:50%"/>

* [側邊欄](../component/drawer.html)

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Ty1Ob2FuTUMtQW8/patterns_navigation_patterns_navdrawer4.png" style="max-width:50%"/>

![](
http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3TTNvTzg5aE51M00/patterns_navigation_patterns_expanding2.png)

* 巢狀  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3X3JyV1JZQ1J6dms/patterns_navigation_patterns_nested1.png)

* 互動式  
允許使用者用 些操作來切換畫面，達到導覽的功能

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3QjdEZk5TRUt6NXc/Expanding%20-%20Overscroll%20Top.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3QjdEZk5TRUt6NXc/Expanding%20-%20Overscroll%20Top.mp4" type="video/mp4">
</video>