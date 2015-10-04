新增了对X选择、粘贴的支持，如需使用，在执行fbterm之前需要设置环境变量 DISPLAY
例如：
```
export DISPLAY=":0"
```

ChangLog:
```
trunk:
2011-08-24:
	* lib/shell.cpp:
	修正复制时空白字符的处理方法，实现自动插入回车符

2011-08-22:
	* lib/shell.cpp:
	middleTextSelect():修复选择时候下标越界BUG
	增加X系统剪切板支持
	修复输入法切换时输出多余字符BUG
	更改切换编码键，由 [Ctrl]+[Alt]+[F1-F6] 改为 [Ctrl]+[Alt]+[F9-F12]

2010-10-5 version 1.7

```