## 抢答器(Node)  
**技术：**  
react + antd + express + socket.io

**原理及使用说明：**  
* 登陆页：用户登录后信息存储在localStorage或者Cookie中，若已经登录过，则读取缓存自动登录。  
* 抢答页：点击抢答之后，发送请求到express程序中，express将用户信息记录缓存中，按钮失效。当管理员点击“开始抢答”时，按钮自动生效。    
* 结果页：查看抢答顺序，如果有新的记录，页面会自动更新。  
* 管理员页：工号和姓名均输入“baiji”，即可进入管理员页面。点击开始时，会清除之前的无效数据，所有用户的按钮自动生效。  