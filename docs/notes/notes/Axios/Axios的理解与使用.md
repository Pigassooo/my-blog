# Axios的理解与使用

## 1. Axios是什么？

1. 前端最流行的 ajax 请求库
2. react/vue 官方都推荐使用 axios 发 ajax 请求
3. 文档: https://github.com/axios/axios

## 2. Axios的特点

1. 基于 xhr + promise 的异步 ajax 请求库
2. 浏览器端/node 端都可以使用
3. 支持请求／响应拦截器
4. 支持请求取消
5. 请求/响应数据转换
6. 批量发送多个请求
7. 自动转换 JSON 数据
8. 自动处理 HTTP 错误
9. 自动处理跨域请求

## 3.Axios的常用方法

1. axios(config)  通用/最本质的发任意类型请求的方式

```javascript
axios({
  method: 'get',
  url: '/user',
  params: {
    id: 123
  }
}).then(function (response) {
  console.log(response);
}).catch(function (error) {
  console.log(error);
});
```

2. axios(url[, config])  可以只指定 url 发 get 请求

```javascript
axios('/user', {
  method: 'get',
  params: {
    id: 123
  }
}).then(function (response) {
  console.log(response);
}).catch(function (error) {
  console.log(error);
});
```

3. axios.request(config)

