# Web-Crawler
# 基础篇

## 正则表达式 

### 正则表达式30分钟入门教程

- [三十分钟入门](http://deerchao.net/tutorials/regex/regex.htm "正则表达式30分钟入门教程")



### 正则语法速查


#### 元字符

##### 常用的元字符
	
| 代码        | 说明           | 
| ------------- |:-------------:| 
| `.`    | 匹配除换行符以外的任意字符 | 
| `\w`    | 匹配字母或数字或下划线或汉字|
| `\d` | 匹配数字  | 
|`\b`|匹配单词的开始或者结束
|`^`|匹配字符串的开始
|`$`|匹配字符串的结束


##### 例子:

- QQ号必须为5位到12位数字时，可以使用：`^\d{5,12}$`
- 有些正则表达式处理工具还有一个处理多行的选项。如果选中了这个选项，`^`和`$`的意义就变成了匹配行的开始处和结束处。

#### 字符转义

##### 例子:

- `deerchao\.net`匹配`deerchao.net`
- `C:\\Windows`匹配`C:\Windows`
