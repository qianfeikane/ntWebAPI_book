# ntWebAPI 帮助文档

## Introduction

>[info] API请求时,需在**Headers**内加入access_token做验证,示例:  
```js
$.ajax({  
  type: "post",  
  dataType:"json",  
  url: "/iso/test",  
  data: { },  
  headers: {  
    Authorization: "bearer XXXXXX"  
  },  
  success: function (data, status) { }  
});
```

>[danger] 测试API可使用Postman工具,官网 [https://www.postman.com]()
