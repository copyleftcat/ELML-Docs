# ELML (极简脚本语言)

ELML 是一门基于大括号的极简脚本语言。

>**官方实现**：目前由 VB6 编写的官方解释器，请前往 [ELML-IDE](https://github.com/copyleftcat/ELML-IDE) 下载。

## 示例代码
\```text
{Let a = "Hello, World!"}
{MsgBox("编程语言：")} {MsgBox(lanName)}
{MsgBox(a)}
\```

## 语法规范
- 使用 `{}` 包裹每一条指令
- `{Let 变量名 = 值}`：定义变量
- `{MsgBox(内容)}`：弹出窗口输出
