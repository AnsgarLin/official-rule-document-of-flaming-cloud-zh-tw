# 動畫
## 物理特性
物件有重量，且必須倚靠外力移動，因此在設計一個物件移動的軌跡時，必須要考慮現實的物理狀況。每種不同的移動軌跡會帶來不同的感覺，因此一個動畫的設計除了必須要滿足物理現象外，也要帶給使用者一個舒適而非急躁的感覺。

基於上述原因，**漸進式加速或減速**可使物體移動不會像固定速度般的枯燥，但又比隨意增減速來的有規律。
<div align="center">
<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.mp4" type="video/mp4">
</video>
<p style="font-size:12px"> 漸進式加減速</p>
</div>

<div align="center">
<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFVk5Lc195M3c4a28/animation-authenticmotion-massandweight-linear.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFVk5Lc195M3c4a28/animation-authenticmotion-massandweight-linear.mp4" type="video/mp4">
</video>
<p style="font-size:12px"> 線性和非對稱加減速</p>
</div>

物件的**進出場動畫**就屬於一種漸進式加減速，在進場後降速可引起使用者注意；在出場時加速可快速移出使用者視線，降低注意力。
<div align="center">
<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFS2hrd3dPVVFfdHM/animation-authenticmotion-massandweight-do.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFS2hrd3dPVVFfdHM/animation-authenticmotion-massandweight-do.mp4" type="video/mp4">
</video>
<p style="font-size:12px"> 進出場動畫</p>
</div>

基於物理原則，不同重量的物件其受物理現象影響的程度也不同，所以移動軌跡於不同物件也不一定相同。舉例來說，較重的物件其減速的軌跡會比輕的物件長。

## 響應式互動
由於手機設備的特性，其顯示在螢幕上的物件並不具有實際的形體，讓使用者可以直覺的感受出目前碰觸的物體。因此，響應式動畫能主動提示使用者其目前碰觸位置，以及物件當前的狀態。

不同類型的物件有不同的響應式動畫，但主要可分為漣漪、抬升和放射式：
### 漣漪
用於物件表層，讓使用者明確知道目前觸控的中心，以及碰觸到的物件。
<div align="center">
<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>
<p style="font-size:12px">點擊產生漣漪</p>
</div>

<div align="center">
<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.mp4" type="video/mp4">
</video>
<p style="font-size:12px">碰觸產生漣漪</p>
 </div>

### 抬升
用於按鈕類物件，從Z方向的移動改變高度和陰影，讓使用者明確知道目前物件的狀態。
<div align="center">
<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>
<p style="font-size:12px">碰觸產生抬升</p>
</div>

### 放射式
在物件產生或是畫面轉換時，動畫是以使用者碰觸的點為中心點向外擴散，讓使用者可以明確知道碰觸位置，以及提示當前畫面的閱讀方向。
<div align="center">
<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsaDBfZWtha0RwNGM/animation-responsiveinteraction-materialresponse-PointOfOrigin_DO_003.webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsaDBfZWtha0RwNGM/animation-responsiveinteraction-materialresponse-PointOfOrigin_DO_003.mp4" type="video/mp4">
</video>
<p style="font-size:12px">碰觸左下方選單，物件由左下方向右上產生，提示碰觸點為左下</p>
</div>

<div align="center">
<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsVHE4SmRKb3huVXM/animation_responsiveinteraction_radialreaction_xhdpi_003.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsVHE4SmRKb3huVXM/animation_responsiveinteraction_radialreaction_xhdpi_003.mp4" type="video/mp4">
</video>
<p style="font-size:12px">碰觸左上方選單，物件由左上方向右下產生，提示閱讀方向為左上至右下</p>
</div>