# koa-ts-starter

TypeScript + koa + eslint + prettier

## 项目结构

```
.
├── src
│   ├── controller      // controller层
│   ├── service         // service层
│   ├── routes.ts       // 路由
│   └── index.ts        // 项目入口index.js
├── ecosystem.config.js // pm2配置
├── nodemon.json        // nodemon配置
├── package.json
└── tsconfig.json
```

## 构建

- yarn build 或 npm run build

## 生产环境启动

- 生产环境使用 pm2 启动 可以达到负载均衡 执行：yarn pro 或 npm run pro （生产环境端口默认：8000）
