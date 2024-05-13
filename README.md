This repository contains sage code used to compute the density of cubic hypersurfaces over the rational numbers with a point. 
It is used in the paper - joint with Lea Beneish - titled "How often does a cubic hypersurfaces have a point?" [Available on the arxiv](https://arxiv.org/pdf/2405.06584).

Files:
* computing_rho_p.ipynb: contains the main computation of rho(p), the local density of p-adic cubic forms with a p-adic point
* presenting_rho.ipynb:  turns the symbolic expressions for rho(p) into the condensed expressions which appear in the paper. Checks they agree with the originals and produces LaTeX.
* rho_numerics.ipynb:    give precise estimates for the product of rho(p) over all primes by truncating appropriately.
