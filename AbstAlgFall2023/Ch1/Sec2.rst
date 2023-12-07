=========
Section 2
=========

.. pfsc::

    from ....theorem1 import Pf

This time we write chart widgets in *directive* form.
Actually we're also using rST *substitutions* so that we can define
the directives at the bottom of the file.

We can point to |w01: a step in a proof|
and to |w02: another step|.

.. |w01: a step in a proof| pfsc-chart::
    :view: Pf.R

.. |w02: another step| pfsc-chart::
    :view: Pf.S
