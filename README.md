# login-page
好看的登录界面
background-size:
1.length
设置背景图像的宽高度
2.percentage
按照父元素的百分比设置背景宽高度
3.cover
将图片完全覆盖住背景区域，导致有些部分没有显示在区域里
4.contain
把图片扩展至最大尺寸，有可能图片小了无法覆盖住区域


如何把整个图片完整显示在浏览器？
1.设置整个区域的vw，vh(非常重要)
2.然后header区域的width=100%，height=100%（支撑整个图片，防止塌陷）
background-size：100% 100%
