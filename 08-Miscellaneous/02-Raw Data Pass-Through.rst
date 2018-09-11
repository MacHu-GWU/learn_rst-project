``.. raw::`` 可以直接在生成的文档中插入目标输出格式的代码。比如可以直接在生成的Html中插入Html。当然你可以选择从其他文件读取, 或是直接从url读取。raw和include的主要区别是, raw引用进来的内容不会被rst渲染, 而include引用进来的会.

参考资料:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#raw-data-pass-through

.. raw:: html

   <a href="https://www.google.com/">Google</a>

.. raw:: html
   :file: inclusion.html

.. raw:: html
   :url: https://www.google.com/