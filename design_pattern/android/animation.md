# 動畫
## 物理特性
物件有重量，且必須倚靠外力移動，因此在設計一個物件移動的軌跡時，必須要考慮現實的物理狀況。每種不同的移動軌跡會帶來不同的感覺，因此一個動畫的設計除了必須要滿足物理現象外，也要帶給使用者一個舒適而非急躁的感覺。

基於上述原因，**漸進式加速或減速**可使物體移動不會像固定速度般的枯燥，但又比隨意增減速來的有規律。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="https://material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.webm" type="video/webm">
  <source src="https://material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.mp4" type="video/mp4">
</video>
  <p style="text-align: center; font-size:12px"> 漸進式加減速</p>
</div>

<div>
<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFVk5Lc195M3c4a28/animation-authenticmotion-massandweight-linear.webm" type="video/webm">
  <source src="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFVk5Lc195M3c4a28/animation-authenticmotion-massandweight-linear.mp4" type="video/mp4">
</video>
  <p style="text-align: center; font-size:12px"> 線性和非對稱加減速</p>


物件的進出場動畫就屬於一種漸進式加減速，在進場後降速可引起使用者注意；在出場時加速可快速移出使用者視線，降低注意力。

<video height="auto" width="100%" preload="metadata" loop="" controls>
  <source src="
http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFS2hrd3dPVVFfdHM/animation-authenticmotion-massandweight-do.webm" type="video/webm">
  <source src="
http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3T7oTWa3HiFS2hrd3dPVVFfdHM/animation-authenticmotion-massandweight-do.mp4" type="video/mp4">
</video>
  <p style="text-align: center; font-size:12px"> 進出場動畫</p>


基於物理原則，不同重量的物件其受物理現象影響的程度也不同，所以移動軌跡於不同物件也不一定相同。舉例來說，較重的物件其減速的軌跡會比輕的物件長。

## 響應式互動
由於手機設備的特性，其顯示在螢幕上的物件並不具有實際的形體，讓使用者可以直覺的感受出目前碰觸的物體。因此，響應式動畫能主動提示使用者其目前碰觸位置，以及物件當前的狀態。

不同類型的物件有不同的響應式動畫，但主要可分為漣漪、抬升和放射式：
### 漣漪
多用於物件表層，讓使用者明確知道目前觸控的中心，以及碰觸到的物件
<video height="auto" width="500%" preload="metadata" loop="" controls>
  <source src="
https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.webm" type="video/webm">
  <source src="
https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>
  <p style="text-align: center; font-size:12px"> 點擊產生漣漪</p>

<video height="auto" width="50%" preload="metadata" loop="" controls>
  <source src="
https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.webm" type="video/webm">
  <source src="
https://material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.mp4" type="video/mp4">
</video>
  <p style="text-align: center; font-size:12px"> 碰觸產生漣漪</p>
