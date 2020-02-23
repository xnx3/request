纯JS，不依赖任何三方框架

# 快速使用
### 第一步，引入 request.js 
<script src="https://res.weiunity.com/request/request.js"></script>
### 第二步，一行代码使用

##### GET请求
````
request.get('http://www.leimingyun.com',{}, function(data){
	console.log(data);
});
````

##### POST请求
````
var params = {
	'author':'guanleiming',
	'site':'www.guanleiming.com'
}
request.get('http://www.leimingyun.com',params, function(data){
	console.log(data);
});
````
