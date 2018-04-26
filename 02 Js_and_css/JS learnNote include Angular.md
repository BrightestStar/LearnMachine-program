<!--2018-4-26-->
## 遇到的的坑
### iframe not work
#### 经过反复排查，不显示的原因是src写成了scr，所以一直无法显示。

### Refused to display 'https://<domain>.com' in a frame because it set 'X-Frame-Options' to 'some-origin'.
#### 经查阅资料，只有当架设iframe的网站与发出X-Frame-Options的网站相同（X-Frame-Options相同），才能显示发出X-Frame-Options网页的内容。

#### 解决方法在发出X-Frame-Options的方法中加入response.setHeader("X-Frame-Options", "SAMEORIGIN");
[参考资料](http://caibaojian.com/x-frame-options.html)
[参考资料](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/X-Frame-Options)
[参考资料](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)
<!--2018-4-26-->

<!--2018-4-25-->
## 学习内容
### angularJS orderBy
#### 在数组中排序，使用orderBy: 'object.key'
`laborInfo = [{id: 'foo'}, {id: 'bar'}]`  
`<li ng-repeat="laborEle in LaborInfo | orderBy: 'id'">`  

### angularJS forEach
`Object = [{'foo01':'bar01'},{'foo02':'bar02'}]`  
`angular.forEach(Object, function(value, key))`   
### angular isObject && isXxx 方法
`angular.isObject(value)` #返回true false

#### [参考资料](https://docs.angularjs.org/api/ng/filter/orderBy#orderBy-arguments)

## 遇到的坑
### 没有办法使用css 将两个嵌套的表格，别接成一个没有嵌套的表格。一下代码是一个嵌套表格的代码。
` <table>`  
`<tr ng-repeat="info in Infos">`   
`<td ng-if="true" ng-repeat='i in info'>{{i.key}}</td>`     
`<td ng-if="false">{{info.key}}</td>`       
`</tr>`     
`</table>`      
### 没有办法将其改成统一格式的表格
` <table>`          
`<tr ng-repeat="info in Infos">`        
`<td>{{info.key}}</td>`     
`</tr>`     
`</table>`      

### 解决办法，定义两个object (a, b) ，点击a.push(b)，然后按id排序。
`<ul>`      
`<li ng-repeat="info in Infos | orderBy: 'id'">`        
`<span ng-click="check(info.key)">{{info.value}}</span>`        
`</li>`     
`</ul>`     

`$scope.check = (key)->`        
`  if key == '有嵌入表格的key'`       
`    angular.forEach($scope.infoChild, (i)->`       
`      $scope.info.push(i)`     
`    )`     
<!--2018-4-25-->

<!--2018-4-24-->
## 遇到的坑
#### Error: ngModel:nonassign Non-Assignable Expression
#### 分析原因：是由ng-model=“xxx()” 书写错误导致的。
#### 正确的写法： ng-model="xxx" 或者 ng-click="xxx()"

## 学习内容
### ngModel
#### ngModel命令用于绑定( input, select, textarea 或者 custom from control) 作为一个特性
#### [参考资料] (https://code.angularjs.org/1.4.7/docs/api/ng/directive/ngModel)

### 调试angular JS
#### 安装两个插件 angular JS batrang 和 angular JS spector，console中没有angularJS 需要重启浏览器。安装好后，可以在页面看到任意变量，如需要在console中调试，在页面右键点击想要调试的变量，然后输入$scope.xxx。
#### [参考资料](https://blog.csdn.net/fangjuanyuyue/article/details/51201622)
<!--2018-4-24-->

<!-- 2018-4-23 -->
## 学习内容

### angular Js router
#### URL Parameters
#### 'hello' -Matches only if the path is exactly '/hello'.
#### '/user/:id' -Matches '/user/bob' or '/user/1234!!!' or even '/user/' but not '/user' or '/user/bob/details'.
#### '/user/{id}' - Same as the '/user/:id',but using curly brace syntax.
#### 'user/{id:int}' -The params is interpreted as integer.

#### Using Parameters in Links
#### To create a link that passes parameters, use the state name like a function and pass it an object with parameter names as keys. The proper href will be generated.
#####  ui-sref='stateName' - Navigate to state, no params. 'stateName' can be any valid absolute or relative state, following the same syntax rules as $state.go()
##### ui-sref='stateName({param: value, param: value})' -Navigate to state, with params.
#### For example :
<a ui-sref="contacts.detail({contactId: id})">View Contact</a>
#### [参考资料](https://github.com/angular-ui/ui-router/wiki/Quick-Reference#ui-sref)


## 遇到的坑
#### angular JS 中 javascript page 无法跳转
### 原因：posts.html写成了posts/html
<!-- 2018-4-23 -->

<!-- 2018-3-22 -->
## 学习内容
### Build a Real-Time Slack Clone using AngularFire:
Creating Direct Messages
## 遇到的问题：
`Uncaught SyntaxError: Unexpected identifier`
#### 经调试，发现错误代码如下：
`var path = uid1 < uid2 ? uid1 + '/' + uid2 : uid2 + '/' uid1;`
#### 正确代码如下：
`var path = uid1 < uid2 ? uid1+'/'+uid2 : uid2+’/‘+uid1;`
#### 原因为url之间有空格。

## 总结：
#### url如无特殊情况，不能有空格。
<!-- 2018-3-22 -->

<!-- 2018-3-21 -->
## 学习内容
### Build a Real-Time Slack Clone using AngularFire
## 遇到的问题：
`angular.js:14800 Error: transition superseded`  
    `at $StateProvider.$get (angular-ui-router.js:2909)`  
    `at Object.invoke (angular.js:5106)`  
    `at angular.js:4893`  
    `at Object.getService [as get] (angular.js:5047)`  
    `at angular-ui-router.js:3696`  
    `at Object.invoke (angular.js:5106)`  
    `at angular.js:4903`  
    `at forEach (angular.js:408)`  
    `at createInjector (angular.js:4903)`  
    `at doBootstrap (angular.js:1955) "Possibly unhandled rejection: {}"`
#### 经测试发现，如果清楚缓存可以登录一次，不会报错，但是第二次就不可以了。而切换到master，就没问题。
#### 分析：会不会是其他没有写的代码导致的呢？经测试不是因为这个原因。是因为url写错了。没有写localhost:4000，而是使用0.0.0.0:4000。后经再次测试，这个报错是因为已经登录过引起的，与resolve没有关系。
<!-- 2018-3-21 -->

<!-- 2018-3-20 -->
## 学习内容
### Build a Real-Time Slack Clone using AngularFire
## 遇到的问题：
##### Error: [$controller:ctrlreg] The controller with the name 'AuthCtrl' is not registered.
##### 原因为 controller 的名字没有被注册。经查找，为html页面引用资源src错误的写成了scr。

###### 参考资料：angular API
<!-- 2018-3-20 -->
