# 发布方法

1. 使用gitbook.com：
   1. 部署于server：gitbook.com自动将网页部署于[https://ustc-sist-survival-manual.gitbook.io/ustc/](https://ustc-sist-survival-manual.gitbook.io/ustc/)
   2. pdf：在gitbook.comgitbook.com的右侧有一个大大的export as PDF。点击export as PDF - Entire space即可。
2. 本地生成：由于gitbook.com风格略丑且不方便定制，建议本地
   1. 安装gitbook
      1. 安装npm
      2. 安装gitbook（win10要求安装gitbook-cli，其他系统不确定）
      3. 为了生成pdf，需要安装calibre
   2. 浏览网页电子书：`gitbook serve`
   3. 生成静态网页：`gitbook build`
   4. 生成pdf：`gitbook pdf .`

