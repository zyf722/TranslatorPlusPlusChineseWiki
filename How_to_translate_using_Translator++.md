# Translator++  简体中文文档
## 如何使用 Translator++ 进行翻译
点此[返回目录](https://github.com/zyf722/TranslatorPlusPlusChineseWiki)；点此[参阅官方原版文档](http://dreamsavior.net/docs/translator/getting-started/how-to-translate-using-translator/)。

在 Translator++ 中进行翻译是非常简单的。总的来说，您要做的就是将最左边一栏（“源文本”）的翻译输入到其右侧即可。

在成功地创建了一个新项目后，您可能会注意到一个如下图所示的翻译表格：

![](https://i.loli.net/2020/03/15/b4JSHD5p9FCTIjZ.png)  
*图1：“源文本”列和翻译文本列。*

图中用红框框起的（1）部分，即表格中的“源文本”列，您不能修改本列。

Translator++ 将在您的游戏中搜索一切可翻译的文本并导入至此列，并在导出时将该列的文本替换为翻译。所以，任何试图更改此列内容的操作都是很危险的。

图中剩下来的（2）部分都是翻译文本列。

Translator++ 将认为靠右的列的翻译比相对靠左的列的翻译要好，因此在最终导出时会使用同行最右边的非空列的内容作为该行源文本的翻译。

下图为您更清晰地展示了这一过程，图中用红框框起的部分将作为翻译导出，同行其他翻译结果将被忽略。

![](https://i.loli.net/2020/03/15/cBVo3C5MLZsNbYu.png)  
*图2：Translator++ 将使用同行最右边的非空列的内容作为翻译。*
