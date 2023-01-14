原生js实现网络接口请求，不依赖任何三方框架

# 快速使用
### 第一步，引入 request.js 

````
<script src="https://res.zvo.cn/request/request.js"></script>
````

### 第二步，一行代码使用

##### GET请求
````
request.get('http://www.leimingyun.com',{}, function(data){
	//接口返回值
	console.log(data);
});
````

##### POST请求
````
//接口请求的参数
var params = {
	'author':'guanleiming',
	'site':'www.guanleiming.com'
}
request.post('http://www.leimingyun.com',params, function(data){
	//接口返回值
	console.log(data);
});
````
