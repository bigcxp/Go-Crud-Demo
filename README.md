# Go-Crud-Demo
Gin框架应用项目
***********
### 实现步骤
1. 创建目录结构
2. 下载依赖包
3. 创建数据库及表
4. 代码实现
----------
```

  ├── db
│   ├── IUser.go //数据库CURD接口设计
│   ├── User.go //用户数据结构对应user_tb表
│   ├── conn 
│   │   └── conn.go //创建数据库连接池
│   └── dao
│       └── userDao.go //对IUser接口实现类
├── go.mod
├── go.sum
├── httpServer
│   └── httpServer.go //处理http请求的类
├── main
│   └── main.go //主函数，程序入口
└── redisUtil 
     └── redisUtil.go //redis缓存工具类
     
```
