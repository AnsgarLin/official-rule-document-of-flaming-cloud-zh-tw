# 卡片

卡片是一個有紙張意義的物件，上面同時具有多種不同類型的物件，例如影像、字串、連結等，但不能擁有可滾動的元件。

> [使用時機](#使用時機)

## 使用時機
* 為一個容器，包含許多不同的物件和動作  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3WFBLZjBNNGpnQzg/components_cards1.png)

* 不需要比較內容

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3am9VWWFlbHVJNDg/components_cards3.png" style="max-width:50%"/>

* 可支援較長的文字內容

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Y1lRbzJERTJIa28/components_cards2.png" style="max-width:50%"/>

## 不應使用時機
* 列表 

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsZGZTVVJIWW4zZWs/components_cards8.png" style="max-width:50%"/>
> <p style="font-size: 12px">以卡片切割會影響使用者快速遊覽列表</p>

* 不需要過多文字描述的圖片

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsN2F1Y2RWNzQ0R1U/components_cards10.png" style="max-width:50%"/>

## 組成
一個卡片可能最多會有以下幾個組成：
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3MHh2ZlhHVUMyQlk/components_cards17.png)
> <p style="font-size: 12px">1. 標頭<br>2. 標題<br>3. 多媒體<br>4. 內文<br>5. 操作</p>

組成排列方式可以有很多種，相同的是卡片提供一個可以獲得更多資訊的入口，不要在卡片上放置過多的訊息和操作。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsZWNWWDZVek41S1U/components_cards_content2.png" style="max-width:50%"/>
> <p style="font-size: 12px">每個卡片可以有不同物件和擺置</p>

卡片組成在排列時需要盡量凸顯重點，例如以下兩個方法：

* 圖片

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cXVadmtJa19wT3M/components_cards_content1.png" style="max-width:50%"/>
> <p style="font-size: 12px">圖片可讓使用者快速區別彼此差別，同時也要注意不要讓圖片影響文字的清晰程度</p>

* 字體

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3NGo3QkpVWTNBZzA/components_cards_content3.png" style="max-width:50%"/>
> <p style="font-size: 12px">放大標題可以直接看出每個卡片的內容主旨</p>

## 主要操作
卡片的主要操作對象為其本身，有以下幾種：

* 排序  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dU9ETE9PUDExMUU/components_cards_behavior1.png)
> <p style="font-size: 12px">使用拖拉的方式可以重新排列卡片順序，預設卡片排列方向為由左至右，由上至下</p>

* 滾動  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dnROYlN6b1hsTmM/components_cards_behavior2.png" style="max-width:50%"/>
> <p style="font-size: 12px">卡片只能垂直方向滾動</p>

## 附屬操作
放置在卡片下方，可依照需求增加附屬操作，附屬操作可為以下兩種：
 
* 按鈕  

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3aHp5aGtIT0dwQ28/components_cards19.png)

* 控件

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3OXdMTGNiaG9MVXc/components_cards_action1.png)
> <p style="font-size: 12px">除了評分，也可以是日期選擇器</p>

如果附屬操作過多，可以在卡片右上方增加一個選單按鈕，但也不要在此選單增加過多選項。

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cXJ0OTI1MXJUV0U/components_cards_action5.png)

當卡片內容超過卡片最高高度時，由於卡片不能具有可滾動元件，所以有以下兩個方式處理：

* 截斷內容  

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dnROYlN6b1hsTmM/components_cards_behavior2.png" style="max-width:50%"/>

* 使用附屬按鈕，讓卡片可進行暫時性延展

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Q3BSMEZNOVNOWU0/components_cards_behavior7.png)

## 設計規範
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3bG0tNkIyNDhJZEU/components_cards28.png)
> <p style="font-size: 12px">標頭<br>圖片高：36 dp<br>圖片寬：36 dp<br>標題字體：14 sp<br>副標字體：14 sp<br>內容上下左右間距：16 dp<br></p>
> <p style="font-size: 12px">多媒體<br>高：與寬比為 9：16 或 1：1（建議）<br>寬：同螢幕寬<br></p>
> <p style="font-size: 12px">標題<br>標題字體：24 sp<br>副標字體：14 sp<br>上間距：24 dp<br>下間距：24 dp（下方無其他組成），16 dp（下方為內文或操作）高：依內容而定</p>
> <p style="font-size: 12px">內文<br>字體：14 sp<br>上間距：16 dp<br>下間距：24 dp（下方無其他組成），16 dp (下方為內文或操作）小點左間距：16 dp</p>
> <p style="font-size: 12px">操作（圖示）<br>上下間距：垂直置中左右間距：16 dp<br>圖示間間距：8dp
</p>
> <p style="font-size: 12px">操作（按鈕）<br>
同按鈕的[設計規範](button.html#設計規範)<br>
按鈕間間距：8 dp（橫向），4 dp（縱向）

以下顯示各種不同的組合，並提供上圖沒有的數值：
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3dmZtRndUeWtpMUk/components_cards30.png)
> <p style="font-size: 12px">標頭<br>
高：72 dp
</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3MXJBM2FCcDVscjg/components_cards34.png)
> <p style="font-size: 12px">標題<br>
副標上間距：12 dp
</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3c29HUjIwc19JQlU/components_cards24.png)
![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3eXpkdFhrZk9oM1k/components_cards25.png)
> <p style="font-size: 12px">標題被圖片和操作覆蓋<br>
圖片寬：80 dp（小圖），112 dp（大圖）<br>
圖片高：80 dp（小圖），112 dp（大圖）
</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3OTNwYzRRZ0o2dGM/components_cards41.png)
> <p style="font-size: 12px">標題被圖片和操作覆蓋<br>
圖片寬：240 dp<br>
圖片高：240 dp<br>
操作圖示右間距：28 dp
</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3ajNVOVJyV2VmcXM/components_cards36.png)
> <p style="font-size: 12px">圖示被標題和操作覆蓋
</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3US1pR2N0OTNIaFE/components_cards37.png)
> <p style="font-size: 12px">圖示被標題和操作覆蓋
</p>