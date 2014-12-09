# Quick wishlist for future additions:

## Easy(sh)

* Add two-way clustering (but first check that combining TWC and HDFE is theoretically sane).
* Add core() support for OSX/Linux.
* In the regression table, make the absvar name column at least as wide as the indepvar name column (it looks ugly otherwise).
* More postestimation commands (e.g. -test-).
* Fix the test suite which is a big mess, and improve code coverage.

## Hard

* Add a more thorough discussion on the possible identification issues
* Find out a way to use HDFEs with efficient GMM (right now only OSL and 2SLS work correctly)
* Implement -bootstrap- option in DoF estimation
* Calculate exact DoF adjustment for 3+ HDFEs (note: not a problem with cluster VCE when one FE is nested within the cluster). Note: Paulo Guimaraes has worked on this, and *lfe* and a few received emails have a few discussions about this.
