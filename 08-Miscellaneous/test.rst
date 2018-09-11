.. include:: https://cdn.rawgit.com/MacHu-GWU/d3c75539b6669ad3bc8e200f1671078c/raw/226338fa82b181204e805f50e47ab8473829a0b2/Rst-Style.rst


在Rst中使用CSS Style Sheet
==============================================================================

- This is :red:`Red` text.
- This is :blue:`Blue` text.
- This is :green:`Green` text.

实现的原理是这样的. Rst中有三个directives:

- ``.. raw::``, 表示在Rst转Html时, 下面的内容会原封不动的嵌入在Html中.
- ``.. role::``, 表示为文本添加Html标签属性, 例如class, id之类的.
- ``.. include::``, 表示引用外部文件的内容, 相当于把外部文件的内容添加到本文件中. **但是无法
