# kf2vec (*k*-mer frequencies to vectors)

kf2vec is a tool for converting genome sequences into *k*-mer feature representations and using them for phylogenetic placement, classification, and model-based distance estimation.

You can find the GitHub repository [here](https://github.com/noraracht/kf2vec).

## Installation

### Option 1: Bioconda (recommended)
```bash
conda create -n kf2vec_env python=3.11
conda activate kf2vec_env
conda install -c bioconda kf2vec
```

### Option 2: From the environment file
Download the environment file from the [GitHub repository](https://github.com/noraracht/kf2vec), and then run
```bash
conda env create -f kf2vec_osx64_v2.yml -n kf2vec_env
conda activate kf2vec_env
```

### Basic Usage
Check installation:
```
kf2vec --help
kf2vec --version
```

For the alternative installation (from the environment file), run
```bash
python -m kf2vec.main --help
```
