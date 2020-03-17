# Translator++  简体中文文档
## Translator++ 中的自动文本换行
点此[返回目录](https://github.com/zyf722/TranslatorPlusPlusChineseWiki)；点此[参阅官方原版文档](http://dreamsavior.net/docs/translator/getting-started/word-wrapping-in-translator/)。

将游戏从一种语言翻译到另外一种语言时，可能出现一种独特的语言现象——翻译的结果比原文长。  
在这种情况下，文本可能会溢出整个对话框，导致显示错乱。

![](https://i.loli.net/2020/03/17/aslCARG4ZEJP5f2.png)  
*图1：这种恼人的现象称之为“文本溢出”*

不过好在 Translator++ 有办法解决这个问题。（耶！）

并且我们可以一键、批量完成这个操作！（太棒了！）

想要执行自动文本换行，只用这么做：

在左侧“对象”面板中，选择文件并右键点击。在弹出的窗口中选择“**对 (?) 进行操作**”-“**批量文本换行**”。

![](https://i.loli.net/2020/03/17/kUfohypH8MOnP9D.png)  
*图2：Translator++ 中的“批量文本换行”*

“批量文本换行”窗口将会出现。

![](https://i.loli.net/2020/03/17/j7RONzGg4fmwrkC.png)  

在“选择上下文”或“手动查找”中选择要进行换行的文本的上下文。

例如，在 RPG Maker VX Ace 中，对话文本位于“Dialog”上下文中。

然后选择需要换行的文本所在的那一列（我们称之为“**源**”）。

再选择换行后的文本要输出的一列（称之为“**目标**”），并按下“**开始换行！**”按钮，等待处理完成即可。

稍等片刻，换行后的文本便会出现在**目标**列中。

![](https://i.loli.net/2020/03/17/mUQosD4BLWX9etE.png)  

文本换行过程中可能会生成多行文本，如在一个对话框内无法一次性显示，Translator++ 将会自动添加第二个对话框。

但是，该功能仅适用于“显示文字”和“显示滚动文字”这两个事件指令。
