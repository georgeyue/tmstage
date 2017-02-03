```javascript
javascript:(function(){ var h=window.location.host.split('.');var t=prompt("cookie key");var a=prompt("Enter cookie value");if (t && a) {document.cookie = t+"="+a+"; path=/; domain="+("."+h[h.length-2]+"."+h[h.length-1]);}})()
```
