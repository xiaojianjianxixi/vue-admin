前后端完全分离--管理员端基于vue+element-ui+vue-cli3解决方案

```
部署步骤：

第一步（已安装，可略过）：安装git ,下载地址：https://git-scm.com/download/win，然后把C:\Program Files\Git\bin设置环境变量path

第二步（已安装，可略过）：https://nodejs.org/en/blog/release/v9.11.2/

第三步（已安装，可略过）：安装npm install -g @vue/cli，参考https://cli.vuejs.org/zh/guide/installation.html

第四步：下载tp5-api 代码，下载地址：https://github.com/xiaojianjianxixi/tp5new

第五步：配置config/database.php 数据库信息

第六步：本地hosts文件配置域名xxx.xxxx.com（域名根据自己喜好，与vue-admin对应即可），然后指向/public目录即可。

第七步：下载vue-admin 代码，下载地址：https://github.com/xiaojianjianxixi/vue-admin, 配置文件vue.config.js , src/config ,baseURL 根据自己需要更改

第八步：进入vue-admin 目录，依次npm install

第九步：开发模式 npm run serve

第十步：生产模式 npm run build ，把生成的代码放到/public 下，更名为vue-admin , 浏览器输入 api.hardphp.com/vue-admin ,账号admin，密码123456 即可。
