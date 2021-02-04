#Ubuntu, VSCode setting Clang-format

https://blog.csdn.net/mxdsdo09/article/details/108553327

一、在VSCode中下载内置的Clang-Format插件

二、本来以为这么简单就可以了，其实还要再安装一下clang-format

在命令行输入sudo apt-get install clang-format

三、设置自定义的.clang-format文件，并设置自动保存

创建.clang-format文件到工作目录下,insert the concents

自动保存的话，则是在上面的目录中的settings.json中，加入
```
    {
        "editor.formatOnSave": true
    }
```
