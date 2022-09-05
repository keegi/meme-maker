# Meme-Maker

### `1.5 Drawing Project Two`
ctx.fillRect(210 - 40, 200 - 30, 15, 100)\
ctx.fillRect(350 - 40, 200 - 30, 15, 100)\
ctx.fillRect(260 - 40, 200 - 30, 60, 200)\

ctx.arc(250, 100, 50, 0, 2 * Math.PI)\
ctx.fill()\

ctx.beginPath()\
ctx.fillStyle = "white"\
ctx.arc(260 + 10, 80, 8, Math.PI, 2 * Math.PI)\
ctx.arc(220 + 10, 80, 8, Math.PI, 2 * Math.PI)\
ctx.fill()

### `1.4 Drawing Project One`
ctx.fillRect(200, 200, 50, 200)\
ctx.fillRect(400, 200, 50, 200)\
ctx.fillRect(300, 300, 50, 100)\
ctx.fillRect(200, 200, 200, 20)\
ctx.moveTo(200, 200)\
ctx.lineTo(325, 100)\
ctx.lineTo(450, 200)\
ctx.fill()

### `1.3 moveTo and lineTo`
ctx.moveTo(50, 50)\
ctx.lineTo(150, 50)\
ctx.lineTo(150, 150)\
ctx.lineTo(50, 150)\
ctx.lineTo(50, 50)\
ctx.stroke()

### `1.2 Path`
const ctx = canvas.getContext("2d") 캔버스 준비.\
ctx.fillRect(50, 50, 100, 100) 채워진 상자 만들기.

ctx.rect(250, 250, 100, 100).\
ctx.fill().\
ctx.beginPath() 이전 rect,fill을 처리하고 새오룬 rect,fill를 만듬.\
ctx.fillStyle = "red" 새로운 상자에 새로운 색을 체움.\
ctx.fill()