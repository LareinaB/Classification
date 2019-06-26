# HTML #
## 1. Doctype作用，HTML5 为什么只需要写 ##
> 
doctype是一种标准通用标记语言的文档类型声明，目的是告诉标准通用标记语言解析器要使用什么样的文档类型定义（DTD）来解析文档.<!DOCTYPE>声明必须是HTML文档的第一行，位于html标签之前
HTML5不基于SGML，所以不需要引用DTD。在HTML5中<!DOCTYPE>只有一种
> SGML: 标准通用标记语言,是现时常用的超文本格式的最高层次标准

## 2.HTML XHTML HTML5的关系 ##
> - HTML属于SGML 
- XHTML属于XML，是HTML进行XML严格化的结果
- HTML5不属于SGML或XML，比XHTML宽松

## 3. 行内元素有哪些，块级元素有哪些，空(void)元素有那些 ##
>- 行内元素：a span i img input select b 等
- 块级元素：div ul ol li h1~h6 p table 等
- 空元素：br hr link 等
## 4. 简述一下你对HTML语义化的理解 ##
简单来说，就是合适的标签做合适的事情，这样具有以下好处：
> 
- 	有助于构架良好的HTML结构，有利于搜索引擎的建立索引、抓取，利于SEO
- 	有利于不同设备的解析
- 	有利于构建清晰的机构，有利于团队的开发、维护
## 5. 常见的浏览器内核有哪些，介绍一下你对浏览器内核的理解 ##
>
- Trident内核：IE
- Gecko内核：NETSCAPE6及以上版本，火狐
- Presto内核：Opera7及以上。[Opera内核原为：Presto，现为：Blink;]
- Webkit内核：Safari，Chrome等。[Chrome的：Blink（WebKit的分支）]
- 浏览器内核又可以分成两部分：渲染引擎和JS引擎。 渲染引擎主要负责取得网页的内容、整理讯息、计算网页的显示方式等，JS引擎则是解析Javascript语言，执行javascript语言来实现网页的动态效果。
## 6. html5有哪些新特性 ##
>	
- 语义化标签: header footer nav section article aside 等
- 增强型表单：date(从一个日期选择器选择一个日期) email(包含 e-mail 地址的输入域) number(数值的输入域) range(一定范围内数字值的输入域) search(用于搜索域) tel(定义输入电话号码字段) 等
- 新的API 
	- 视频和音频：audio video
	-  Canvas绘图 SVG绘图
	-  地理定位：Geolocation
	-  拖放API：drag
- web worker：是运行在后台的 JavaScript，独立于其他脚本，不会影响页面的性能
- web storage: localStorage sessionStorage
- WebSocket: HTML5开始提供的一种在单个 TCP 连接上进行全双工通讯的协议

