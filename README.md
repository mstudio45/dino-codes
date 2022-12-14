# dino-codes
chrome://dino


140K+ score:
```
Runner.instance_.saveHighScore(0, true);Runner.config.ACCELERATION = 10000;setTimeout(function(){Runner.instance_.gameOver()Runner.instance_.saveHighScore(Runner.instance_.highestScore, false)},10000)
```

Laser on 'D' (by congaterori on github):
```
b = Runner.instance_.clearCanvas;
window.addEventListener("keydown", checkKeyPressed, false); function checkKeyPressed(l) { if (l.keyCode == "68" ) {drawline()}};
function drawline() {
if (Runner.instance_.horizon.obstacles.length>0){
Runner.instance_.clearCanvas=function(){};
Runner.instance_.canvasCtx.beginPath();
Runner.instance_.canvasCtx.moveTo(Runner.instance_.tRex.xPos+23,Runner.instance_.tRex.yPos+20);
Runner.instance_.canvasCtx.lineTo(Runner.instance_.horizon.obstacles[0].xPos+10,Runner.instance_.horizon.obstacles[0].yPos+10);
Runner.instance_.canvasCtx.stroke();
setTimeout(function(){Runner.instance_.clearCanvas = b;}, 15);
Runner.instance_.horizon.removeFirstObstacle();}}
```

No gravity:
```
Runner.instance_.tRex.config.GRAVITY = 0.1
```

No gravity:
```
Runner.instance_.tRex.config.GRAVITY = 0.1
```
