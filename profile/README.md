# mlgid-project

## A comprehensive toolbox for grazing-incidence diffraction (GID)

<p align="center">
  <img src="images/mlgid_logo_mlgid.png" width="400" alt="mlgid">
</p>

This project aims to implement a comprehensive set of tools for the standardization and automation of GID data processing. The packages can be used separately or combined together in the pipeline. 



> As a convention, packages that rely on machine learning start with `ml`, while other packages (such as those for conversion to reciprocal space and conventional peak fitting) start with `py`.

<!--- # Feedback from the community:
> It is a big and beautiful pipeline, folks, and everybody loves it. (requested anonymity)
-->

# Available packages

## [pygid](https://github.com/mlgid-project/pygid) - conversion of raw GID data to reciprocal space

## [mlgidDETECT](https://github.com/mlgid-project/mlgidDETECT) - ML-based Bragg peak detection

## [pygidFIT](https://github.com/mlgid-project/pygidFIT) - fitting of Bragg peaks

## [mlgidMATCH](https://github.com/mlgid-project/mlgidMATCH) - ML-based matching of crystal structures with Bragg peaks


## [mlgidGUI](https://github.com/mlgid-project/mlgidGUI) - graphical user interface for annotating GID data

## [pygidSIM](https://github.com/mlgid-project/pygidSIM) - simulating synthetic GID data from crystal structures

---

# Publications

The following is the list of papers related to the _mlgid_ project.


<details>
  <summary><strong>List of papers</strong></summary>

### pygid

pygid: a Python package for fast data reduction in grazing-incidence diffraction

A. Abukaev, C. Völter, M. Romodin, S. Schwartzkopff, F. Bertram, O. Konovalov, A. Hinderhofer, D. Lapkin and F. Schreiber. 	Journal of Applied Crystallography [https://doi.org/10.1107/S1600576725010593]

### mlgidGUI

mlgidGUI - an annotation program for 2D scattering data

C. Völter, V. Starostin, M. Romodin, E. Kneschaurek, D. Lapkin, A. Hinderhofer, and F. Schreiber. Journal of Open Source Software [https://joss.theoj.org/papers/10.21105/joss.08499]

### ML-based peak detection and structure refinement

_Tracking perovskite crystallization via deep learning-based feature detection on 2D X-ray scattering data_

V. Starostin, V. Munteanu, A. Greco, E. Kneschaurek, A. Pleli, F. Bertram, A. Gerlach, A. Hinderhofer, and F. Schreiber. npj Comput. Mater. 8, 101 (2022) [https://doi.org/10.1038/s41524-022-00778-8](https://doi.org/10.1038/s41524-022-00778-8)

### Deployment at synchrotron facilities for real-time analysis

_End-to-end deep learning pipeline for real-time processing of
surface scattering data at synchrotron facilities_

V. Starostin, L. Pithan, A. Greco, V. Munteanu, A. Gerlach, A. Hinderhofer, and F. Schreiber. Synchrotron Radiat. News 35, 21-27 (2022) [https://doi.org/10.1080/08940886.2022.2112499](https://doi.org/10.1080/08940886.2022.2112499)

### Benchmarking peak detection

_Benchmarking deep learning for automated peak detection on GIWAXS data_

C. Völter, V. Starostin, D. Lapkin, V. Munteanu, M. Romodin, M. Hylinski, A. Gerlach, A. Hinderhofer, F. Schreiber. J. Appl. Crystallogr. 58, 513-522 (2025) [https://doi.org/10.1107/S1600576725000974](https://doi.org/10.1107/S1600576725000974)

</details>
