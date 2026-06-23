# UBC Master of Data Science Capstone Project

Capstone final report for the project in collaboration with the Boreal Avian Modelling Centre.

## Environment Setup

To preview and render the report locally, please follow the below instructions.

### Install Miniconda

#### Linux

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh

bash Miniconda3-latest-Linux-x86_64.sh
```

#### macOS

```bash
curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh

bash Miniconda3-latest-MacOSX-arm64.sh
```

#### Windows

Download and install Miniconda from:

[https://www.anaconda.com/download/success](https://www.anaconda.com/download/success)

---

### Clone the Repository

```bash
git clone https://github.com/beardw/capstone-final-report

cd capstone-final-report
```

---

### Create and Activate the Conda Environment

```bash
conda env create -f environment.yml

conda activate capstone
```

---

### Render or Preview Report

```bash
quarto render final-report.qmd
```

OR

```bash
quarto preview final-report.qmd
```

---

### Deactivate Environment

```bash
conda deactivate
```
