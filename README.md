[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cgusb/solidification-tracking/main)

# Metadata

Author: C. G. Becker and M. Corvellec
Title: Solidification tracking of a metallic alloy
Year: 2022
Month: December
Abstract: In this example, we identify and track the solid-liquid
(S-L) interface in a series of x-radiography images depicting a
nickel-based alloy undergoing solidification. This process is preceded
by laser melting, which simulates metal additive manufacturing (AM)
conditions. Tracking the S-L interface position over time yields the
solidification velocity, which enables the prediction of resulting
microstructures. Material properties of AM-built parts depend on the
resulting microstructures, which is why the ability to predict
microstructures is valuable. In subsequent studies, these predicted
microstructures will be verified, improving the capability to link
processing parameters to microstructures and thus material properties.
The image sequence was obtained by the Center for Advanced Non-Ferrous
Structural Alloys (CANFSA) and beamline scientists of the Advanced Photon
Source (APS) located at Argonne National Laboratory (ANL).

# Context and content

This repository contains an example tutorial developed for the Python
package scikit-image. This analysis was first presented at ImageXD
2021 [1]. The annotated analysis routine was accepted into the
long-form documentation of scikit-image and will be released with
version 0.20.0.

The [Python file](./plot_solidification_tracking.py) is the source for
the data analysis workflow. It is used to render the [HTML
file]((https://scikit-image.org/docs/dev/auto_examples/applications/plot_solidification_tracking.html)
featured in the above-mentioned documentation. The [Jupyter
notebook](./plot_solidification_tracking.ipynb) is derived from this
Python file as well.

# Reference

[1] Corvellec M. and Becker C. G. (2021, May 17-18)
    "Quantifying solidification of metallic alloys with scikit-image"
    [Conference presentation]. BIDS ImageXD 2021 (Image Analysis Across
    Domains). Virtual participation.
    https://www.youtube.com/watch?v=cB1HTgmWTd8
