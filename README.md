# vuemail

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### 本地仓库关联github上创建的远程仓库;

1. 在github上创建一个空的仓库;并复制这个仓库的地址;

2. 在本地电脑上创建了vuemail工程项目,执行如下命令

```
git remote add origin '远程仓库的地址'

git push -u origin master

```

### 划分目录结构：

#### assets: 资源，用来存放img和css文件
#### components:

     用来存放多个页面需要用到的组件；
     可以继续划分为:common和content这两个文件夹，common用于存放可以给其它项目用的组件；content用于存放这个项目自己所用的组件；
#### network
     用于存放和网络请求相关的封装

#### views: 
     每个大的页面，每个页面都是一个组件;
     可以按照模块进行继续的划分

#### store:
     共用的变量

#### router:
     用于存放路由的相关配置

#### common：
     抽取出来的公共的js文件;
