# 控制器
控制器以圖示的型態存在於一個列表方塊的左邊或是右邊，用於顯示當前方塊的狀態、資訊或是操作。

控制器也可以存在方塊的底層，使用滑動的方式將其顯示。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7TWlQcWJZRE1NQ1U/components_listcontrols_usage.png)

控制器可以當作以下四種功能來使用：
* 顯示狀態

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7MEdoQjlzVjZZOVk/components_listcontrols_menu1.png)

* 主要操作  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7Vnh0b0VhSlE5ajg/components_listcontrols_checkbox1.png)
> <p style="font-size: 12px">複選框，選取操作比顯示細節重要</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7MTZ3SU1HZ1V3dVE/components_listcontrols_menu3.png)
> <p style="font-size: 12px">巢狀選單</p>

* 次要操作  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7YUQ5TEFVT3ZJQjg/components_listcontrols_checkbox2.png)
> <p style="font-size: 12px">複選框</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3ZDhGVEFDTFQya2s/components_listcontrols_switch.png)
> <p style="font-size: 12px">開關</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7X0pmWjRNZ21UUFE/components_listcontrols_reorder.png)
> <p style="font-size: 12px">排序</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3bl8zNGVqM19TNWM/components_listcontrols_expand2.png" style="max-width:50%"/>
> <p style="font-size: 12px">延展</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsVHpIeFlLM1JEXzg/components_listcontrols_leave2.png" style="max-width:50%"/>
> <p style="font-size: 12px">其他，同時提示使用者在整個應用中，滑動列表方塊代表的意義</p>

* 次要資訊  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7MTlwWk9tajlPeFE/components_listcontrols_menu2.png)
> <p style="font-size: 12px">功能說明</p>

不能將控制器圖示並排於其他圖示，而屬於次要操作的控制項應至於右邊。

## 類型
控制器依照類型分為三種，各種有不同的使用時機：
* 複選框  
用於讓使用者可以進行複選，但如果只有一個選項，建議使用開關。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cFp4WHdDaWZESmM/components_switches_check3.png)
> <p style="font-size: 12px">開<br>顏色：主題色</p>
> <p style="font-size: 12px">關<br>顏色：黑<br>透明度：54 %</p>
> <p style="font-size: 12px">停用<br>顏色：黑<br>透明度：26 %</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cy1pRXJxY2dnN28/components_switches_check4.png)
> <p style="font-size: 12px">開<br>顏色：主題色</p>
> <p style="font-size: 12px">關<br>顏色：白<br>透明度：70 %</p>
> <p style="font-size: 12px">停用<br>顏色：白<br>透明度：30 %</p>

* 單選按鈕  
用於讓使用者從一組選項中挑選一個，通常為第二層選單且選單是全部展開，如果不需要使用者可以一次看到所有選項，建議使用下拉式選單。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cEVOUmMwZ05tU00/components_switches_radio3.png)
> <p style="font-size: 12px">開<br>顏色：主題色</p>
> <p style="font-size: 12px">關<br>顏色：黑<br>透明度：54 %</p>
> <p style="font-size: 12px">停用<br>顏色：黑<br>透明度：26 %</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3aWtqNWY3NmxJeHc/components_switches_radio4.png)
> <p style="font-size: 12px">開<br>顏色：主題色</p>
> <p style="font-size: 12px">關<br>顏色：白<br>透明度：70 %</p>
> <p style="font-size: 12px">停用<br>顏色：白<br>透明度：30 %</p>

* 開關  
用於讓使用者決定某一個選項的開關狀態

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Mk55RHlTUi1YaVE/components_switches_switch3.png)
> <p style="font-size: 12px">開<br>顏色：主題色（控鈕），主題色（橫桿）<br>透明度：100 %（控鈕），50 %（橫桿）</p>
> <p style="font-size: 12px">關<br>顏色：#FAFAFA（控鈕），黑（橫桿）<br>透明度：100 %（控鈕），26 %（橫桿）</p>
> <p style="font-size: 12px">關<br>顏色：#BDBDBD（控鈕），黑（橫桿）<br>透明度：100 %（控鈕），12 %（橫桿）</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsTDJPbG5DUjJOYkk/components_switches_switch4.png)
> <p style="font-size: 12px">開<br>顏色：主題色 200（控鈕），主題色 200（橫桿）<br>透明度：100 %（控鈕），50 %（橫桿）</p>
> <p style="font-size: 12px">關<br>顏色：#FAFAFA（控鈕），白（橫桿）<br>透明度：100 %（控鈕），30 %（橫桿）</p>
> <p style="font-size: 12px">關<br>顏色：#424242（控鈕），白（橫桿）<br>透明度：100 %（控鈕），10 %（橫桿）</p>