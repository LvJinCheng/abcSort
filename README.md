# 原生JavaScript仿通讯录排序（数据）
* 此方法只操作数据，通过改变获取到的原始数据的顺序和格式，实现排序功能；
* 适用于js模板引擎、angular、vue等动态循环加载数据；
* 由于拼音首字母排序方法和按字段排序方法的区别，分别封装了两个函数：
```javascript
  ABCSort(data)//按拼音首字母排序
  timeSort(data,timeStr)//按传入字段排序
```
* 处理前后的数据对比在PinYin.html中（也可打开控制台查看），详细注释在PinYin.js中
