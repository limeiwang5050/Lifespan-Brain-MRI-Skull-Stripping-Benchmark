# A Review and Benchmarking of Brain MRI Skull-Stripping Methods Across the Human Lifespan

## Overview

This repository accompanies the study:

**“A Review and Benchmarking of Brain MRI Skull-Stripping Methods Across the Human Lifespan.”**

The study provides a systematic review and large-scale benchmark of brain MRI skull-stripping methods across the human lifespan. The benchmark includes paired T1-weighted and T2-weighted MRI from nine neuroimaging datasets, spanning from neonates to older adults.

This repository releases the **reference brain masks used in the benchmark** to facilitate reproducibility, independent evaluation, and future development of skull-stripping methods.

**Only reference brain masks are distributed through this repository. Original MRI images are not redistributed.** Users should obtain the corresponding MRI scans directly from the original data providers using the links below and comply with the respective data-use agreements.

---

## Reference Labels and Original MRI Data

The lifespan benchmark data were obtained from nine publicly available neuroimaging datasets. Reference brain masks are provided separately for each dataset.

| Dataset | Reference Labels | Original MRI Data |
|---|---|---|
| dHCP | [`dHCP_labels.zip`](Labels/dHCP_labels.zip) | [Developing Human Connectome Project](https://biomedia.github.io/dHCP-release-notes/) |
| HBCD | [`Part 1`](Labels/HBCD_1_labels.zip) · [`Part 2`](Labels/HBCD_2_labels.zip) · [`Part 3`](Labels/HBCD_3_labels.zip) | [NBDC Data Share](https://nbdc-datashare.lassoinformatics.com/) |
| BCP | [`BCP_labels.zip`](Labels/BCP_labels.zip) | [NIMH Data Archive – Baby Connectome Project](https://nda.nih.gov/edit_collection.html?id=2848) |
| IBIS | [`IBIS_labels.zip`](Labels/IBIS_labels.zip) | [NIMH Data Archive](https://nda.nih.gov/) |
| HCPD | [`HCPD_labels.zip`](Labels/HCPD_labels.zip) | [NIMH Data Archive](https://nda.nih.gov/) |
| ABCD | [`ABCD_labels.zip`](Labels/ABCD_labels.zip) | [NBDC Data Share](https://nbdc-datashare.lassoinformatics.com/) |
| HCP | [`HCP_labels.zip`](Labels/HCP_labels.zip) | [Human Connectome Project – Young Adult](https://www.humanconnectome.org/study/hcp-young-adult) |
| IXI | [`Part 1`](Labels/IXI_1_labels.zip) · [`Part 2`](Labels/IXI_2_labels.zip) · [`Part 3`](Labels/IXI_3_labels.zip) | [IXI Dataset](https://brain-development.org/ixi-dataset/) |
| HCPA | [`HCPA_labels.zip`](Labels/HCPA_labels.zip) | [NIMH Data Archive](https://nda.nih.gov/) |

---

## Matching Reference Labels to Original MRI Data

The released reference masks retain the **original dataset-specific subject identifiers** in their filenames, allowing them to be matched to the corresponding MRI scans obtained from the source datasets.

After downloading the original MRI data from the links above, users can identify the corresponding T1-weighted and T2-weighted scans using the subject identifiers contained in the reference-mask filenames.

Because naming and directory conventions differ among the nine source datasets, users should follow the organization and naming conventions of each original dataset when matching the released masks to the source MRI data.

> **Note:** This repository does not redistribute any original MRI images. Access to the source MRI data is governed by the terms, licenses, and data-use agreements of the respective data providers.

---

## Citation

If you use these reference brain masks in your research, please cite:

**A Review and Benchmarking of Brain MRI Skull-Stripping Methods Across the Human Lifespan**

Full citation information will be added upon publication of the accompanying article.

---

## Contact

For questions regarding the released reference masks or the lifespan skull-stripping benchmark, please open an issue in this repository.
