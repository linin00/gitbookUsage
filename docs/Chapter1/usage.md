# 使用
1. 初始化 

新建文件夹，初始化：` gitbook init `

生成两个文件：` README.md ` -- 书籍介绍`SUMMARY.md`书籍的结构目录

2.生成目录结构

编辑 `SUMMARY.md`文件，如下

```
# 目录

* [前言](README.md)
* [第一章](Chapter1/README.md)
  * [第1节：衣](Chapter1/衣.md)
  * [第2节：食](Chapter1/食.md)
  * [第3节：住](Chapter1/住.md)
  * [第4节：行](Chapter1/行.md)
* [第二章](Chapter2/README.md)
* [第三章](Chapter3/README.md)
* [第四章](Chapter4/README.md)
```
再次执行`gitbook init` 自动生成文件目录结构

3. 部署

`gitbook serve` 部署到github前记得`gitbook build . docs`
