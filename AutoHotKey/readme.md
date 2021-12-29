- AutoHotKey是一种脚本语言
  - 参考：[AutoHotkey新手入门](https://www.autoahk.com/archives/9458)

目前我最常用到的脚本是：
```shell
# 文件名是以 .ahk 结尾
CapsLock::Esc
Esc::CapsLock
```

该脚本的作用是：在Windows系统中，交换Esc与Caps两个键位。这样做是为了方便使用Vim（需要大量使用Esc,而Caps用的比较少，也可以用Shift+字母输入大写字母，所以做了交换）。

-- 21-12-29 日下午16:31</br>
学习到一个新的脚本：
```shell
#w::    ;;这里的 #->表示window键  w->表示字母w键					
WinMinimize,A    ;;最小化当前窗口		
return	   ;;结束代码段
```
该脚本的作用是：在Windows系统中，最小化当前窗口。
