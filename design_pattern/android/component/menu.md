# 選單

為一個暫時性的物件，由其他物件觸發產生，並擁有至少兩個選項。

> [組成](#組成)
> [操作](#操作)
> [規範](#規範)
> [簡易式選單](#簡易式選單)

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

## 規範
選單應永遠存在整個應用的上層，且文字部分應簡短。

不論是靜態或動態的選單，較常使用的功能應該擺在最上面。

> <p style="font-size: 12px">選項<br>上間距：8 dp<br>寬：倍數 * 同應用欄高，倍數可以是1.5，2，3，6，7
> <p style="font-size: 12px">文字<br>字體：16 sp<br>上下間距：16 dp</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7bEZ2SjJVb195VmM/components_menus_specs1.png)
> <p style="font-size: 12px">選項高：48 dp</p>

## 簡易式選單
