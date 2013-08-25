####插件简介:
一个为Sublime Text2而开发的JS+CSS批量压缩插件(需要Mono或.NET) 

####支持平台:
1. Windows (需要安装.net framework 3.5或以上版本)
2. Mac (需要安装Mono 2.x或以上版本)
3. Linux (需要安装Mono 2.x或以上版本)

####常见问题:
1. 如果使用过程中出现 "UnicodeEncodeError: 'ascii' codec can't encode characters" 的错误, 此问题可能是Sublime Test2的Bug, 请在Sublime Text2安装目录找到 "sublime_plugin.py" ,在import之后其它代码之前添加如下两行:

```python
	reload(sys)  
	sys.setdefaultencoding("utf-8")
```
