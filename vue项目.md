## vue项目
1. 运行项目 
npm run serve 
2. 打包项目
npm run build 
运行完成后会多一个dist文件夹 这个是最后上线用的  要在服务端运行 
3. (额外)npm install 
http-server -g  global 全局  在文件夹下面运行http-server 自动把目录下的index.html 当做首页 
4. es6的模块语法  导出和引入的东西都是一个对象 moudle(对象) 
import 表示引入 必须是通过export导出的
export 表示导出 
export default 默认导出 
5. 我们可以把每个.vue文件看成一个组件 // @ is an alias to /src  @符号是/src的别名
6.组件的使用三部曲 
1） 通过import 引入组件
2)  在components里面注册
3） 用标签的形式使用
7. props传值默认值如果是数组或者对象的时候必须用函数
8.配置路由跳转
router-link 写完路径 配置rouer.js   

