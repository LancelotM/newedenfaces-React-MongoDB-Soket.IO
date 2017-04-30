<h1>EVE Online 角色投票 demo</h1>
需要本地配置
    MongoDB
    Node.js
    Gulp
然后通过
    npm install 根据package.json，自动注入依赖包
    mongorestore characters.bson 向数据库中添加角色库 
    mongo 启动数据库
    glup 连接依赖文件、编译LESS样式并监视文件变化
    npm start 启动项目
效果预览
主页
<img src="Home.png">
角色
<img src="character.png">
<a href="http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio/">英文教程</a>
