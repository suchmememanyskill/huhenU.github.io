# huhenU.github.io
test
```javascript
function slide() {
    var num = 0, style = document.getElementById('container').style;
    window.setInterval(function () {
        // increase by num 1, reset to 0 at 4
        num = (num + 1) % 4;

        // -600 * 1 = -600, -600 * 2 = -1200, etc 
        style.marginLeft = (-600 * num) + "px"; 
    }, 3000); // repeat forever, polling every 3 seconds
}
```
