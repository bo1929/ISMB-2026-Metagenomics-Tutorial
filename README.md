# ISMB 2026 Tutorials
## Scalable metagenomic sequence analysis using *k*-mer based methods
This tutorial offers a practical introduction to *k*-mer–based approaches for large-scale metagenomic analysis, featuring some of the most widely used and prominent tools in the field.
Hands-on exercises will help participants become familiar with these methods.
The tools that will be covered include:

- Kraken2, sylph, and Sourmash for taxonomic classification and profiling,

- krepp, DecoDiPhy, and kf2vec for phylogenetic placement and distance estimation,

- VirFinder for phage identification and phage-host interaction prediction.

Each tool may require a different setup.

Instructors will make their slides available.

## Schedule and links
- 9:00 am - 9:15 am (15 mins): Siavash Mirarab
**Introduction, schedule, and logistics**

### 9:15 am - 9:45 am (30 mins): Siavash Mirarab
**Background, overview of different problems, and *k*-mer-based approaches**

### 9:45 am - 10:45 am (1 hour): Ben Langmead
**Taxonomic classification using Kraken2**

- No install or data preparation is required before the tutorial!

- A sandbox.bio application will be linked on this page.

- Pyodide application will be used for exploring Kraken2 classification decisions.

- For more reading and hands-on exercises, refer to [this protocol paper](https://www.nature.com/articles/s41596-022-00738-y).

### 10:45 am - 11:00 am (15 mins): Coffee Break

### 11:00 am - 12:00 pm (1 hour): Fengzhu Sun
**Phage identification and phage-host interaction using VirFinder and *d2* family of methods**

- No installation or environment setup is needed before the tutorial!

- The hands-on tutorial will be through [this Colab notebook](https://colab.research.google.com/drive/12RK4Dhqrr5M_HouFl6hbbzFdv2KEihDQ).

- Participants are encouraged, but not required, to check [this protocol paper](https://doi.org/10.1002/cpz1.70310) and [this example](https://github.com/secdio/DeepVirFinder_protocol).
Please email me at asapci(at)ucsd(dot)edu if you do not have access to the protocol paper (paywall).

### 12:00 pm - 1:00 pm (1 hour): David Koslicki
**k-mer sketching for fast metagenomic analysis using Sourmash and YACHT**

- **Pre-tutorial setup:** Please follow the steps in [this repository](https://github.com/KoslickiLab/ISMB-2026-workshop) to install Sourmash and YACHT, and download the data that will be used in the tutorial.

- Tutorial and exercises for [Sourmash](https://github.com/KoslickiLab/ISMB-2026-workshop/blob/main/Sourmash.md) and [YACHT](https://github.com/KoslickiLab/ISMB-2026-workshop/blob/main/YACHT.md).

### 1:00 pm - 2:00 pm (1 hour): Lunch Break

### 2:00 pm - 3:00 pm (1 hour): Yun William Yu
**Abundance profiling using sylph and ANI calculation using skani**

- **Pre-tutorial setup:** Participants should have a Linux environment with [Bioconda](https://bioconda.github.io/).
The machine should have access to at least 16 GB of RAM and 16 GB of free disk space to run the tutorial.
Multicore setups are recommended but not necessary.

- The tutorials we will follow are at the following links for [skani](https://github.com/bluenote-1577/skani/wiki/skani-basic-usage-guide) and [sylph](https://sylph-docs.github.io/5%E2%80%90minute-sylph-tutorial/)

**Instructor note:** Closer to the tutorial date, a single combined Git repository and documentation might be created and linked here to make it easier for the participants to follow.

### 3:00 pm - 4:00 pm (1 hour): Ali Osman Berk Sapci
**Estimating distances from reads to genomes and phylogenetic placement using krepp**

### 4:00 pm - 4:15 pm (15 mins): Coffee Break

### 4:15 pm - 4:45 pm (30 mins): Shayesteh Arasti
**Consolidating read placements into a few phylogenetic placements using DecoDiPhy**

- No installation or environment setup is needed before the tutorial!

- The tutorial for DecoDiPhy will follow this [Colab notebook](https://github.com/shayesteh99/DecoDiPhy/blob/main/DecoDiPhy_tutorial.ipynb)

### 4:45 pm - 5:15 pm (30 mins): Eleonora Rachtman
**Converting sequences into *k*-mer feature representations for phylogenetic placement, classification, and distance estimation**

- **Pre-tutorial setup:** Follow the steps [here](kf2vec-instructions.md).

- See [this document](kf2vec-tutorial.pdf) for the hands-on exercises.

### 5:15 pm - 5:30 pm (15 mins): Siavash Mirarab
Discussion of applications & closing remarks

### 5:30 pm - 5:45 pm (15 mins)
Audience survey on the effectiveness of the course
