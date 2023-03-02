# NMFS Open Science Collaborative Resource Book

This is an online resource by the NMFS Open Science community. [Read the book](https://nmfs-opensci.github.io/ResourceBook)

# Attribution

This is a copy of the [Quarto website template](https://github.com/Openscapes/quarto-website-tutorial) developed by Qpenscapes. This particular variant is based off [NMFS Openscapes](https://nmfs-openscapes.github.io)

# Can I copy this repo?

Feel free to fork or as a template. Though if you want to start more bare bones, use the Openscapes [Quarto website template](https://github.com/Openscapes/quarto-website-tutorial).

# How does it work?

This online book is being built automatically with a GitHub Action. The Action is not loading R (or Python), so any code you have in your qmd files will not render and in fact will cause the GitHub Action to fail. Note, for plain markdown, you can use `.md` instead of `.qmd`. You'll need to edit the workflow in the `.github/workflows` folder to install R/Python if you have code.

The structure of the book is in `_quarto.yml`. The rest should be self-explanatory after you look at that file.

<hr>

## Disclaimer

This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project content is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.

## License addendum

This content was created by U.S. Government employees as part of their official duties.  This content is not subject to copyright in the United States (17 U.S.C. §105) and is in the public domain within the United States of America. Additionally, copyright is waived worldwide through the CC0 1.0 Universal public domain dedication.


