Code with syntax highlight:

.. code-block:: python

	d = {"a": 1, "b": 2}
	for key, value in d.items():
	    pass

Code with line number:

.. code-block:: python
	:number-lines:

	import sys

	PY2 = sys.version_info.major == 2
	PY3 = sys.version_info.major == 3

Reference:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#code