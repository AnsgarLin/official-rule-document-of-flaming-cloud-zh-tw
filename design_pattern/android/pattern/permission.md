# 權限

要求使用者權限必須要簡潔且容易理解，務必詳細解釋為何需要此種權限，用於何處。

## 類型
權限依照類型可分成如下表中的幾大類：

| 權限 | 功能 |
| -- | -- |
| 日曆 | 編輯日曆 |
| 相機 | 照相或綠影 |
| 聯絡人 | 編輯聯絡人 |
| 地點 | 定位資訊 |
| 麥克風 | 聲音錄製 |
| 電話 | 撥打和編輯來電 |
| 身體感測 | 心跳率和相關類型 |
| 簡訊 | 傳送和瀏覽簡訊 |
| 儲存 | 瀏覽多媒體和檔案 |

## 要求權限
有些時候使用者的行為直接傳達明確的意圖，就不需要要求權限，如拍照、選擇聯絡人或撥打等。

但大部分的情況，需要在執行階段前跟使用者進行權限啟用確認，依照權限的重要程度和相對應的詢問方式可分成四個象限，如下圖：

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3QXkxaEJ4OTM3X0E/patterns_permissions_patterns0.png)
> <p style="font-size: 12px">左右<br>需要目標權限的原因不明確，則需要先解釋</p>
> <p style="font-size: 12px">上下<br>應用是否需要目標權限才可使用，不同意則只會影響某部分操作</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3OGJnTll2dmQ3T2c/patterns_permissions_patterns1.png" style="max-width:50%"/>
> <p style="font-size: 12px">原因不明，預先解釋</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3N1hpVkRMWXU0WkE/patterns_permissions_patterns2.png" style="max-width:50%"/>
> <p style="font-size: 12px">原因明確且必要，預先要求</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3eE9IYkVXcU9fLXc/patterns_permissions_patterns4.png" style="max-width:50%"/>
> <p style="font-size: 12px">原因明確且非必要，執行前要求</p>

## 拒絕權限
由於拒絕開放權限會造成某些功能無法正常使用，因此必要時需要提供提示訊息，情境可略分為以下兩種：

* 權限背使用者拒絕後
* 權限自動拒絕，通常用於使用者曾經點選拒絕，並且勾選"不要再問詢問"時

為了讓功能即使在被拒絕權限後也可使用，必需要提供回復權限的方式。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3WGxFdDdfR1o4U2M/patterns_permissions_denied1.png" style="max-width:50%"/>
> <p style="font-size: 12px">提示目標權限未開，並提供開啟路口</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3eDc0Zi1ZTlE5NjA/patterns_permissions_denied2.png" style="max-width:50%"/>
> <p style="font-size: 12px">應用因爲權限被關閉而無法繼續使用，則必須告知原因並提供開啟路口</p>

