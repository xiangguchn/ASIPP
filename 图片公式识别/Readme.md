这里介绍一种快速识别图片中公式的方案，这种方案可以快速得到LaTex源码与word公式。通过设置快捷键，录制宏，可以大大节省时间。
首先通过Mathpix截图识别出公式的Latex源码：

Mathpix下载：https://mathpix.com/

下载安装之后，快捷键可以自己设置，默认的Ctrl + Alt + M不适合单手操作，毕竟另一个手还要操纵鼠标截图。

截图区域选好之后，Mathpix会自动识别图片中的公式，给出LaTex源码，并将LaTex源码复制到剪切板上。


--------------------------

如果只需要LaTex源码，到这里就可以了。下面是介绍的是如何将Latex源码变为word中的公式

--------------------------

LaTex转MathML可以通过在线网站：https://stackedit.io/editor来完成。


将剪切板上的LaTex源码粘贴到两个“$”之间，右边会出现公式:


右键公式 -> Show Math As -> MathML Code :


得到MathML Code：


全选 -> 复制。在Word中插入公式 -> 只粘贴文本，就可以得到可以编辑的word公式了（Word中的这几步，可以录制一个宏，选择快捷键更节省时间）：




公式来源：EAST中性束注入的能量损失研究
