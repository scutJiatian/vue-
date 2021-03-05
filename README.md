# vue-
以webpack配置为基础开发

利用知乎日报的接口开发的web app，连接后台数据只需执行proxy.js转发代理文件即可
首先安装所有依赖
npm install

启动项目.
启动代理服务 解决跨域资源问题:
node proxy.js  
终端会提示
接口代理运行在 http://127.0.0.1:8010/
图片代理运行在 http://127.0.0.1:8011/
说明启动成功

接下来启动前端dev-server
npm run dev
即可使用
