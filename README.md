# AIMLab 网站

## 一、项目操作
1. Clone 项目：

```
git clone git@git.coding.net:aimlab/aimlab.git
cd aimlab
```

2. 安装环境

```
brew install node # Mac 命令，已安装则跳过
npm install  # deps
```

3. 命令
```
grunt build   # 编译站点
grunt server  # 预览，http://localhost:8000
```

4. 更新站点
```
git add .
git commit -m "update log"
git push origin master
```

## 二、编辑内容

* 文档位于 `src/content`，目前有 `cn` 和 `en` 两个版本；
* 版本内部的目录名称与菜单一一对应，如中文版「动态」->「论文」，对应 `src/content/cn/news/01-paper.md`；
* 文档采用 markdown 编写，通过 `grunt build`命令，编译为页面；
* 小附件可以放到 `assets` 目录下，并在文档中提供链接供下载；
* Coding.net 限制 Pages 服务部署不超过 100MB，大附件最好通过网盘。



