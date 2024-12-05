COSMOS-Web Strong Lensing
=========================

This repository contains candidate strong lenses found by the COSMOS-Web Lensing Science Working Group.

Lenses were found by a visual inspection campaign, where 6 people inspected of order 42000 images from the COSMOS-Web
survey and ranked their likelihood of being a strong lens.

COSMOS-Web data consists of long exposure time multi-band James Webb Space Telescope. This means that every strong
found comes with exquisite imaging data for lensing analysis.

Getting Started
---------------

The repository has 436 folders containing the candidiates which passed the visual inspection criteria
described in the discovery paper (insert link in future).

17 candidates begin with the tag `M24`, which are the 17 most spectactular lenses found in the survey which
are to be described in a stand-alone paper.

The remaining candidates begin with a score out of 12, where a higher score means more inspectors input the candidate
as a good candidate lens. A good guide to follow is:

- `S10 - S12`: Very high quality lens candidates.
- `S07 - S09`: High quality lens candidates.
- `S05 - S06`: Medium quality lens candidates.
- `S02 - S04`: Low quality lens candidates.
- `S00 - S01`: Very low quality lens candidates.

However, we have had recent discussions which indicate that there are low score candidates which are still
good strong lens candidates. Improvements in our visualization and analysis of the candidates is helping us determine
that harder to identify lenses are still strong lenses.

Public Data Release
-------------------

Each folder of each candidate contains the following files:

- `.fits` files containing the JWST imaging data, RMS noise map and PSF for all 4 wavebands (F115W, F150W, F277W, F444W).
- `.png` files showing the data and results of lens modeling.
- a `result` folder in each waveband containing the lens light model, lensed source model and a source reconstruction in the source plane.

Science Goals
-------------

The COSMOS-Web survey will produce a unique sample of strong lenses, which drive its core science goals:

- **Cosmology via Strong and Weak Lensing**: The unprecendented depth of JWST imaging means COSMOS-Web will be the
densest collections of strong lenses ever found. This will allow for a detailed structural study of a small patch of
the Universe, whcih will be complemented by the COMSOS-Web weak lensing analysis.

- **Distant Galaxies**: Even without lensing, JWST is illuminating the faintest and most distant galaxies ever seen.
The magnified source galaxies of the strong lenses found in this sample will push the limits of what we can learn about
galaxies even further.