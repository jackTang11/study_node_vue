### 初始化项目
1. 创建 server
   ```
   1. npm init -y
   2. 配置运行脚本 nodemon index.js
   3.
   ```
2. web
   ```
      vue create web
   ```
3. admin
   ```
      vue create admin
   ```
 ### 基于element 后台基础界面搭建
cd admin
+ vue add element
+ vue add router
+ 创建 main.vue
+ 在router 中修改路由为main

### 配置之后，在其他地方可以直接使用
```
import http from './http'
Vue.prototype.$http = http

this.$http 的方式来引用
```
### 安装axios
```text
npm i axios
引用
import axios from 'axios'
```
