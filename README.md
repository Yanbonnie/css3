# css3
css3使用
table中的td内容超出隐藏

table标签需要设定属性 table-layout: fixed;width:XXXpx;
在要超出隐藏的td标签上设定属性  white-space: nowrap;text-overflow: ellipsis;overflow: hidden; 
不要忘了给table加个宽度 
