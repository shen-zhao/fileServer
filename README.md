### 文件服务器[Fork by holyzfy](https://github.com/holyzfy)

1.在fileServer目录下运行`npm install`

2.修改`/config/local.json`

```
{
    // 端口
    "port":3000,
    // 服务器根目录，请填写绝对路径(在想启动服务的目录下运行pwd获取路径)
    "webapps": "F:/f2e",
    "vm": [],
    // 响应头
    "responseHeaders": {
        "Cache-Control": "no-cache, no-store, must-revalidate",
        "Pragma": "no-cache",
        "Expires": "0"
    }
}
```

3.运行`node server.js`，在浏览器打开`localhost:3000`;