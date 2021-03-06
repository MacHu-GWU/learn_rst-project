与表格有关的元素。

参考资料:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#tables

Grid Table:

+-----------+------+------------+-----------------+
| City name | Area | Population | Annual Rainfall |
+-----------+------+------------+-----------------+
| Adelaide  | 1295 |  1158259   |      600.5      |
+-----------+------+------------+-----------------+
| Brisbane  | 5905 |  1857594   |      1146.4     |
+-----------+------+------------+-----------------+
| Darwin    | 112  |   120900   |      1714.7     |
+-----------+------+------------+-----------------+
| Hobart    | 1357 |   205556   |      619.5      |
+-----------+------+------------+-----------------+
| Sydney    | 2058 |  4336374   |      1214.8     |
+-----------+------+------------+-----------------+
| Melbourne | 1566 |  3806092   |      646.9      |
+-----------+------+------------+-----------------+
| Perth     | 5386 |  1554769   |      869.4      |
+-----------+------+------------+-----------------+

CSV Table:

.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"

List Table:

.. list-table:: Frozen Delights!
   :widths: 15 10 30
   :header-rows: 1

   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!

Reference:

- http://docutils.sourceforge.net/docs/ref/rst/directives.html#tables