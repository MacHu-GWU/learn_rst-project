可以在文档中动态的引用当前的时间。

参考资料:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#date

.. |date| date::
.. |time| date:: %H:%M

Today's date is |date|.

This document was generated on |date| at |time|.