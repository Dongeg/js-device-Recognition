# js-device-Recognition
js设备区分
```javascript
var UA=window.navigator.userAgent;
var CLICK='click';
if(/ipad|pad|iphone|android/.test(UA)){
   CLICK='tap';   //zepto框架中的触摸事件
}
$(".class")[CLICK](function(){

})
```
