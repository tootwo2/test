### 说明

#### Part 1: 优化 index.html 的 PageSpeed Insights 得分97

1. 去除style.css的引用，内嵌到index.html
2. 压缩views/images/pizzeria.jpg和img/profilepic.jpg
3. 将"//fonts.googleapis.com/css?family=Open+Sans:400,700"移到文档底部

#### Part 2: 优化 pizza.html 的 FPS（每秒帧数）

1. 滚动优化，将updatePositions方法里面的获取document.body.scrollTop放到循环外。
2. 调整pizza大小优化，将changePizzaSizes中获取pizza大小的方法简化。
