# Python PIL (Python Image Library) 命令执行漏洞 

## 原理

参考文章：

- https://github.com/neargle/PIL-RCE-By-GhostButt/blob/master/readme.md

## 测试

编译及运行测试环境：

```
docker-compose build
docker-compose up -d
```

访问 http://localhost:8000/ 上传 poc.png

![1.png](./1.png)

可以发现 payload 中的文件已经创建成功了。

![3.png](./3.png)



