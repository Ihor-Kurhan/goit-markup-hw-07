# goit-markup-hw-01

.banner {
  min-height: 600px;
  background-image: url(‘../images/car-mobile.jpg’);
  background-position: center top;
  background-size: 960px 576px;
  background-repeat: no-repeat;
}
/*
screen
2x +
0px - 767px
*/
@media screen and (min-device-pixel-ratio: 2) and (max-width: 767px),
  screen and (min-resolution: 192dpi) and (max-width: 767px),
  screen and (min-resolution: 2dppx) and (max-width: 767px) {
  .banner {
    background-image: url(‘../images/car-mobile@2x.jpg’);
  }
}
/*
768px +
*/
@media screen and (min-width: 768px) {
  .banner {
    background-image: url(‘../images/car-tablet.jpg’);
  }
}
/*
screen
2x +
768px +
*/
@media screen and (min-device-pixel-ratio: 2) and (min-width: 768px),
  screen and (min-resolution: 192dpi) and (min-width: 768px),
  screen and (min-resolution: 2dppx) and (min-width: 768px) {
  .banner {
    background-image: url(‘../images/car-tablet@2x.jpg’);
  }
}
/*
1200px +
*/
@media screen and (min-width: 1200px) {
  .banner {
    background-image: url(‘../images/car-desktop.jpg’);
  }
}
/*
2x +
1200px +
screen
*/
@media screen and (min-device-pixel-ratio: 2) and (min-width: 1200px),
  screen and (min-resolution: 192dpi) and (min-width: 1200px),
  screen and (min-resolution: 2dppx) and (min-width: 1200px) {
  .banner {
    background-image: url(‘../images/car-desktop@2x.jpg’);
  }
}
Приклад роботи з контентними зображеннями
<img
 srcset=“photo.jpg 1x, photo@2x.jpg 2x”
 src=“photo.jpg”
 alt=“Опис зображення для усіх версій”
/>