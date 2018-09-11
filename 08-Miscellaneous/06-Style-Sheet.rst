.. include:: ./css.rst


在Rst中使用CSS Style Sheet
==============================================================================

- This is :red:`Red` text.
- This is :blue:`Blue` text.
- This is :green:`Green` text.

实现的原理是这样的. Rst中有三个directives:

- ``.. raw::``, 表示在Rst转Html时, 下面的内容会原封不动的嵌入在Html中.
- ``.. role::``, 表示为文本添加Html标签属性, 例如class, id之类的.
- ``.. include::``, 表示引用外部文件的内容, 相当于把外部文件的内容添加到本文件中. **但是只能引用本地文件, 无法引用网上的文件**.

所以你可以将你的CSS文件用raw包装起来. 然后用role定义若干个class. 最后将整个用RST写的CSS文件用include引用进来即可.
