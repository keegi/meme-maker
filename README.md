# Meme-Maker

### `1.5 Drawing Project Two`
ctx.fillRect(210 - 40, 200 - 30, 15, 100)

### `1.4 Drawing Project One`
ctx.fillRect(200, 200, 50, 200)

### `1.3 moveTo and lineTo`
ctx.moveTo(50, 50)

### `1.2 Path`
const ctx = canvas.getContext("2d") 캔버스 준비.\
ctx.fillRect(50, 50, 100, 100) 채워진 상자 만들기.

ctx.rect(250, 250, 100, 100).\
ctx.fill().\
ctx.beginPath() 이전 rect,fill을 처리하고 새오룬 rect,fill를 만듬.\
ctx.fillStyle = "red" 새로운 상자에 새로운 색을 체움.\
ctx.fill()