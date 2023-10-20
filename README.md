# Linux
Linux basic knowledge
## 一、常见命令
## 二、特殊命令
### 1. nohup
```python
nohup 英文全称 no hang up（不挂起），nohup Command [ Arg … ] [　& ]
  -参数说明：
	Command：要执行的命令。
	Arg：一些参数，可以指定输出文件。
	&：让命令在后台执行，终端退出后命令仍旧执行。

## 在后台执行 root 目录下的 runoob.sh 脚本，并重定向输入到 runoob.log 文件
nohup /root/runoob.sh > runoob.log 2>&1 &
	2>&1 解释：将标准错误 2 重定向到标准输出 &1 ，标准输出 &1 再被重定向输入到runoob.log 文件中。
	0 – stdin (standard input，标准输入)
	1 – stdout (standard output，标准输出)
	2 – stderr (standard error，标准错误输出)
   ```
