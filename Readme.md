# Readme

本项目采用vscode配置gcc环境进行编译，读取、存储文件均使用相对路径，因此您可以在任何地方解压并运行。

用vscode打开code文件夹，终端输入“make”（已有makefile），生成test.exe, 然后终端输入“./test”即可运行

#### 说明

1. 考虑到莎士比亚的文集有限，可以采取静态索引来节省项目搜索时间。项目开始时，文件夹里不会有`word.txt`，在第一次运行之后，会自动生成`word.txt`文化用于静态倒排索引。为加快搜索速度，之后的搜索都会基于读取静态索引来进行。
2. 为消除网络环境对于搜索爬虫速度影响，我们率先将莎士比亚文集所有文章爬了下来并存在了`full`文件夹下，因此程序可以在未连接互联网的地方运行。

# search-engine
