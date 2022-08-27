# Starbucks_Clone

### #구글 아이콘 사용
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

### #BEM(Block Element Modifier)
HTML 클래스 속성의 작명법
- 요소__일부분 : 언더바 기호로 요소 일부분 표시
- 요소--상태 : 하이픈 기호로 요소 상태 표시

### #링크아직 없을 때
```html
<a href="javascript:void(0)"></a>
```

✏️ https://cdnjs.com/libraries/lodash.js
```js
<script src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.21/lodash.min.js" integrity="sha512-WFN04846sdKMIP5LKNphMaWzU7YpMyCU245etK3g/2ARYbPK9Ub18eG+ljU96qKRCWh+quCY7yefSmlkQw1ANQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```
```js
window.addEventListener('scroll', _.throttle(function() {
  console.log('scroll!');
}, 300));  // _.throttle(함수, 시간)
```
__-> 화면을 스크롤할 때 실행되는 함수의 개수를 일정시간동안 한 번만 수행하도록 함.(_.throttle)__

✏️ https://cdnjs.com/libraries/gsap
```html
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.10.4/gsap.min.js" integrity="sha512-VEBjfxWUOyzl0bAwh4gdLEaQyDYPvLrZql3pw1ifgb6fhEvZl9iDDehwHZ+dsMzA0Jfww8Xt7COSZuJ/slxc4Q==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```
__gsap.to(요소, 지속시간, 옵션);__
 
 ### ✔️특정위치로 가기(ex. 화살표 누르면 상단으로 이동)
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.0/ScrollToPlugin.min.js" integrity="sha512-TxuhgzYZZCsKL8STS5wmzau5RF3EotX6lAOZPkOJwfy7q9fXMzhlEHfQI4iUuxVMgkbG5XUtzbjshNCKYL+VXw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```


### #Swiperjs
✏️ https://swiperjs.com/

✔️ Use Swiper from CDN
```html
<link rel="stylesheet" href="https://unpkg.com/swiper@6.8.4/swiper-bundle.min.css" />
  <script src="https://unpkg.com/swiper@6.8.4/swiper-bundle.min.js"></script>
```

### 유튜브 영상 넣기
✏️ https://developers.google.com/youtube/iframe_api_reference?hl=ko

### #랜덤한 숫자를 생성하는 함수
```js
// 범위 랜덤 함수(소수점 2자리까지)
function random(min, max) {
  // `.toFixed()`를 통해 반환된 문자 데이터를,
  // `parseFloat()`을 통해 소수점을 가지는 숫자 데이터로 변환
  return parseFloat((Math.random() * (max - min) + min).toFixed(2))
}
```

### #ScrollMagic cdn
✏️ https://cdnjs.com/libraries/ScrollMagic
```js
<script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.8/ScrollMagic.min.js" integrity="sha512-8E3KZoPoZCD+1dgfqhPbejQBnQfBXe8FuwL4z/c8sTrgeDMFEnoyTlH3obB4/fV+6Sg0a0XF+L/6xS4Xx1fUEg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

### #특수기호
```html
<!-- $copy -->
&copy;
<!-- &lt;div&gt; -->
&lt;div&gt;
```
✏️ https://www.w3schools.com/html/html_entities.asp