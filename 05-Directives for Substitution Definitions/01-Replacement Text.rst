``.. |key| replace::`` 可以用来替换一段长文本。

参考资料:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#replacement-text

Rest::

	.. |reST| replace:: reStructuredText

	Yes, |reST| is a long word, so I can't blame anyone for wanting to
	abbreviate it.

Output:

.. |reST| replace:: reStructuredText

Yes, |reST| is a long word, so I can't blame anyone for wanting to
abbreviate it.