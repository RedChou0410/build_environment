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
