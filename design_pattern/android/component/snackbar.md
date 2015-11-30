# 提示欄

對於使用者的操作提供一個簡單的反饋。

> [規範](#規範)

提示欄的高度同於[懸浮式按鈕](button.html#懸浮式按鈕)，由下向上浮出，並由使用者移除或是在一段時間後會自動消失。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsSVRPNWlSTm81T2M/components_snackbar_usage_fabdo_005.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsSVRPNWlSTm81T2M/components_snackbar_usage_fabdo_005.mp4" type="video/mp4">
</video>

提示欄會具有以下特性：

* 純大寫  

按鈕字母全部大寫，如同[平面化按鈕](button.html#平面化按鈕)

* 純文字  
欄位內只能放文字，不能放圖示

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7M2QzbjlPWUwtcXc/components_toasts_usage1.png" style="max-width:50%"/>

* 唯一性  
一次只會顯示一個提示欄，如有多個要連續顯示，則前者必須要先淡出，後者才可以推入。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsX3VhUHNoaWVEbDQ/components_snackbars_usage_consecutivesbdifferenttype_005.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsX3VhUHNoaWVEbDQ/components_snackbars_usage_consecutivesbdifferenttype_005.mp4" type="video/mp4">
</video>

* 至多一個操作  
如需要多個操作，建議使用[對話框](dialog.html)

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7Mm5pd0t5VmVRb1U/components_toasts_usage5.png" style="max-width:50%"/>

## 規範

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B57Y8yNEHsZPcS1OaVBVajhpeDQ/components_toasts_mobile4.png)
> <p style="font-size: 12px">欄高：48 dp（單行），80 dp（雙行），112 dp（雙行且按鈕和文字同列）<br>背景顏色：#323232<br>文字左右間距：24 dp<br>文字上下間距：14 dp（單行），24 dp（雙行）<br>字體：14 sp</p>
> <p style="font-size: 12px">按鈕<br>左右間距：24 dp（與文字同行才有）<br>下間距：14 dp（與文字同列才有）<br>字型：Roboto Medium<br>字體：14 sp</p>