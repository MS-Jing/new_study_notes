# 前言

我们有时候通过vue init下载vue脚手架的时候会报错无法下载

，我们可以通过离线下载模板再用离线下载的模板进行创建脚手架项目

# 开始

+ github下载模板的地址`https://github.com/vuejs-templates/`
+ 选择下载你要安装的模板，然后解压放在你的用户目录(这个目录就是你win+R 输入cmd打开的那个目录)下的`.vue-templates`目录下
+ 然后再到你要创建项目的目录下：
  + 执行 `vue init webpack-simple project_name --offline`
  + webpack-simple：是你刚才下载的模板的名字
  + project_name：是你要创建的项目的名字
+ 完后就发现和vue init webpack project_name 一样了