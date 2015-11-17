# 概念

## 3D
每個物件都是處於一個3D的空間的物件，而空間中代表Z座標的方向軸是朝使用者延伸。每個物件皆用X和Y座標代表長寬，Z代表距離基底的高度，並且都有著固定**1dp**的厚度。

![座標系](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7UXpQYWltVjNPWXc/whatismaterial_environment_3d.png)

## 陰影
陰影是由兩點模擬光源照射而成，一點在正上方，一點在正上方偏上，整合兩個光源的陰影即可產生一個柔和的陰影效果。
![](螢幕快照 2015-11-17 下午3.57.15.png)

陰影等於是Z座標的表徵，物件在基底上產生的陰影，將直接對應到其與基底的距離。