# web-design
前端学习笔记+md学习笔记

# Css
```/* 滚动条样式 */
/* 滚动条整体 */
.parentWrap::-webkit-scrollbar {
 width: 3px;
}
/* 滚动条轨道样式 */
 .parentWrap::-webkit-scrollbar-track {
/*  background-color:red; */
 -webkit-border-radius: 2em;
 -moz-border-radius: 2em;
 border-radius:2em;
}
/* 滑块样式 */
 .parentWrap::-webkit-scrollbar-thumb {
 background-color:#8AACFF;
 -webkit-border-radius: 2em;
 -moz-border-radius: 2em;
 border-radius:2em;
}
.parentWrap{
	max-height:400px;
	overflow:auto;
}
/* 滚动条样式结束 */
```
