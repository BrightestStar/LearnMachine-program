rails(包括其他语言在rails中的应用)
—————————————2018-1-29—————————————	7
学习内容：	7
js点击自动计算时间。	7
遇到的坑：	7
拆解/总结：	7
—————————————2018-1-30—————————————	8
学习内容	8
rails序列化：	8
Store:	9
遇到的坑：	10
拆解/总结：	11
————————————-—2018-2-1————————————-—	12
学习内容：	12
1.调试序列化；	12
2.分组方法的使用：	12
遇到的问题：	12
拆解/总结：	12
—————————————2018-2-2————————————-—	14
学习内容：	14
1.ruby 与 rails 中的 group ;	14
2.学习使用yml文件。	15
3.使用radio_button（按钮选项框）的辅助表单：	15
4.order的方法：	15
遇到的问题：	16
拆解/总结：	16
—————————————2018-2-5————————————-—	17
学习内容：	17
1.getting started_with_angularjs and rails:	17
拆解：	17
1.安装gem:	17
2.修改config/routes.rb，在这之前添加model和controller。	17
3.设定application_controller.rb:	17
4.实作rails的function:	18
6.修改js和scss:	19
7.将visitor.coffee改成visitor.js，并定义app	19
8.编写views/xxx/index.html.erb	21
遇到的问题：	23
—————————————2018-2-6————————————-—	24
学习内容：	24
Ruby方法拆解：	24
1.方法的定义：	24
2.方法的简单调用：	24
2.1.运算符形式的方法调用：	24
3.方法的分类：	24
3.1.实例方法：	24
3.2.类方法：	24
3.3.函数式方法：	25
4.方法的定义：	25
4.1.方法的返回值：	25
4.2.参数个数不确定的方法：	26
4.3.补充：	26
遇到的问题：	26
总结：	26
—————————————2018-2-7————————————-—	28
学习内容：	28
1.Action Controller 概览	28
1.1. 参数	28
1.2.会话	28
1.2.1访问会话：	28
1.2.2 闪现会话：	29
1.3 cookies：	30
遇到的问题：	31
总结：	32
—————————————2018-2-8————————————-—	33
学习内容：	33
1.action controller 中的cookies	33
2.渲染XML和JSON数据：	33
3.过滤器：	33
4.请求伪造防护：	34
5.Angular JS 注入依赖：	35
遇到的问题：	37
总结：	37
—————————————2018-2-10———————————-—	38
学习内容：	38
1.按关联表的数量来排序：	38
2.joins 与 left_outer_joins 的区别：	38
遇到的问题：	38
总结：	39
—————————————2018-2-11———————————-—	40
学习内容：	40
1.Learn to Build Modern Web Apps with AngularJS and Ruby on Rails	40
遇到的问题：	40
总结：	40
—————————————2018-2-12———————————-—	42
学习内容：	42
1.Creating Angular Services:	42
遇到的问题：	43
总结：	43
—————————————2018-2-23———————————-—	45
学习内容：	45
Angular on rails 	45
遇到的问题：	45
总结：	45
—————————————2018-2-24———————————-—	47
学习内容：	47
Angular on rails 	47
遇到的问题：	47
总结：	48
—————————————2018-2-26———————————-—	49
学习内容：	49
Angular JS 实作flapper News 项目（copy reddit)总结。	49
遇到的问题：	49
总结：	49
1.$http 	49
2.angular.copy :	51
3.angular JS $templateCache：	51
4.factory service vs provider :	52
—————————————2018-2-27———————————-—	54
学习内容：	54
1.angular-rails（getting-started-with-rails）：	54
2.angular-rails（wiring-everything-up）前后端交互应用中resolve：	54
遇到的问题：	54
总结：	55
—————————————2018-2-28———————————-—	56
学习内容：	56
1.angular-rails（adding-user-authentication-with-devise）	56
遇到的问题：	56
总结：	57
—————————————2018-3-01———————————-—	58
学习内容：	58
1.angular-rails（associating-users-with-posts-and-comments）的熟练练习：	58
遇到的问题：	58
总结：	58
—————————————2018-3-06———————————-—	59
学习内容：	59
工作：将一个表格，在打印预览中显示。	59
遇到的问题：	59
—————————————2018-3-27———————————-—	60
学习内容：	60
学习angular with rails	60
遇到的问题：	60
总结：	60
—————————————2018-3-28———————————-—	61
学习内容：	61
1.angularJS-$http：	61
遇到的问题：	61
总结：	61
1.$http：	61
用法：	61
2.cacheFactory：	62
用法：	62
返回值：	62
具体用法：	62
3.rootScope:	62
4.angular-ui-route：	63
使用方法：	63
$stateProvider：	63
$urlRouterProvider:	63
directives:	64
$state:	64
—————————————2018-3-29———————————-—	65
学习内容：	65
1.angular-devise：	65
Auth.currentUser（）：	65
—————————————2018-4-23———————————-—	67
学习内容：	67
XML：	67
总结：	67
xml是一种标记语言。	67
xml用途。	67
ruby on rails 中创建xml数据	67—————————————2018-1-29—————————————
学习内容：
js点击自动计算时间。
遇到的坑：
在引用jQuery时，要使用相关gem(gem ‘jquery-ui-rails’-使用说明见官网)


拆解/总结：

1.如果希望在其他地方使用js中的自定义对象，需要在function外面定义对象；
2.js经过计算得到的时间是毫秒，如需得到天数，需自行转换；
3.如何使用js来改变input的值？
document.getElementById(“id”).value = value;

———————————————————————2018-1-29————————————————————————————————————2018-1-30—————————————
学习内容
资料来源：ihowr 的实战圣经 （关于序列化）
rails序列化：
序列化（Serialize)通常指的是将一个物件转换成一个可被数据库储存记传输的纯文字形态，反之将这笔资料从数据库读出后转回物件的动作我们就称之为反序例（Deserialize)。
Rails提供了serialize让你指定需要序列化资料字段。任何物件在存入数据库时就会自动序列化成YAML格式，而当从数据库取出时就会自动帮你反序列成原先的物件。这个字段通常用text形态，有比较大的空间可以存储资料，然后将一个Hash物件序列化之后存进去。
例：
Class User < AppilcationRecord
    serialize :settings
end

>user = User.create(:settings => { “sex” => “male”, “url” => “foo”})
>User.find(user.id).setting #=>  { “sex” => “male”, “url” => “foo”}
也可用于一些不需要数据库索引和正视化的一整包资料，例如KML轨迹资料等等。

虽然序列化很方便可以让你储存任意的物件，但是缺点是序列化资料就失去了透过数据库查询索引的功效，你无法在SQL的where条件中指定序列化后的资料。

Store:
Store又在包裹了上面的序列化功能，是个简单又实用的功能，让你可以将某个字段指定存储为Hash值。以上面的例子为例：

Class User < AppilcationRecord
    store :settings, :accessors => [:sex, :url]
end
特别的是其中accessors用来设定可以直接存取的属性，这样就可以像平常一样那样操作sex和url这两个属性。

Class User < AppilcationRecord
    store :settings, :accessors => [:sex, :url]
end

>user = User.new(:sex => “male”, :url => “http://example.com”)
>user.sex
#=> “male”
>user.url
#=>”http://example.com”
>user.settings
#=> {:sex => ”male”, :url => ”http://example.com”}

因为store就像使用hash一样，也可以像hash那样使用：
>user.settings[:food] = “pizza”
>user.settings
#=> {:sex => "male", :url => "http://example.com", :food => “pizza"}

官方更多详情：ruby china 序例化


遇到的坑：
1.以上方法完全不管用。再认真阅读官方文件时。使用下列代码可以成功操作，但无法使用数据库调取：
  include ActiveModel::Serializers::JSON

  attr_accessor :wounder_leve, :wage_stand, :the_count, :the_days

  def attributes=(hash)
    hash.each do |key, value|
      send("#{key}=", value)
    end
  end

  def aaa
    {'wounder_leve' => "一级", 'wage_stand' => 1800, "the_count" => 5000, "the_days" => 10}
  end

2.上面代码完全不管用的原因是因为测试时，手动增加了一个model下的文件：Page，而不是使用rails g model page。
拆解/总结：
1.在使用accessors时，总是报错找不到accessor的方法，于是查看了源代码，发现里面写了一个 options[:accessors]，于是猜想是否因为自己手动新增，而没有引用accessor这个存储器。第一次解读源代码，虽然偶然因素比较多，但是也说明可以慢慢的阅读源代码了。
2.至于手动添加文件不管用，最后我只找到了这样一句话不知道能不能解释我的疑问：

This generator invokes your configured ORM and test framework, which defaults to Active Record and TestUnit.

大概意思是说调用了配置的 ORM（Object Relation Map），默认 Active Record。而自己之前做的测试，是用mongo 生产的，调用的应该是 mongo的配置。所以在Page的rb文件中，引用是错误的。


———————————————————————2018-1-30———————————————————————————————————-—2018-2-1————————————-—
学习内容：
1.调试序列化；
2.分组方法的使用：
将一个类中的多次出现相同的字段的记录做成一个hash。代码如下：
Word.group(:spelling).count
筛选出来值满足某些条件的hash。代码如下：
Word.group(:spelling).count.select{|k, v| v > 1 }
遇到的问题：
引用 gem ‘ jquery-ui-rails’时，报bad uri 的错。没有查到资料。因为之前没有问题，在引用这个gem后出现的问题，于是想到可能是引用出了问题。于是删掉下面的代码：
“//= require jquery-ui” 更新bundle update 可以了。
拆解/总结：
猜测原因：引用的  jquery-ui-rails 的其他数据包，可能与已引用的数据包相冲突。在使用日历的当前页引用下面的代码，可以使用js的日历：
<script src=“https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
在内部引用时，如果产生冲突时，可以使用外部引用——即引用一个网址。

———————————————————————2018-2-1————————————————————————————————————2018-2-2————————————-—
学习内容：
1.ruby 与 rails 中的 group ;
1.1 rails 中的group是一个查找方法，返回一个ActiveRecord::Relation 实例。如需根据订单创建日期查找订单记录，代码如下：
Order.select("date(created_at) as ordered_date, sum(price) as total_price”).group("date(created_at)")
也可以使用group方法后调用count方法，来得到分组项目的总数：
Order.group(:status).count
# => { 'awaiting_approval' => 7, 'paid' => 12 }
也可以使用having来为分组结果添加约束条件（sum(price)为总价）：
Order.select("date(created_at) as ordered_date, sum(price) as total_price").
  group("date(created_at)").having("sum(price) > ?", 100)

1.2 Ruby中的group查找到明确的说明。查找到一个group_by的方法。（调用group_by的对象不能为ActiveRecord::Relation 实例对象）
group_by { |obj| block } → a_hash  （返回值中， key 为 block中的结果）
a = [1, 2, 3, 4, 5, 1, 2]
a.group_by {|i| i % 2 }
# => {1=>[1, 3, 5, 1], 0=>[2, 4, 2]}

2.学习使用yml文件。
2.1修改config/application设定
config.i18n.default_locale = “en" ；
2.2 编写local/en.yml文件
en:
	zzz:
		xxx: yyy
2.3 调用是只许使用t(‘zzz.xxx’)即可。
3.使用radio_button（按钮选项框）的辅助表单：
直接复制代码如下（其中第5行是显示内容，第4行是值）
0.<% input_status = t("unit.input_status") %>
1.<div class="btn-group" data-toggle="buttons">
2.  <% input_status.each do |status| %>
3.    <label class="btn btn-default">
4.      <%= f.radio_button :input_status, status %>
5.      <%= t(status) %>
6.    </label>
7.  <% end %>
8.</div>

4.order的方法：
Allows to specify an order attribute:
User.order(:name)
User.order(email: :desc)
User.order(‘name’)
User.order(‘name DESC, email’) #先排序name，再排序email。
User.order(‘id ASC’).reorder(‘name DESC’) #先排序name，再排序email。
更多详情参考地址：rails api about order

遇到的问题：
在实作TOEFL项目时，没有想到特别好的方法来完成多义词的匹配功能。尝试了多种分组方法、筛选方法，也不能解决问题。
最后只能使用添加字段的方法来完成想要实现的功能。

拆解/总结：
学习2中t等于I18n.t，是个Helper方法，会根据语系来做字符串的替换。
———————————————————————2018-2-2———————————————————————
—————————————2018-2-5————————————-—
学习内容：
1.getting started_with_angularjs and rails:
拆解：
1.安装gem:
gem 'angularjs-rails'
gem ‘bootstrap-sass'
2.修改config/routes.rb，在这之前添加model和controller。
Rails.application.routes.draw do
  resources :visitors, only: [:index, :create, :destroy], defaults: {format: :json}
  #希望rails返回json格式，具体情况可以根据情况来定。
  root to: "visitors#index"
end
3.设定application_controller.rb:
class ApplicationController < ActionController::Base
  # Prevent CSRF attacks by raising an exception.
  # For APIs, you may want to use :null_session instead.
  protect_from_forgery with: :exception
  # angular JS 并不知道如何通过地址的请求，来避免伪造 cookies。 可以通过下面的方法来实现。

  after_action :set_csrf_cookie_for_ng

  def set_csrf_cookie_for_ng
    cookies['XSRF-TOKEN'] = form_authenticity_token if protect_against_forgery?
  end

  private

  def verified_request?
    super || valid_authenticity_token?(session, request.headers['X-XSRF-TOKEN'])
  end
end

4.实作rails的function:
class VisitorsController < ApplicationController
  respond_to :json
  def index
    respond_to do |format|
      format.json { render json: Visitor.all }
      format.html
    end
  end

  def create
    respond_with Visitor.create(visitor_params)
  end

  def destroy
    respond_with Visitor.destroy(params[:id])
  end

private
  def visitor_params
    params.require(:visitor).permit(:first_name, :last_name, :reason)
  end
end

6.修改js和scss:
//= require jquery
//= require jquery_ujs
//= require turbolinks
//= require angular
//= require angular-resource
//= require bootstrap-sprockets
#下面的为scss
@import "bootstrap-sprockets";
@import "bootstrap";
7.将visitor.coffee改成visitor.js，并定义app
var visitorCenter = angular.module('VisitorCenter', [‘ngResource']);
#ngresource 提供一个想 rails 中的 resources 的接口。

visitorCenter.factory("Visitor", function($resource) {
  return $resource("visitors/:id", { id: '@id' }, {
    index:   { method: 'GET', isArray: true, responseType: 'json' },
    update:  { method: 'PUT', responseType: 'json' }
  });
})
#让Angular JS 与 application 交互。

visitorCenter.controller("visitorsController", function($scope, Visitor) {
  $scope.visitors = Visitor.index()

  $scope.addVisitor = function() {
    visitor = Visitor.save($scope.newVisitor)

    $scope.visitors.push(visitor)
    $scope.newVisitor = {}
  }

  $scope.deleteVisitor = function(index) {

    visitor = $scope.visitors[index]
    Visitor.delete(visitor)
    $scope.visitors.splice(index, 1);
  }
})
#定义一个controller，告诉Angular JS 如何与我们的app交互。

8.编写views/xxx/index.html.erb
<div class="container" ng-app="VisitorCenter">
  <h1>Visitors</h1>

  <div ng-controller="visitorsController">
    <div class="well">
      <h3>Add a new Visitor</h3>
      <form ng-submit="addVisitor()">
        <div class="row">
          <div class="col-xs-6">
            <input type="text" ng-model="newVisitor.first_name" class="form-control" placeholder="First Name" />
          </div>
          <div class="col-xs-6">
            <input type="text" ng-model="newVisitor.last_name" class="form-control" placeholder="Last Name" />
          </div>
        </div>
        <div class="row">
          <div class="col-xs-12">
            <br />
            <input type="text" ng-model="newVisitor.reason" class="form-control" placeholder="Reason for Visit" />
          </div>
        </div>
        <div class="row">
          <div class="col-xs-12 text-center">
            <br />
            <input type="Submit" value="Add Visitor" class="btn btn-primary" />
          </div>
        </div>
      </form>
    </div>

    <h3>Currently Visiting</h3>
    <hr />
    <table class="table table-bordered table-striped">
      <thead>
        <tr>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Reason for Visit</th>
          <th>&nbsp;</th>
        </tr>
      </thead>
      <tbody>
        <tr ng-show="!visitors.length">
          <td colspan="4">No visitors in the building.</td>
        </tr>
        <tr ng-repeat="visitor in visitors">
          <td>{{ visitor.first_name }}</td>
          <td>{{ visitor.last_name }}</td>
          <td>{{ visitor.reason }}</td>
          <td><a class="btn btn-danger" ng-click="deleteVisitor($index)">Remove</a></td>
        </tr>
      </tbody>
    </table>

  </div>
</div>
复制代码实作第一个angular JS的测试。
参考地址：richonrails angular rails 实作、Angular JS Rails Gem Homepages 、Angular JS Homepage
遇到的问题：
1.gem版本有冲突。解决方案：删除版本号。
2.手敲代码时，定义Visitor的要素时，拼写错误。
———————————————————————2018-2-5———————————————————————
—————————————2018-2-6————————————-—
学习内容：
Ruby方法拆解：
1.方法的定义：
方法是有对象定义的与该对象相关的操作。在Ruby中，对象的所有操作都被封装成方法。
2.方法的简单调用：
对象.方法名(参数1，参数2，…,参数n)。
上面的对象被称为接受者，调用方法的过程被称为向对象发送消息。返回的结果是就是对象接收了消息。
2.1.运算符形式的方法调用：
Ruby中有些方法看起来很像运算符。如：二元运算符、-、散列的元素下标的[] 等，实际上都是方法。
3.方法的分类：
3.1.实例方法：
假设有一个对象（实例），那么一这个对象为接收者的方法就被称为实例方法。
3.2.类方法：
接受者不是对象而是类本身是的方法，就是类方法。例如我们在创建对象时就用到了类方法。如：
File.open(“some_file”)、Array.new、Time.now
此外，不直接对实例进行操作，只是对该实例所属的类进行相关操作时，我们也会用到类方法。如：
File.rename(oldname, new name)  #修改文件名
调用类方法是，可以使用::代替. 。
3.3.函数式方法：
没有接受者的方法，我们称之为函数式方法。确切的说是可以省略接受者。
4.方法的定义：
方法有多个参数时，从参数列表的右边开始依次指定默认值。
4.1.方法的返回值：
我们可以用return指定方法的返回值。如果省略return语句时，这个方法的最后一个表达式就是返回值。
正常情况下，return好像没有机会使用，但在某些情况下，我们会希望马上终止程序，这时就用到了return。如：
def max(a, b)
	if a > b
		return a
	end
	b
end
p max(10, 5) # => 10
如果省略return的参数，程序则返回nil。
4.2.参数个数不确定的方法：
通过使用“*变量名”的形式来定义参数个数不确定的方法，Ruby就可以把所有参数封装为数组，供方法内部使用。
还可使用“**变量名”的形式来定义，将未定义的变量以散列的对象形式保存。
4.3.补充：
如果参数为数组时，会将数组的每个元素拆解出来，然后传进去。

遇到的问题：
为什么修改文件名是一个类方法呢？因为文件名并不是某个文件的属性，是一个类的属性？
并不是很清楚，需要拓展阅读文件的资料。
总结：
根据拆解2的理解，没有对象是否无法使用方法？
拆解3.2的类方法，终于明白::的意思了,即是“.”的意思。
拆解3.3的函数式方法，是否可以理解为接收者为计算机本身，所以可以省略。如：
print、sleep

———————————————————————2018-2-6———————————————————————

—————————————2018-2-7————————————-—
学习内容：
1.Action Controller 概览
Action Controller 是MVC中的C（控制器）。路由器决定使用哪个控制器处理请求后，控制器负责解析请求，生成相应的输出。
1.1. 参数
控制器的动作中，往往需要获取用户发送的数据或其他参数。在web中参数分为两类。第一类随URL发送，叫做“查询字符串参数”，即URL中？符号后面的部分。第二类经常称为“POST数据”，一般来自用户填写的表单。而在rails中，不区分这两种参数，都可以通过params散列获取。
1.2.会话
应用中的每一用户都有一个会话（session)，用于存储少量数据，再多次请求中永久存储。绘画只能在控制器和视图中使用，可以通过以下几种存储机制实现：
ActionDispatch::Session::CookieStore: 所有数据都存储在客户端
ActionDispatch::Session::CacheStore: 数据存储在Rails缓存里
ActionDispatch::Session::ActiveRecordStore: 使用Active Record把数据存储在数据库中（需要使用 active-session_store gem）
所有存储机制都会用到一个 cookie，存储每个会话的ID (必须使用cookie， 因为Rails 不允许在URL 中传递会话ID,这么做不安全）。
1.2.1访问会话：
可以通过实例方法session访问会话。
class ApplicationController < ActionController::Base
 
  private
 
  def current_user
    @_current_user ||= session[:current_user_id] &&
      User.find_by(id: session[:current_user_id])
  end
end
把数据存入会话：
class LoginsController < ApplicationController
  # “创建”登录，即“登录用户”
  def create
    if user = User.authenticate(params[:username], params[:password])
      # 把用户的 ID 存储在会话中，以便后续请求使用
      session[:current_user_id] = user.id
      redirect_to root_url
    end
  end
end
#购物车的原理。删除会话时，需重新定义一个方法：
@_current_user = session[:current_user_id] = nil 
1.2.2 闪现会话：
闪现消息可用于报错信息或是flash提示功能。且只有下一个动作才能处理前一个动作设置的闪现消息。一般会在布局中加入闪现消息：
    <% flash.each do |name, msg| -%>
      <%= content_tag :div, msg, class: name %>
    <% end -%>
如果希望闪现消息保留到其他请求，可以使用keep方法：
def index
	flash.keep
end
如果希望闪现消息在同一个请求中，可以使用:
flash.now[:error] = “balabala”
1.3 cookies：
cookies的使用方法和 session差不多。
class CommentsController < ApplicationController
  def new
    # 如果 cookie 中存有评论者的名字，自动填写
    @comment = Comment.new(author: cookies[:commenter_name])
  end
 
  def create
    @comment = Comment.new(params[:comment])
    if @comment.save
      flash[:notice] = "Thanks for your comment!"
      if params[:remember_name]
        # 记住评论者的名字
        cookies[:commenter_name] = @comment.author
      else
        # 从 cookie 中删除评论者的名字（如果有的话）
        cookies.delete(:commenter_name)
      end
      redirect_to @comment.article
    else
      render action: "new"
    end
  end
end


参考资料：ruby china controller 概览

遇到的问题：
1.写好后一直报错：
undefined method ‘respond_to’ … Did you mean? respond_to?
分析原因：Rails 4.2版本后，不再支持这个功能。通过使用 gem ‘responders' 可以很容易引用之前的类。而之前没有报错，原因可能是因为之前使用devise的gem，而devise也引用了这个方法。
2.一直找不到数据库中的数据：
原因：进错了数据库。

参考资料：ruby china 4.2 版本修正

总结：
1.在使用Angular JS时，index方法并没有使用数据库中的数据？因为在数据库中直接新增的数据并没有显示出来。

———————————————————————2018-2-7————————————————————————————————————2018-2-8————————————-—
学习内容：
1.action controller 中的cookies
注意，删除会话中的数据是把键的值设为nil,但若想删除cookie中的值，要使用cookies.delete(:key)方法。
2.渲染XML和JSON数据：
class UsersController < ApplicationController
  def index
	@users = User.all
	respond_to do |format|
	  format.html #index.html.erb
	  format.xml { render xml: @users }
	  format.json { render json: @users }
	end
  end
end
其中使用的是 render xml: @users 而不是 render xml: @users.to_xml。 如果不是字符串对象，Rails会自动调用to_xml 方法。
3.过滤器：

class ApplicationController < ActionController::Base
  before_action :require_login
 
  private
 
  def require_login
    unless logged_in?
      flash[:error] = "You must be logged in to access this section"
      redirect_to new_login_url # halts request cycle
    end
  end
end
其中过滤器就是before_action 。因为其中重新定向到登陆表单页面。如果前置过滤器渲染页面或者做了重新定向，动作就不会运行。如果要跳过某个动作，可以使用skip_before_action :require_login, only: [:new, :create]
4.请求伪造防护：
跨站请求伪造（Cross-Site Request Forgery，CSRF）是一种攻击方式，A网站的用户伪装成B网站的用户发送请求，在B站中添加、修改或删除数据，而B站的用户浑然不知。防范措施：1）.所有破坏性动作都使用POST请求；2）.添加一个只有服务器才知道的难以猜测的令牌。如果请求中没有正确的令牌，服务器会拒绝访问。
<%= form_for @user do |f| %>
  <%= f.text_field :username %>
  <%= f.text_field :password %>
<% end %>
会看到Rails自动添加了一个隐藏字段，用于设定令牌：

<form accept-charset="UTF-8" action="/users/1" method="post">
<input type="hidden"
       value="67250ab105eb5ad10851c00a5621854a23af5489"
       name="authenticity_token"/>
<!-- fields -->
</form>
多数表单的辅助方法都会有这样一个令牌，如果想自己编写表单，或者基于其他原因想添加令牌，可以使用 form_authenticity_token方法。

参考资料：https://ruby-china.github.io/rails-guides/action_controller_overview.html
更多资源：
cookies： http://api.rubyonrails.org/v5.1.1/classes/ActionDispatch/Cookies.html
respond： http://api.rubyonrails.org/v5.1.1/classes/ActionDispatch/Response.html
request： http://api.rubyonrails.org/v5.1.1/classes/ActionDispatch/Response.html

5.Angular JS 注入依赖：
依赖注入（Dependency Injection， 简称DI)是一种软件设计模式，在这种模式下，一个或更多的依赖（或服务）被注入（或者通过引用传递）到一个独立的对象（或客户端）中，然后成为了该客户端状态的一部分。
Angular JS 提供5个核心组件用来作为依赖注入：
value:Value是一个简单的javascript对象，用于向控制器传递值（配置阶段）：
// 定义一个模块
var mainApp = angular.module("mainApp", []);

// 创建 value 对象 "defaultInput" 并传递数据
mainApp.value("defaultInput", 5);
...

// 将 "defaultInput" 注入到控制器
mainApp.controller('CalcController', function($scope, CalcService, defaultInput) {
   $scope.number = defaultInput;
...
factory: factory是一个函数用于返回值（有点拗口）。在service和controller需要时创建。通常我们使用factory函数来计算或返回值。
// 定义一个模块
var mainApp = angular.module("mainApp", []);

// 创建 factory "MathService" 用于两数的乘积 provides a method multiply to return multiplication of two numbers
mainApp.factory('MathService', function() { //定义MathService 为一个方法。
   var factory = {}; //定义个变量 factory 
   
   factory.multiply = function(a, b) {
      return a * b
   }
   return factory;  //返回一个变量
}); 

// 在 service 中注入 factory "MathService"
mainApp.service('CalcService', function(MathService){ //将MathService这个方法作为参数传入方法中
   this.square = function(a) {
      return MathService.multiply(a,a);
   }
...

service:
provider: provider 创建一个service、factory等（配置阶段）。Provider中提供一个factory方法 get()， 它用于返回 value/service/factory。
constant: constant（常量）用来在配置阶段传递数值，注意这个常量在配置阶段是不可用的。
遇到的问题：
总结：
1.读取cookies其实就是hash的添加、读取与删除。
2.学习内容5中，注入value相当于定义一个局域变量。
angularJS 是否可以理解成 将div、controller以及前段页面打包进了一个div中。在div中调用app中定义的变量。
其中的service 理解为运行一个服务。
———————————————————————2018-2-8————————————————————————————————————2018-2-10———————————-—
学习内容：
1.按关联表的数量来排序：
如何使用链接表中的joins 或 left_outer_joins：
@posts = Post.left_outer_joins(:votes).group('posts.id').order("count(votes.user_id) DESC”)
# 其中 post user是多对多的关系，中间表是 votes
2.joins 与 left_outer_joins 的区别：
如果想要选择一组记录，而不管它们是否具有关联记录，可以使用 left_outer_joins 方法。
而joins的方法返回的值只为有关联记录的。

参考资料：rails guidle 资源
参考资料：over_flowr资源
遇到的问题：
在按关联表的数量来排序时，使用includes是无效的。之前尝试时，是使用group(‘votes.post_id’),这样只返回两条记录，想再想来，之所以会产生这个问题是因为这样分组是按有选票和没有选票分组，所以只选出两条记录。
总结：

———————————————————————2018-2-10————————————————————————————————————2018-2-11———————————-—
学习内容：
1.Learn to Build Modern Web Apps with AngularJS and Ruby on Rails
The $scope variable serves as the bridge between Angular controllers and Angular templates. If you want something to be accessible in the template such as a function or variable, bind it to $scope。
$scope变量是controller和Angular templates(表单）之间的桥梁。如果想将一些方法、变量传入template，就要绑定$scope。不过要通过controller 和 app 。
遇到的问题：
点击链接时，并没有真的生成一个页面，而是生成一个URL。不知道是自己做错了，还是因为本来就是这个设定。
页面没有变化，原因是引用CDN的时候，网页没有写：http:
总结：
1.angular 中的比较相等使用三个等号（===）
2.angular中定义方法时，如需传入参数，不用在方法名称后面写（），只需要在function（*arg）{. . . }

———————————————————————2018-2-11————————————————————————————————————2018-2-12———————————-—
学习内容：
1.Creating Angular Services:
angular JS 的文件structure
高级结构：

遇到的问题：
1.引用路径（ui-router）后，不能添加post了，确切的说是controller失效了。但是并没有查出原因。
总结：
1.factory中定义一个变量为区域变量。其他的angular都可以call。
2.使用config配置路径，要自定义url、templateUrl、controller:
.config([‘$foo, $foo1’, bar($foo, $foo1) {
$foo.state(‘home’, {
url: ‘/home’,
templateUrl: ‘/home.html’,
controller: ‘someController’
});
$foo1.otherwise(‘home’);
}])


———————————————————————2018-2-12————————————————————————————————————2018-2-23———————————-—
学习内容：
Angular on rails 
遇到的问题：
1.bootstrap col-md-6 col-md-offset-3 not work。原因是在bootstrap4中，做了一些修改。应写成 offset-md-3 col-md-6。
2.bower install angular angular-ui-router bootstrap —save后 不能正确解析url。原因可能是ui-route的新版本有一些修改。在href中加一个！后，问题解决了。
<a href=“#!/posts/{{$index}}”>Comments</a>
解决过程参考home的网址，及Easier AngularJS Routing with Angular UI Router。
3.不能读取templateUrl的html文件，原因是不能写script。但这个方法之前尝试过，并没有生效，于是认为是自己写错了。经过对比“智审”的代码，发现错位的原因。也不排除是版本的问题。下一次尝试便知。
总结：
1.之前2018-2-12遇到的问题，想到了原因，可能是因为bower没有安装正确，且安装后没有按照顺序输入命令。在第二次重做时，问题就不存在了。正确的操作顺序：
1.bower init
2.created .bowerrc file 修改配置。
{
  "directory":"vendor/assets/bower_components"
}
3.bower install angular angular-ui-router bootstrap —save
2.之前遇到过一个无法引用controller的问题，原认为是config与controller的顺序错误，后经尝试与顺序无关。盖因自己的application.html.erb文件中的script写错了位置。复制代码后，问题不见了。
———————————————————————2018-2-23————————————————————————————————————2018-2-24———————————-—
学习内容：
Angular on rails 
遇到的问题：
1.在使用angular API时，一直报错：
$http.get(…).success is not a function
错误代码：
    return $http.get('/posts.json').success(function(data){
      angular.copy(data, o.posts);
    });
原因：angular 1.6之后就讲success改成了then()。
而修改之后，内置参数也发生了变化。代码如下：
    return $http.get('/posts.json').then(function(response){
      angular.copy(response.data, o.posts);
    });
上述代码分两部分，第一部分是后端命令（index），第二部分是前端命令（显示请求的数据）。
2.bootstrap not display ,原因：引用的bootstrap文件中没有定义请求class的参数。使用bootstrap gem 后可以显示。
引出一个问题，在刚开始引用文件时，出现问题，究竟是哪一步让引用出现了冲突？
总结：
angular.copy(foo, bar);
这行代码是将foo的值，赋给bar 。经次教训，应该细看教材代码，切勿走马观花。
———————————————————————2018-2-24————————————————————————————————————2018-2-26———————————-—
学习内容：
Angular JS 实作flapper News 项目（copy reddit)总结。
遇到的问题：

总结：
1.$http 
1) The $http service is a core AngularJS service that facilitates communication with the remote HTTP servers via the browser's XMLHttpRequest object or via JSONP.
（$http 服务是Angular JS 服务中的核心服务，经由浏览器的 XMLHttpRequest 对象或者经由 JSONP 加快与远端HTTP服务的交互.）
The $http service is a function which takes a single argument — a configuration object — that is used to generate an HTTP request and returns a promise .

案例代码:
$http({
  method: 'GET',
  url: '/someUrl'
}).then(function successCallback(response) {
    // this callback will be called asynchronously
    // when the response is available
  }, function errorCallback(response) {
    // called asynchronously if an error occurs
    // or server returns response with an error status.
  });
response 对象可调用的方法/对象：data config headers status xhrStatus statusText 。 

$http.get('/someUrl', config).then(successCallback, errorCallback);
$http.post('/someUrl', data, config).then(successCallback, errorCallback);  //其中data为需要改动的对象(Request content)。
修改$http 的配置：$http(config).then(. . . )
var req = {
 method: 'POST',
 url: 'http://example.com',
 headers: {
   'Content-Type': undefined
 },
 data: { test: 'test' }
}

$http(req).then(function(){...}, function(){...});
2.angular.copy :
之前总结过，angular.copy(arg1, arg2), 是将arg1，赋值给arg2。如果arg1为null, 可写成angular.copy(arg2)，这时是将arg2赋值为null。
3.angular JS $templateCache：
$templateCache is a Cache object created by the $cacheFactory.
定义 templateCache :
var myApp = angular.module('myApp', []);
myApp.run(function($templateCache) {
  $templateCache.put('templateId.html', 'This is the content of the template');
});
or get it via the $templateCache service:
$templateCache.get(‘templateId.html') 
$cacheFactory(cacheId, [options]) 的返回值：
{object} info() — Returns id, size, and options of cache.
{{*}} put({string} key, {*} value) — Puts a new key-value pair into the cache and returns it.
{{*}} get({string} key) — Returns cached value for key or undefined for cache miss.
{void} remove({string} key) — Removes a key-value pair from the cache.
{void} removeAll() — Removes all cached values.
{void} destroy() — Removes references to this cache from $cacheFactory.
4.factory service vs provider :
factory service 的用法基本相同，只是定义是有些差别。而provider的区别则是在app.config()中进行定义，而定义的方法也有很大的不同（代码如下）。
       this.thingFromConfig = '';

        this.$get = function ( $http, $q ) {
            return {
                setArtist: function ( artist ) {
                    _artist = artist;
                },
                getArtist: function () {
                    return _artist;
                },
                callITunes: function () {
                    var deferred = $q.defer();
                    _finalUrl = makeUrl();

                    $http({
                        method: 'JSONP',
                        url: _finalUrl
                    }).success(function ( data ) {
                        deferred.resolve(data);
                    }).error(function ( error ) {
                        deferred.reject(error);
                    });

                    return deferred.promise;
                },
                thingOnConfig: this.thingFromConfig
            };
        };


———————————————————————2018-2-26————————————————————————————————————2018-2-27———————————-—
学习内容：
1.angular-rails（getting-started-with-rails）：
a file application.js with //= require_tree . to restore the default behavior of the javascripts folder.
所以需要在application.html.erb文件中要加
<%= javascript_include_tag 'application' %> 这样一行。其中逻辑是这样的，这行代码引用application.js文件。而application.js则会引用app.js文件。
2.angular-rails（wiring-everything-up）前后端交互应用中resolve：
By using the resolve property in this way, we are ensuring that anytime our home state is entered, we will automatically query all posts from our backend before the state actually finishes loading.

遇到的问题：
1.在application.html.erb文件中，并不需要引用app.js资源。为什么？
总结：



———————————————————————2018-2-27————————————————————————————————————2018-2-28———————————-—
学习内容：
1.angular-rails（adding-user-authentication-with-devise）
遇到的问题：
1.前端报错：Possibly unhandled rejection，于是搜索发现可能是
“happened the same upgrading from 1.5.8 to 1.5.9 ”的原因，于是修改angular配置如下：
app.config(['$qProvider', function ($qProvider) {
    $qProvider.errorOnUnhandledRejections(false);
}]);
前端不再报错了，但是后台依然报错：
NoMethodError (undefined method `for' for #<Devise::ParameterSanitizer:0x007f8369977b58>
Did you mean?  fork):
再次搜索发现，是因为rails 5 版本导致的问题，application_controller.rb文件的配置已经不使用for了。
devise_parameter_sanitizer.permit(:sign_up, keys: [:username])
于是问题经过测试发现，与前端不无联系。
参考文档：devise strong_parameter
2.序列化数组报错：
 ‘ActiveRecord::SerializationTypeMismatch’
尝试各种方法皆报错。原因在设定字段时只能使用text格式，其他格式无效。
参考资料：thelazylog
总结：
1.经查看$qProvider文档，$qProvider是一个让报错（是否）手动显示的方法。
官方文档：Retrieves or overrides whether to generate an error when a rejected promise is not handled. This feature is enabled by default.

可以这样使用：
app.config(['$qProvider', function ($qProvider) {
    $qProvider.errorOnUnhandledRejections(false);
}]);
//关掉显示报错。
参考文档：provider api 解释
2.如果想将关联的记录同时删除，可以使用：
class Post < ApplicationRecord
  has_many :comments, dependent: :destroy
end
//这样就将post关联的comments删除了。

———————————————————————2018-2-28————————————————————————————————————2018-3-01———————————-—
学习内容：
1.angular-rails（associating-users-with-posts-and-comments）的熟练练习：
1.Only allow users to vote once
2.Implement a 'downvoting' feature
3.Display the number of comments next to each post on the main page.
4.Database/Form validations and error handling.
遇到的问题：
在实作投票时，可以使用得到后台的数据。但是不能返回一个json，经过多次尝试对比发现，put的路由方法不能得到返回值，于是将路径换成post。但是紧接着发现了另一个问题，那就是有嵌套关系时，需将上级的关联对象同时返回才能得到返回值。
总结：


———————————————————————2018-3-01————————————————————————————————————2018-3-06———————————-—
学习内容：
工作：将一个表格，在打印预览中显示。
遇到的问题：
document.getElementsByClassName(‘signatoryBox’)，无法出现在angular.controller中，经过查阅api，需将其写在function中，才可以调用：
$scope.object = angular.element(window.document.getElementsByClassName
('signatoryBox'))[0].innerHTML;


———————————————————————2018-3-06————————————————————————————————————2018-3-27———————————-—
学习内容：
学习angular with rails
遇到的问题：
在添加评论时，无法在后台传输数据成功后，无法更新前端。经尝试没有找到方法，后阅读原来代码，找到方法，在更新前端时，需找到前端定义的对象。本案例中为： $scope.post = post，所以在传参数时，即可将post直接传进需要调取的方法即可得到所有的评论，然后只需push即可。
总结：
在使用angular JS 时，调用的顺序为app -> config -> controller -> factory 基本与rails相似。
———————————————————————2018-3-27———————————————————————
—————————————2018-3-28———————————-—
学习内容：
1.angularJS-$http：

遇到的问题：

总结：
1.$http：
$http是一个方法，被用于生成一个HTTP请求，然后立即返回一个响应，成功或者失败。
用法：
在controller中引用$http。具体用法如下：
$http.get('/someUrl', config).then(successCallback, errorCallback);
$http.post('/someUrl', data, config).then(successCallback, errorCallback);
$http的快捷方法一共七个。分别是：get head post put delete jsonp patch。
var req = {
 method: 'POST',
 url: 'http://example.com',
 headers: {
   'Content-Type': undefined
 },
 data: { test: 'test' }
}
$http(req).then(function(){...}, function(){...});
其中headers为浏览器编译对象。（暂时先这样解释）。
2.cacheFactory：
cacheFactory是一个方法，用于搭建缓存对象，并提供一个接口。
用法：
$cacheFactory(cacheId, [options]);
返回值：
一个对象、一对key-value、一个value、移除一对key-value、删除整个cache。
具体用法：
在controller中引用，有三个可调用方法：
info()-查看cache信息; get()-当cache被创造时使用; put()-被用于返回一个值;
3.rootScope:
所有应用都有一个$rootScope，它可以作用在ng-app指令包含的所有HTML元素中。$rootScope可作用于整个应用中。是各个controller中scope的桥梁。用rootscope定义的值，可以在各个controller中使用。
4.angular-ui-route：
使用方法：
angular.module("myApp", ["ui.router"]).config(function($stateProvider){
    $stateProvider.state(stateName, stateConfig);
})
$stateProvider：
stateName相当于action；
stateConfig中的表单定义：template-一个HTML字符串,templateUrl-一个URL的文件路径;templateProvider-一个方法，返回一个HTML内容的字符串。
stateConfig中的resolve：一个被注入controller依赖的映射。keys-注入controller的依赖命名。factory-「字符串|方法」，如果是方法，将被注入然后作为依赖的返回值。如果结果是一个应答，将在值被注入controller前响应。（如果不需要引用，可以不注入controller？）
stateConfig中的onEnter和onExit：是一个回调，也可以接入所有resolved的依赖。
$urlRouterProvider:
跳转方法。
用法：
$urlRouterProvider.when(whenPath, toPath)
$urlRouterProvider.otherwise(path)
directives:
ui-view：这个命令告诉$state哪里应该替换你的templates。view可以不命名可以命名。
ui-sref:绑定链接的命令。
ui-sref的Usage:
ui-sref=‘stateName’;ui-sref=‘stateName({params: value, param: value})’
$state:
用法：
$state.go(to [, toParams] [, options])
$state.reload()：
强制重新载入当前页。

———————————————————————2018-3-28————————————————————————————————————2018-3-29———————————-—
学习内容：
1.angular-devise：
Auth.currentUser（）：
返回一个应答注入当前用户，有三种可能发生的情况：
1）Auth有一个已认证的用户，将立即解析这个用户。
2）Auth没有认证的user，但是服务有一个之前认证过session，Auth将接受那个session，并且解析它的user，然后一个devise:new-session事件将当前用户作为参数进行广播。
3）Auth没有认证的user，且服务也没有认证的session。这时将拒绝应答。
代码如下：
angular.module('myModule', ['Devise']).
    controller('myCtrl', function(Auth) {
        Auth.currentUser().then(function(user) {
            // User was logged in, or Devise returned
            // previously authenticated session.
            console.log(user); // => {id: 1, ect: '...'}
        }, function(error) {
            // unauthenticated error
        });
    });


———————————————————————2018-3-29————————————————————————————————————2018-4-23———————————-—
学习内容：
XML：
总结：
xml是一种标记语言。
标记指计算机所能理解的信息符号，通过此种标记，计算机之间可以处理包含各种信息的文章等。如何定义这些标记，既可以选择国际通用的标记语言，比如HTML,也可以使用像XML这样由相关人士自由决定的标记语言，这就是语言的可扩展性。
xml用途。
XML设计用来传达及携带数据信息，不用来表现或展示数据，HTML则用来表现数据，所以XML用途的焦点是它说明数据是什么，以及携带数据信息。
ruby on rails 中创建xml数据
1.gem install builder
2.    require 'builder'
    xml = Builder::XmlMarkup.new(:target =>$stdout,:indent => 1)
    # :target =＞$stdout 参数：指示输出内容将被写向标准输出控制台
    # :indent =＞1 参数：XML输出形式将被缩进一个空格字符
    # x.comment! "书本信息" # <!-- 书本信息 -->
    xml.instruct!# <?xml version="1.0" encoding="UTF-8"?>
    xml.s(:Envelope,"xmlns:s"=>"http://schemas.xmlsoap.org/soap/envelope/"){
        xml.s(:Body){
            xml.Login(:xmlns=>'http://tempuri.org/'){
                xml.user "LoginName"
                xml.pw "LoginPw"
            }
        }
    }
    p xml #打印XML
3.输出结果
<?xml version="1.0" encoding="UTF-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
 <s:Body>
  <Login xmlns="http://tempuri.org/">
   <user>LoginName</user>
   <pw>LoginPw</pw>
  </Login>
 </s:Body>
</s:Envelope>
<inspect/>




———————————————————————2018-4-23———————————————————————
