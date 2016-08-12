##编写一个gulpfile.js文件，实现以下功能

1. 把app下所有的html拷贝到dist下面
2. 把app/js下所有的除了名字叫test.js之外的js文件全部合并并压缩后保存到dist/js目录下
3. 把app/less下所有的less文件全部编译成css，并合并并压缩后保存到dist/css目录下
4. 把app/imgs下所有的jpg和png图片全部压缩后保存到dist/imgs目录下
5. (选做)在拷贝到dist目录下面的html文件中增加引用合并压缩后的js和css文件.
6. 编写一个web服务器可以实时预览dist目录下面的项目文件，并在app目录下文件内容修改后可以实时刷新浏览器看到最新的结果. 