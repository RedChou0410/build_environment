# Build Environment

<br />

## 解决 Windows 版 Git 出现 templates not found 的问题

https://blog.csdn.net/sunux_sunux/article/details/52944807

找到 C:\Users\<登录用户名>\.gitconfig

指定 templates 位置

```
[init]  
templatedir=C:/Program Files/Git/mingw64/share/git-core/templates  
```

<br />

## git bash 在 gulp 運行 live-server 時, 無法用 ctrl + c 終止執行緒

Ctrl-C doesn't terminate process or clear the line

https://github.com/Tyriar/node-pty/issues/7

~~用 ctrl + z~~
> 無法停掉 web server, 可能是 windows 版本問題

改用 **cmder**

## gulp

install gulp
```
$ npm install --global gulp
```

透過 package.json 安裝 gulp 模組

```
$ npm install
```
