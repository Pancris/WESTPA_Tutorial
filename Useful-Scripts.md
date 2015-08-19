The following are user submitted scripts (bash, python, zsh, etc) that may be helpful to you.

# How To Contribute

Where appropriate, please use a git/mercurial repository, and link to the repo from this page.  For individual scripts, use [gists](gist.github.com), which are essentially one file git repositories that may be linked with their own unique URL.  This avoids cluttering the page and allows for version control, even for individual scripts.  Please include contact information, if desired, and a brief description of what the script does.  For now, please simply add in scripts; as more are added, they will be organized appropriately.

# Scripts

## [Weighted Ensemble-Based String Method](https://stringmethodexamples.readthedocs.org/en/latest/ Weighted Ensemble-based String Method)

Author: Joshua Adelman

Description: See site for description & download.

## [Report CPU/Wallclock Time](https://gist.github.com/ajoshpratt/aba3ecb5d77bca9d3420)

Author: Adam Pratt

Contact: [ajp105@pitt.edu](mailto:ajp105@pitt.edu?Subject=WallclockScript)

Description: Pulls wallclock and CPU time from a WESTPA .h5 file and prints it to the console.  Useful for quickly converting this information into human readable format.

## [Generate Free Energy Surface Evolution Movie](https://gist.github.com/ajd98/abd7cadd8017557582da)

Author: Alex DeGrave

Contact: [ajd98@pitt.edu](mailto:ajd98@pitt.edu?Subject=FreeEnergyEvolutionMovieScript)

Description: Generates a movie of the time evolution of a free energy surface from a WESTPA simulation. [An example from a 2-dimensional, 2-well toy model](https://www.dropbox.com/s/aeow7xi4jr35fgk/energy_surface_evolution.avi?dl=0).

## [Sample predicate function for w_select](https://gist.github.com/ajoshpratt/e751b38c869f477ee637)

Author: Adam Pratt

Contact: [ajp105@pitt.edu](mailto:ajp105@pitt.edu?Subject=SamplePredicateFunction)

Description: A sample function, as used in w_select.  Pulls in the progress coordinate information for an N dimensional system and checks to see if the final timepoint of each segment is larger than 5.  If so, it adds it to the collection of seg_ids to be returned.
