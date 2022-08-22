# fitsnap.github.io
Software and information related to SNAP and FitSNAP

This repo houses the HTML files for creating the FitSNAP doc page at https://fitsnap.github.io/

Steps to change this webpage:

1. Fork this repo and make a local clone.

2. Copy and paste the contents of `path/to/FitSNAP/docs/html` to this directory, e.g. `cp path/to/FitSNAP/docs/html/* path/to/fitsnap.github.io` 

3. To sucessfully create the webpage from HTML files, we need to create a `.nojekyll` file in this directory, because Jekyll is Github's default which we are not using. 

4. Submit a pull request from your forked repo to the upstream version.
