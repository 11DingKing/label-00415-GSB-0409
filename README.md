# Ant Design Pro 管理后台

基于 Ant Design Pro 的企业级中后台前端解决方案。

## How to Run

### Docker 方式运行（推荐）

```bash
# 构建并启动服务
docker-compose up --build -d

# 查看日志
docker-compose logs -f

# 停止服务
docker-compose down
```

### 本地开发运行

```bash
# 进入项目目录
cd frontend-admin

# 安装依赖
npm install --legacy-peer-deps

# 启动开发服务器
npm start

# 或启动带 mock 数据的开发服务器
npm run dev
```

## Services

| 服务名称       | 端口 | 描述                    |
| -------------- | ---- | ----------------------- |
| frontend-admin | 8081 | Ant Design Pro 管理后台 |

## 测试账号

| 用户名 | 密码       | 角色     |
| ------ | ---------- | -------- |
| admin  | ant.design | 管理员   |
| user   | ant.design | 普通用户 |

## 题目内容

下载并运行 ANT DESIGN PRO

## 访问地址

- 管理后台: http://localhost:8081

## 技术栈

- React 19
- Ant Design 5.x
- Ant Design Pro Components
- UmiJS 4.x
- TypeScript

## 项目结构

```
label-00415/
├── frontend-admin/          # Ant Design Pro 管理后台
│   ├── config/              # 配置文件
│   ├── mock/                # Mock 数据
│   ├── public/              # 静态资源
│   ├── src/                 # 源代码
│   │   ├── components/      # 公共组件
│   │   ├── locales/         # 国际化
│   │   ├── pages/           # 页面
│   │   └── services/        # API 服务
│   ├── Dockerfile           # Docker 构建文件
│   └── nginx.conf           # Nginx 配置
├── docker-compose.yml       # Docker Compose 配置
├── .gitignore               # Git 忽略文件
└── README.md                # 项目说明
```

## License

MIT
