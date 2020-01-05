# 项目说明
- Koa + ts

## 热更新
- 在package.json的scripts处添加如下内容
```js
"watch-server": "nodemon --watch 'src/**/*' -e ts,tsx --exec 'ts-node' ./src/server.ts"
```