

<!-- 2018-3-20 -->
## 学习内容
### Build a Real-Time Slack Clone using AngularFire
## 遇到的问题：
##### Error: [$controller:ctrlreg] The controller with the name 'AuthCtrl' is not registered.
##### 原因为 controller 的名字没有被注册。经查找，为html页面引用资源src错误的写成了scr。

###### 参考资料：angular API
<!-- 2018-3-20 -->

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
    `at doBootstrap (angular.js:1955) "Possibly unhandled rejection: {}”`
#### 经测试发现，如果清楚缓存可以登录一次，不会报错，但是第二次就不可以了。而切换到master，就没问题。
#### 分析：会不会是其他没有写的代码导致的呢？经测试不是因为这个原因。是因为url写错了。没有写localhost:4000，而是使用0.0.0.0:4000。后经再次测试，这个报错是因为已经登录过引起的，与resolve没有关系。
<!-- 2018-3-21 -->

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
#### For example :
<a ui-sref="contacts.detail({contactId: id})">View Contact</a>


## 遇到的坑
#### angular JS 中 javascript page 无法跳转
### 原因：posts.html写成了posts/html
<!-- 2018-4-23 -->
