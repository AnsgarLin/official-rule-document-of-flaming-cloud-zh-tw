# 圖片讀取

色彩在讀取並顯示的過程中，應分別從不透明度、灰階和飽和度，各分三階段來進行漸變。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7M05lWkx3NTVncEE/patterns_loadingimages1.png)
> <p style="font-size: 12px">不透明度<br>從 0 到 100 %</p>
> <p style="font-size: 12px">曝光<br>伽瑪從 0 到 1<br>灰度從低到高</p>
> <p style="font-size: 12px">飽和度<br>從 0 或 20 % 到 100 %</p>

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B08MbvYZK1iNM2xXbGwyN2pISUE/patterns-imagerytreatment-imageload-transition_large_xhdpi.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B08MbvYZK1iNM2xXbGwyN2pISUE/patterns-imagerytreatment-imageload-transition_large_xhdpi.mp4" type="video/mp4">
</video>
> <p style="font-size: 12px">讀取圖片建議使用較長的時間間隔；在轉場過程則反之</p>

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B0NGgBg38lWWdlUtbnpFOUMzRUk/patterns-loadingimages-loading-070901_Load_Add_Animation_xhdpi_002.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B0NGgBg38lWWdlUtbnpFOUMzRUk/patterns-loadingimages-loading-070901_Load_Add_Animation_xhdpi_002.mp4" type="video/mp4">
</video>
> <p style="font-size: 12px">轉場則應越快越好</p>