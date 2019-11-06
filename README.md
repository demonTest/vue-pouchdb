#
测试 Vue pouchdb 工具

###  安装
```
npm install
npm run dev
```

### 使用技术
1. Vue + vue-router
2. PouchDB 前端存储
3. ECharts 图表展示

### 注意点
1. 由于是Vue的项目，因此需要在服务器上才能运行。
2. PouchDB 由于为前端存储（IndexedDB），因此一个域名对应一个数据库。所以当换浏览器或换地址时，数据会丢失（因为没有数据库）。
  - 数据库的查看可以利用F12进行查看
