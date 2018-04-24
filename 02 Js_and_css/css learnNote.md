<!--2018-4-24-->
## 学习内容
### 如何将表格做成4列
### 使用float:left，代码如下：
`<table ng-if="defaultYBg" style="color:white;font-size:13px;width:100%">`  
`<tr ng-repeat="(key, value) in yBgInfo" style="float:left;width:50%">`  
`<td style="float:left;width:25%">{{key}}</td>`  
`<td style="float:left;width:25%">{{value}}</td>`    
`</tr>`  
`</table>`  
#### [参考资料](https://www.w3schools.com/howto/howto_css_four_columns.asp)
<!--2018-4-24-->
