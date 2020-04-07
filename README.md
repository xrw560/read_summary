# read_summary

1. 配置npm国内源，在用户目录下新建`.npmrc`文件，内容:



```shell
registry=https://registry.npm.taobao.org
```
2. 由于使用gitbook install 安装很慢，建议使用`npm init`初始化一个package.json文件，然后每个包通过npm命令安装，以后就可以通过npm install一键快速安装依赖包了。

```shell
npm install gitbook-plugin-anchor-navigation-ex
npm install gitbook-plugin-page-treeview
npm install gitbook-plugin-prism
npm install gitbook-plugin-search-pro
npm install gitbook-plugin-simple-page-toc
npm install gitbook-plugin-splitter
npm install gitbook-plugin-tbfed-pagefooter
npm install prism
```

