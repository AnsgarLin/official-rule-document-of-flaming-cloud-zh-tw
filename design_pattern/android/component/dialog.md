# 對話框

對話框是由文字和各種不同物件所組成，用於中斷使用者目前的操作，來提示一些需要告知的資訊、需要進行的決定等。

> [類型](#類型)  
> [規範](#規範)

使用時有以下幾個情況需要注意：
* 減少中斷  
由於對話框會中斷操作，因此必須要謹慎使用，並非所有需要做的選擇、設定或顯示資訊都需要靠對話框。也可以用選單或是延展物件來顯示詳細內容。

* 開關方式  
對話框不應該可以直接由其他物件開啟。且可以透過點擊取消、點擊對話框外部和系統返回鍵關閉。

* 生命週期  
在被取消或是完成決定前，對話框都不應該被關閉。

* 滾動元件  
對話框內容應盡量攤平，避免使用可滾動的元件

以下有兩種特殊的對話框類型，可跳脫一些限制：
* 全螢幕  
因為不會產生圖層上的變化，所以可再開啟一層對話框

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3bWxmZ1M0UTJBR0E/components_dialogs_fullscreen1.png" style="max-width:50%"/>

* 可滾動元件  
有些時候使用滾動元件是不能避免的

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3T29XaVRQa0QxZkk/components_dialogs_1.png)
> <p style="font-size: 12px">固定標頭可以隨時在語意上連結每一選項</p>

## 類型
對話框有分成以下幾種類型：

* 警告   
無標頭，用一行或兩行闡述問題，並提供操作按鈕。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3TzFHYVlrbWF2bnM/components_alerts_1.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3cGUwa0F5ekUwVms/components_dialogs_usage1.png" style="max-width:50%"/>
> <p style="font-size: 12px">有標頭的對話框用於重要性較高的警告，像是連線問題或刪除檔案，並伴隨著問題說明</p>

* 選單對話框  
詳細請查看[選單]()

* 簡易對話框  
列出可點擊的選項，不提供關閉按鈕。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3UjRsSGxGS0dRVzA/components_dialogs_simple1.png" style="max-width:50%"/>
> <p style="font-size: 12px">選項在點選後即會立即啟動相對應操作並關閉</p>

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3SXJuazMwTkFnY0U/components_dialogs_simple5.png)
> <p style="font-size: 12px">當選單對話框的任一選項多於單行時，則應改為使用此類型</p>

* 確認對話框  
列出控制物件給使用者選擇，並提供確認和取消的按鈕。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3aXcyajZDN29jS1k/components_dialogs_confirmation2.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3eWhJZmwwdFpob0k/components_dialogs_confirmation5.png" style="max-width:50%"/>
> <p style="font-size: 12px">同[選取器]()

* 全螢幕  
在有限的空間下使用複雜的對話框時，在手機端應使用全螢幕呈現。多用於設定頁面，並提供關閉和確認按鈕。

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3bWxmZ1M0UTJBR0E/components_dialogs_fullscreen1.png" style="max-width:50%"/>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3OV9CR1NMNnpxN2s/components_dialogs_fullscreen2.png" style="max-width:50%"/>
> <p style="font-size: 12px">運用全螢幕，將在視覺上把畫面的基準面抬升到與對話框相同，所以可以再開一層對話框</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3Qy04bFg2X0F4UkE/components_dialogs_fullscreen8.png" style="max-width:50%"/>
> <p style="font-size: 12px">關閉和確認按鈕應置於上方。如果有改變設定，則未存擋就退出時需要進行確認；反之則直接關閉</p>

<img src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3OVBIMmJkVUllWjQ/components_dialogs_fullscreen7.png" style="max-width:50%"/>
> <p style="font-size: 12px">應用列標題應簡短，如在某些語系下會過長，則放入對話框中</p>

## 規範
> <p style="font-size: 12px">文字<br>同於[卡片](card.html#卡片)

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3c3htV1IweVNKcFU/components_dialogs_updates1.png)

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsSzE3dEVKNnNTM2c/components_dialogs_updates2.png)
> <p style="font-size: 12px">按鈕間距：8 dp<br>
其餘同於[平面化按鈕](button.html#平面化按鈕)

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3VlYzX2d5TGl5N2s/components_dialogs_consistent_placement3.png)

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3RS1ESkM1cG5zNjg/components_dialogs_stacked.png)

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3OExlLU5oNDhjYW8/components_dialogs_updates5.png)

![](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3clVROTBzOU1hMHM/components_dialogs_updates10.png)