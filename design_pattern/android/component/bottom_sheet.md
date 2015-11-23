# 下表
下表依照用法有分成兩種：

> [固定式](#整合式)  
> [模組式](#模組式)  

## 固定式

用於呈現更深入的內容，與主頁面整合而不用另外開啟頁面，不使用時仍會存在於畫面中不會自動消失。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dDZKN1lHNG1TekU/components_bottomsheets_usage1.png" style="max-width:50%"/>
> <p style="font-size: 12px">固定式的下表將在地圖操作時持續顯示詳細資訊</p>

## 模組式  
通常為選單或是對話框的替代方案，在表啟動時會從畫面下方滑入，畫面其他部分將蓋上一層灰，來提高下表的辨識度。使用者在使用完畢後關閉，讓被覆蓋在下方的內容可以再度被使用。

主要功能有以下三個：

* 以列表或網格的形式呈現按鈕選單或對話框  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3NWNQcUo1TnhhaWs/components_bottomsheets_modal1.png" style="max-width:50%"/>
> <p style="font-size: 12px">列表</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3UzA3RDctV2k0YUk/components_bottomsheets_modal2.png" style="max-width:50%"/>
> <p style="font-size: 12px">網格</p>

* 呈現一個上下文選單

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Zm9IR1dxb0E5Ync/components_bottomsheets_modal15.png" style="max-width:100%"/>
> <p style="font-size: 12px">從選單中跳出一個二級選單</p>

* 呈現詳細內容

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3bmFYUkhqVXJpY3c/components_bottomsheets_modal7.png" style="max-width:50%"/>
> <p style="font-size: 12px">同於固定式，模組式一樣可以拿來呈現由其他應用而來的內容</p>

### 深層連結
模組式選單可以放置深層連結，來與其他應用交互作用。

深層鏈結不可以退到比起始點還要上一層的頁面，只有停在起始點，或是進入下一層時才可以退回。如有必須要退至上一層頁面，則再開啟一起始點是上一層的深層連結。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3b1BpT0dRd0tFaUE/components_bottomsheets_modal_do.png" style="max-width:50%"/>
> <p style="font-size: 12px">在深層連結的起點，不可退回上一層，只可關閉</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3UTB0bG8tYWxVRG8/components_bottomsheets_modal_dont.png" style="max-width:50%"/>
> <p style="font-size: 12px">進入下一層，可退回</p>

### 操作方式
模組式開啟後可用以下三種方式關閉：
* 向下拖移  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3a3Z2UGZJMkRWamM/components_bottomsheets_behavior1.png" style="max-width:50%"/>

* 點擊列表外的範圍  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cGt6TlA0ZzNLdDg/components_bottomsheets_behavior2.png" style="max-width:50%"/>

* 點擊關閉按鍵  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cTdiQWp2TkI0NEE/components_bottomsheets_behavior3.png" style="max-width:50%"/>

### 畫面規範
模組式在開啟時，預設是依照內容數量決定高度，最高到達高寬比為16:9。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3VVJVdF9wRG5Iem8/components_bottomsheets_specs9.png" style="max-width:50%"/>
> <p style="font-size: 12px">最大高度：寬 = 16：9</p>

如選項實際高度大於起始限制的最大高度，則一樣起始為限制的最大高度，而使用者可以藉由滾動讓選單填滿畫面。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Ym9QLTlfbUR4ekk/components_bottomsheets_modal11.png" style="max-width:50%"/>
> <p style="font-size: 12px">選項多於一頁</p>

選單內容可分為三種：

* 圖文列表  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dXNVNEpIZzZQdUU/components_bottomsheets_specs1.png" style="max-width:50%"/>
> <p style="font-size: 12px">左右間距：16 dp<br>上下間距：8 dp<br>選項高：48 dp<br>選項圖示寬高：24 dp<br>選項圖示上下間距：垂直置中<br>文字與選項圖示間距：32 dp</p>

* 帶有標題的上下圖文列表  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Q3NrbGhWQXJxSGs/components_bottomsheets_specs3.png" style="max-width:50%"/>
> <p style="font-size: 12px">上列表標題高：56 dp<br>上列表的下間距：7 dp<br>上下表分隔線高：1 dp<br>其他與圖文列表相同</p>

*網格列表  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3a2JBazEtX3R2Ulk/components_bottomsheets_specs7.png" style="max-width:50%"/>
> <p style="font-size: 12px">左右間距：24 dp<br>網格列上下間距：除最底邊24 dp，其餘16 dp<br>網格圖示寬高：48 dp<br>網格圖示上下間距：垂直置中<br>網格圖示左右間距：除左右圖示靠向邊界，中間圖示平均分佈<br>文字高度：16dp<br>文字間距：中央對齊各圖示</p>