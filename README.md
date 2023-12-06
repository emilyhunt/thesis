[![Latest PDF](https://img.shields.io/badge/Submitted_PDF-download-green.svg)](https://archiv.ub.uni-heidelberg.de/volltextserver/33588/1/thesis_Hunt_final.pdf)
[![DOI](https://img.shields.io/badge/DOI-10.11588/heidok.00033588-blue.svg)](https://doi.org/10.11588/heidok.00033588)


# Improving the census of open clusters in the Milky Way with data from Gaia

This is the repo of [my PhD thesis](https://raw.githubusercontent.com/emilyhunt/thesis/main/my-thesis.pdf).

This work is a big look at open clusters in the era of Gaia. The introduction of my thesis is hopefully a nice intro and review of how Gaia has changed open cluster science, with a lot of technical details following later about how to detect open clusters in Gaia data, how to construct a catalogue, and how to define open clusters & measure their parameters.

## Abstract

For over a century, open clusters have been a key tool for understanding stellar and galactic evolution. Now, thanks to groundbreaking new astrometric and photometric data from the European Space Agency's Gaia satellite, it is possible to study open clusters to never before seen levels of accuracy and precision. In this thesis, I develop and apply new methodologies to improve the census of open clusters with data from Gaia. I focus on using modern, efficient, and statistically rigorous techniques, aiming to maximise the reliability and usefulness of the open cluster census despite the many challenges of working with the billion-star dataset of Gaia. 

Firstly, I conducted a comparative study of clustering algorithms for retrieving open clusters blindly from Gaia data. I found that a previously untrialed algorithm, HDBSCAN, is the most sensitive algorithm for open cluster recovery. Next, using this methodology, I used Gaia DR3 data to create the largest homogeneous catalogue of open clusters to date, recovering a total of 7167 clusters -- 2387 of which are candidate new objects. I developed an approximate Bayesian neural network for classifying the reliability of the colour-magnitude diagrams of the clusters in the census. Additionally, I used a modification of this network to infer parameters such as the age and extinction of these clusters. Finally, since many of the objects in my catalogue appeared more compatible with moving groups, I measured accurate masses, Jacobi radii, and velocity dispersions for these clusters, thus creating the largest catalogue of these parameters for open clusters to date. Using said parameters, I showed that no more than 5619 of the clusters in my catalogue are compatible with bound open clusters. I used my mass estimates to derive an approximate completeness estimate for the Gaia DR3 open cluster census, finding that the approximate 100\% completeness limit depends strongly on cluster mass. 

The results of this thesis show that it is possible to reliably create a catalogue of open clusters with a single blind search, in addition to measuring parameters for these objects. The methods developed in this thesis will be applicable to future data releases from Gaia and other sources.

## Citation

If you use this thesis in your work, you can cite the [DOI of my thesis](https://doi.org/10.11588/heidok.00033588); if you use one of the chapters, you should cite the relevant papers (Chapter 2: [Hunt & Reffert 2021](https://ui.adsabs.harvard.edu/abs/2021A%26A...646A.104H/abstract); Chapter 3: [Hunt & Reffert 2023](https://ui.adsabs.harvard.edu/abs/2023A%26A...673A.114H/abstract); Chapter 4: Hunt & Reffert _submitted_)

## Thesis style

My thesis used the [Clean Thesis style](http://cleanthesis.der-ric.de/) by R. Langner. You can find a [template directory](https://github.com/derric/cleanthesis) here on GitHub. (It was a really pretty thesis style so I can recommend it highly!)

## License Information for the Clean Thesis Style

README.md
Copyright 2019 R. Langner

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in
  http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is R. Langner.

This work consists of all files listed in MANIFEST.md.
