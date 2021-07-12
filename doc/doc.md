# post 表单提交

```js
ajax(url,{
    data: JSON.stringify(data), // 提交数据
    type: 'POST', // method
    contentType: 'multipart/form-data',
    processData: false, // 不转义 data 数据。
    dataType: 'json', // 预期服务器返回的数据类型
}) 

```


# post formData

```js
var formData = new FormData();
ajax(url,{
    data:formData, // 提交数据
    contentType: false, // 内容编码类型
    processData: false, // 不转义 data 数据。
    cache: false, // 设置为 false 将不缓存此页面
})
```