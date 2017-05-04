如何使用Unicode符号。

参考资料:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#unicode-character-codes

Rest::

	Copyright |copy| 2003, |BogusMegaCorp (TM)| |---|
	all rights reserved.

	.. |copy| unicode:: 0xA9 .. copyright sign
	.. |BogusMegaCorp (TM)| unicode:: BogusMegaCorp U+2122
	   .. with trademark sign
	.. |---| unicode:: U+02014 .. em dash
	   :trim:

Output:

Copyright |copy| 2003, |BogusMegaCorp (TM)| |---|
all rights reserved.

.. |copy| unicode:: 0xA9 .. copyright sign
.. |BogusMegaCorp (TM)| unicode:: BogusMegaCorp U+2122
   .. with trademark sign
.. |---| unicode:: U+02014 .. em dash
   :trim: