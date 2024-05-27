=================
Week 7, Wednesday
=================

.. pfsc::

    from gh.toepproj.lit.H.ilbert.ZB import Thm119

Carrying on with Thm 119, we were looking at
:pfsc-chart:`this step <Thm119.Pf.S130.A2>`. I want to now talk about the role
this step is playing in this proof.

We want to show that :pfsc-chart:`$f' = f$ <Thm119.Pf.A160>`, and we're working
toward one half of that, namely that :pfsc-chart:`$f' \\geq f$ <Thm119.Pf.A150>`.
What we know about $f$ is :pfsc-chart:`this <Thm119.Thm.I2>`. So it would
suffice to show that we've got :pfsc-chart:`the same congruence <Thm119.Pf.A140>`
(essentially), with $f'$ in place of $f$.

And we're going to get this from :pfsc-chart:`here <Thm119.Pf.A120>`.
We know that $\zeta^\ell = 1$, and that the value of $\zeta^g$ for any integer
$g$ depends only on the residue of $g$ mod $\ell$.
Therefore :pfsc-chart:`the subproof we've been looking at <Thm119.Pf.S130>`
supplies the critical observation we need.
