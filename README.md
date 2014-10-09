normal.inverse.js
=================
> Get z value from normal standard distribution

### Lower tail quantile for standard normal distribution function.

This function returns an approximation of the inverse cumulative standard normal distribution function.  I.e., given `P`, it returns an approximation to the `X` satisfying `P = Pr{Z <= X}` where `Z` is a random variable from the standard normal distribution.

The algorithm uses a minimax approximation by rational functions and the result has a relative error whose absolute value is less
than `1.15e-9`.

- Author:      Peter John Acklam
- E-mail:      jacklam@math.uio.no
- URL:     [http://home.online.no/~pjacklam/notes/invnorm/](http://home.online.no/~pjacklam/notes/invnorm)

- Javascript implementation by Liorzou Etienne
- Adapted from Dr. Thomas Ziegler's C implementation itself adapted from Peter's Perl version

**Q**: What about copyright? 
**A**: You can use the algorithm for whatever purpose you want, but please show common courtesy and give credit where credit is due.

If you have any reclamation about this file (ie: normal.inverse.js file), please contact me.

