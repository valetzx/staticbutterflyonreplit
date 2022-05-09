## 说明
此仓库为[小康博客](https://www.antmoe.com/)魔改样式仓库.

 原版 ^ 
 
## 使用
下载此仓库到本地
在Replit部署：

个人版：

<a href="https://repl.it/github/valetzx/staticbutterflyonreplit">
  <img alt="Run on Repl.it" src="https://repl.it/badge/github/valetzx/staticbutterflyonreplit" style="height: 40px; width: 190px;" />
</a>

教育版：

将以下代码粘贴至Replit Shell后回车

`git clone https://github.com/valetzx/staticbutterflyonreplit && mv -b staticbutterflyonreplit/* ./ && mv -b staticbutterflyonreplit/.[^.]* ./ && rm -rf *~ && rm -rf staticbutterflyonreplit`

1. 安装扩展包
    `npm i`
    
2. 运行命令`npm run server`
    ~~此时通过浏览器访问`http://localhost:3000/css/style.min.css`即可看到生成的代码。~~
    
    通过访问你Replit生成的域名 DEMO：https://theme.pigp.repl.co/
    
    访问：`https://theme.pigp.repl.co/css/index.acfdffc3.css` 为主题样式代码。
    
3. 运行命令`npm run build`
    此时，就会在多出一个`dist`目录，里面就是构建出来的样式文件。
    
## 其他
~~`./src/css/config.less`文件为配置文件，部分设置可以直接通过设置进行修改。~~

原作者没更新，正在探索。

注入主题请在 butterfly 的 `_config.butterfly.yml` 寻找 `# Inject` 项目插入：

```
  head:
     - <link rel="stylesheet" href="https://theme.pigp.repl.co/css/index.acfdffc3.css">
```


