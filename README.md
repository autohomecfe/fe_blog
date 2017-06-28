## 新养车之家

当前版本v1.0版本

### 项目文件的划分：

```
├── bin/     启动目录
├── build/   webpack配置目录
├── src/ 前端文件目录
    ├── api/    api接口目录
    ├── assets/ 静态文件目录（sass、images）
    ├── components/ 组件文件目录
    ├── filters/ 过滤器文件目录
    ├── tool/ 工具方法目录
    ├── router/  路由文件目录
    ├── views/   vue模板文件
    ├── vuex/    vuex相关文件

	
前端框架： Vue2.1.0

后端服务器：Node6.3

自动化构建工具：webpack2.2.0 && gulp

```
**构建开发环境**

``npm run dev``

**对文件进行编译打包**

``npm run build``

**发布上传静态资源到测试CDN服务器，并添加域名**

``npm run deploy``（必须先执行npm run build命令）

**发布上传静态资源到正式CDN服务器，并添加域名**

``npm run build:deploy``（必须先执行npm run build命令）

**构建生产环境**

``npm run production``






 