## Demo：使用GET方法获取数据

```javascript
// 加载request模块
var request = require('request');

// 构造请求内容
var req = {
	url: 'wwww.google.com/data.json',
	qs: {
		param1: '',
		param2: ''
	}
}

request.get(lcaApi, function (err, res, body) {
	if (err) {
		// err
		return ;
	}

	let data = JSON.parse(body);
}

```