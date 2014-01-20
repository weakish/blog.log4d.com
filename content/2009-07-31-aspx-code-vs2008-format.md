Title: VS2008格式化aspx代码
Author: alswl
Slug: aspx-code-vs2008-format
Date: 2009-07-31 00:00:00
Tags: VisualStudio
Category: 工欲善其事必先利其器

在VS2008中编辑代码时候，可以使用「编辑-高级-设置文档的格式」来进行格式化代码，快捷键是Ctrl+K Ctrl+D。

但是我在格式化aspx代码时候，却遇到这样的问题，提示「未能重新格式化文档。已还原为原始格式」，「未能完成该操作。」，「未能完成操作。参数不正确」。

遇到这样的原因大凡是由于Html代码中存在一些问题，如嵌套有没有正常关闭，特殊符号如">"有没有转换成转义字符。

比较快捷的修改方法是使用DreamWeaver提供的验证功能，在「结果」面板中，可以使用F7快捷键打开，使用它的验证功能，可以快速找出Html不合法的地方。
