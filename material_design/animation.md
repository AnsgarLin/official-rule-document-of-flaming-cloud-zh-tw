# 動畫

> [物理特性](#物理特性)  
> [響應式互動](#響應式互動)  
> [有意義的動畫](#有意義的動畫)  
> [圖標](#圖標) 

## 物理特性
物件有重量，且必須倚靠外力移動，因此在設計一個物件移動的軌跡時，必須要考慮現實的物理狀況。每種不同的移動軌跡會帶來不同的感覺，因此一個動畫的設計除了必須要滿足物理現象外，也要帶給使用者一個舒適而非急躁的感覺。

基於上述原因，**漸進式加速或減速**可使物體移動不會像固定速度般的枯燥，但又比隨意增減速來的有規律。
<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.mp4" type="video/mp4">
</video>

> <p style="font-size:12px"> 漸進式加減速</p>

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFVk5Lc195M3c4a28/animation-authenticmotion-massandweight-linear.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFVk5Lc195M3c4a28/animation-authenticmotion-massandweight-linear.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">線性和非對稱加減速</p>

物件的**進出場動畫**就屬於一種漸進式加減速，在進場後降速可引起使用者注意；在出場時加速可快速移出使用者視線，降低注意力。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFS2hrd3dPVVFfdHM/animation-authenticmotion-massandweight-do.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFS2hrd3dPVVFfdHM/animation-authenticmotion-massandweight-do.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">進出場動畫</p>

基於物理原則，不同重量的物件其受物理現象影響的程度也不同，所以移動軌跡於不同物件也不一定相同。舉例來說，較重的物件其減速的軌跡會比輕的物件長。

## 響應式互動
由於手機設備的特性，其顯示在螢幕上的物件並不具有實際的形體，讓使用者可以直覺的感受出目前碰觸的物體。因此，響應式動畫能主動提示使用者其目前碰觸位置，以及物件當前的狀態。

不同類型的物件有不同的響應式動畫，但主要可分為以下三種：
* 漣漪  
用於物件表層，讓使用者明確知道目前觸控的中心，以及碰觸到的物件。

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">點擊產生漣漪</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">碰觸產生漣漪</p>

* 抬升  
用於按鈕類物件，從Z方向的移動改變高度和陰影，讓使用者明確知道目前物件的狀態

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">碰觸產生抬升</p>

* 放射式  
在物件產生或是畫面轉換時，動畫是以使用者碰觸的點為中心點向外擴散，讓使用者可以明確知道碰觸位置，以及提示當前畫面的閱讀方向。

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsaDBfZWtha0RwNGM/animation-responsiveinteraction-materialresponse-PointOfOrigin_DO_003.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsaDBfZWtha0RwNGM/animation-responsiveinteraction-materialresponse-PointOfOrigin_DO_003.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">碰觸左下方選單，物件由左下方向右上產生，提示碰觸點為左下</p>

## 有意義的動畫
由前面的章節可以知道，一個動畫不只是單純的效果，也具有隱含的提示功能。因此，一個良好的動畫設計，必須要考慮以下三點：
* 如何引導使用者的注意力

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3RXRFb0tRZEZDUUU/animation_meaninfultransitions_considerations_do.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3RXRFb0tRZEZDUUU/animation_meaninfultransitions_considerations_do.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">展開中心為點擊的物件，並且動畫內容只包含內容而不包含上方按鈕，引導使用者的注意力從列表上的單一選項，進入至下一畫面的圖片</p>

* 動畫之間的連續性

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B08MbvYZK1iNTGRLb2Zud2RUNFE/animation-meaningfultransitions-hierarchicaltiming-4do_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B08MbvYZK1iNTGRLb2Zud2RUNFE/animation-meaningfultransitions-hierarchicaltiming-4do_large_xhdpi.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">每個物件的動畫是接連著啟動，提醒使用者物件之間的權重，也代表閱讀方向</p>

* 動畫效果必須要一致

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B08MbvYZK1iNT2dLWHE1NG8tV00/animation-meaningfultransitions-consistentchoreography-do1_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B08MbvYZK1iNT2dLWHE1NG8tV00/animation-meaningfultransitions-consistentchoreography-do1_large_xhdpi.mp4" type="video/mp4">
</video>

> <p style="font-size:12px">一致的動畫效果，才不至於打亂連續性，讓使用者可以更注意在畫面的流程，而不會使使用者分心，迷失在動畫過程中</p>

## 圖標
以動畫來呈現圖標的轉變，可使畫面更加生動活潑。

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFbFRfT196SWRyS2s/animation_delightfuldetails_wellcrafted.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFbFRfT196SWRyS2s/animation_delightfuldetails_wellcrafted.mp4" type="video/mp4">
</video>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B2wX4iIvu8L6ZHZfV1NfRHdCZHM/animation-delightfuldetails-030401_Status_Change_xhdpi_003.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B2wX4iIvu8L6ZHZfV1NfRHdCZHM/animation-delightfuldetails-030401_Status_Change_xhdpi_003.mp4" type="video/mp4">
</video>