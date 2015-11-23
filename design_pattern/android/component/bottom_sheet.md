# 下表
下表依照用法有分成兩種：

> [固定式](#整合式)  
> [模組式](#模組式)  

## 固定式

用於呈現更深入的內容，與主頁面整合而不用另外開啟頁面，不使用時仍會存在於畫面中不會自動消失。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dDZKN1lHNG1TekU/components_bottomsheets_usage1.png"
style="max-width:50%"/>
> <p style="font-size: 12px">固定式的下表將在地圖操作時持續顯示詳細資訊</p>

## 模組式  
通常為選單或是對話框的替代方案，在表啟動時會從畫面下方滑入，畫面其他部分將蓋上一層灰，來提高下表的辨識度。使用者在使用完畢後關閉，讓被覆蓋在下方的內容可以再度被使用。

主要功能有以下三個：

* 以列表或網格的形式呈現按鈕選單或對話框  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3NWNQcUo1TnhhaWs/components_bottomsheets_modal1.png"
style="max-width:50%"/>
> <p style="font-size: 12px">列表</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3UzA3RDctV2k0YUk/components_bottomsheets_modal2.png"
style="max-width:50%"/>
> <p style="font-size: 12px">網格</p>

* 呈現一個上下文選單

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Zm9IR1dxb0E5Ync/components_bottomsheets_modal15.png"
style="max-width:100%"/>
> <p style="font-size: 12px">從選單中跳出一個二級選單</p>

* 呈現詳細內容

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3bmFYUkhqVXJpY3c/components_bottomsheets_modal7.png"
style="max-width:50%"/>
> <p style="font-size: 12px">同於固定式，模組式一樣可以拿來呈現由其他應用而來的內容</p>

模組式選單可以放置深層連結，來與其他應用交互作用，主要用途可分以下兩種：

* 讓使用者可以遊覽其他應用的更深層資訊
* 回到原點

深層鏈結不可以退到比起始點還要上一層的頁面，只有停在起始點，或是進入下一層時才可以退回。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3b1BpT0dRd0tFaUE/components_bottomsheets_modal_do.png"
style="max-width:50%"/>
> <p style="font-size: 12px">在深層連結的起點，不可退回上一層</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3UTB0bG8tYWxVRG8/components_bottomsheets_modal_dont.png"
style="max-width:50%"/>
> <p style="font-size: 12px">進入下一層，可退回</p>

如有必須要退至上一層頁面，則再開啟一起始點是上一層的深層連結。

## 操作方式