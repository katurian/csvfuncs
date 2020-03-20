# csvfuncs
Functions for adding and deleting CSV columns when the file is too large for Pandas. Another function extracts CSVs from a compressed zip file.

# notes
I'm too lazy to write documentation, but please note that the column ``index`` variable in ``removeColumns()`` and ``addColumns()`` is represented by the alphabetical headers in Microsoft Excel. You can change these headers to numerical labels at ``Options/Formulas``. Scroll down and check ``R1C1 reference style``.