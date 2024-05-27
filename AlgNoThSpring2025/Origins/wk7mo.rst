==============
Week 7, Monday
==============

.. pfsc::

    from gh.toepproj.lit.H.ilbert.ZB import Thm119, Thm117

We looked at Hilbert's Thm 119, which shows how primes different from $\ell$ factor
in the $\ell$th cyclotomic field.

I want to talk about :pfsc-chart:`this step <Thm119.Pf.S130.A2>`.
Here $\mathfrak{p}$ is a prime ideal coprime to $\ell$.
The proof cites a step from the proof of Thm 117, where we factored $\ell$.
I want to go back and look at how we got that factorization, so let's
|open the proof of Thm 117|.

.. |open the proof of Thm 117| pfsc-chart::
    :view: Thm117.Pf.A5
    :group: "Thm117"

The form of the factorization is easier to remember, if you remember how we
get it. It comes from |factoring the minimal polynomial|
that defines the field, and then just plugging in $x = 1$.

.. |factoring the minimal polynomial| pfsc-chart::
    :view: Thm117.Pf.A4
    :group: "Thm117"
