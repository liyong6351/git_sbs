# learngit
To learn git from zero

## gitbook 指令 

* gitbook init
* gitbook build
* gitbook serve
* gitbook 添加插件:在执行git init的目录新建book.json,添加

```
{
"plugins":[
        "mermaid-gb3",
        "toggle-chapters"
    ],
}
```
* 在启动时需要先安装插件，使用一下指令

npm install gitbook-plugin-toggle-chapters  
npm install gitbook-plugin-mermaid-gb3
