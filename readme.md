# 博客文档

基于swagger-ui构建，来展示以及测试API接口

## 目录结构

```md
├── node_modules/ 第三方库引用
├── index.html
├── src
│   ├── ... 其它单元文档
│   └── index.json 主文档
└── readme.md
```

## 选择BootCDN加载swagger-ui-dist

由于穷的一比，没钱提升服务器的带宽，导致加载一个1M的文件都得10s，这完全不能忍。。。