Formalization of StalinSort
=================================

This is, to the very best of my knowledge, the first 
formalization of StalinSort, an optimal sorting algorithm using 
Coq proof assistant.

In order to produce short proofs, we rely on a tactics library by 
Adam Chlipala (crush tactic).

Future work
--------------

A possible improvement in this formalization is to instrument the
code with a monad to show that StalinSort is O(n).
