# 選單

為一個暫時性的物件，由其他物件觸發產生，並擁有至少兩個選項。

> [組成](#組成)  
> [操作](#操作)  
> [簡易式選單](#簡易式選單)  
> [下拉式選單](#下拉式選單)  
> [規範](#規範)

有些情況下可以擁有一個選項，例如選取字串後的選單，則只有複製功能。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzdmJrQUk3aXd0RTg/components_menus_usage2.png" style="max-width:50%"/>

選單內的選項應該是一般的操作按鈕，而不是畫面的主要操作或是具有導航功能。

選單內的內容會依照當前畫面而有所不同，因此要將無關的按鈕移除。

有時候雖然有關聯，但因為對象的狀態不同，而可能有些選項會停止使用。運用這種方法也可以提示使用者目前在哪個使用狀態。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bmZ1ajBVaXhsNTQ/components_menus_items2.png" style="max-width:50%"/>
> <p style="font-size:12px">使用者沒有任何操作，所以“Redo”呈現灰色</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Q05OWk5YLUh0NGc/components_menus_usage6.png)
> <p style="font-size: 12px">如果選項過多，則會自動變成一個可滾動的元件</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3VGxlSGNVWmNJX3c/components_menus_behavior2.png)
> <p style="font-size: 12px">下拉式選單在開啟時應以目前選到的選項，正好蓋在啟動的物件上</p>

## 組成
選項由文字、圖片或[控制器](control.html)搭配組成。

## 操作
選單可以透過點擊外部，或是重複點擊開啟選單的按鈕。

通常選單會在選擇一個選項後關閉，除非這選單是可以重複選擇多個選項。

## 簡易式選單
以列表方式呈現，開關的方式和一般的選單相同，主要提供針對列表中單一方塊的操作。

不同於[簡易式對話框](dialog.html#簡易式對話框)，簡易式選單的選項較不會影響畫面內容。

簡意式選單有在開啟時對其當前選項和方塊的特性。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQscEN4TlItQ1R4d3c/components_dialogs_simplemenus2.png)
> <p style="font-size: 12px">選單向下偏移來對齊</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsbXpoZkNIcXgxc3M/components_dialogs_simplemenus3.png)
> <p style="font-size: 12px">選單向上偏移來對齊</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsRmtOT0hySXRMYjg/components_dialogs_simplemenus4.png)
> <p style="font-size: 12px">選單向下會超過邊界，以後續的選項來對齊</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsM1JlMU1GQlVCajg/components_dialogs_simplemenus10.png" style="max-width:50%"/>
> <p style="font-size: 12px">選項內容超過單行，使用[簡易式對話框](dialog.html#簡易式選單)代替

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsM3lfVmVsWk9KRUE/components_dialogs_simplemenus12.png" style="max-width:50%"/>
> <p style="font-size: 12px">簡易式選單永遠會小於螢幕寬高，來預留可點擊的範圍來關閉選單</p>

## 下拉式選單
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3RklUaGVRbl9tMDg/components_buttons_dropdown2.png)
> <p style="font-size: 12px">一般<br>不會呈現狀態的變化項，打開為一般選單</p>
> <p style="font-size: 12px">分段式<br>會依照目前狀態改變高度，打開為一般選單</p>
> <p style="font-size: 12px">分段式編輯<br>會依照目前狀態改變高度，打開為一般選單，同時也可以編輯當前選項內容</p>

## 規範
選單應永遠存在整個應用的上層，且文字部分應簡短。

不論是靜態或動態的選單，較常使用的功能應該擺在最上面。

> <p style="font-size: 12px">選項<br>上間距：8 dp<br>寬：倍數 * 56 dp（預設）或應用欄高，倍數可以是1.5，2，3，6，7
> <p style="font-size: 12px">文字<br>字體：16 sp<br>上下間距：16 dp<br></p>

* 一般  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bEZ2SjJVb195VmM/components_menus_specs1.png)
> <p style="font-size: 12px">選項高：48 dp</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B-Ef4kCjUzkPSmluWU5MSExRWms/components_dialogs_simplemenus9.png" style="max-width:50%"/>
> <p style="font-size: 12px">選單左右間距：16 dp</p>

* 下拉式  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3U2VCaGE1YmFtQ1k/components_buttons_dropdown3.png)
> <p style="font-size: 12px"></p>