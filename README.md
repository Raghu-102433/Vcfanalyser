# vcfanalyser



A simple toolkit to analyze and visualize **VEP-annotated VCF files**.  

It converts VEP-annotated VCFs into tables and generates summary plots for quick variant insights.



---



##  How To Use:



### Create and activate a conda environment

```

conda create -n vcfanalyser python=3.10 -y

conda activate vcfanalyser

```

### Install dependencies

``` bash

# Install GATK inside the environment

conda install -c bioconda gatk4 -y
```

### Install Python libraries
```
pip install pandas matplotlib seaborn openpyxl
```

Verify installation

```
gatk --version

python -c "import pandas, matplotlib, seaborn, openpyxl; print('Python libs OK')"
```

###  Run the analysis

```
chmod +x vcf_analyser.sh

./vcf_analyser.sh <input_vcf> <output_dir>
```

Example:

```
./vcfanalysis.sh sample_vcf.vcf analysisresults/
```

---
Author:
Raghavendra S, Bioinformatics researcher

 Contact: raghava.332410@gmail.com

---

##  License
This project is released under the **MIT License**.  

If you use or adapt this tool in your work, please **cite or acknowledge the author** as:  

**Raghavendra S (Raghu-102433). (2025). *Vcfanalyser*: A toolkit for analyzing and visualizing VEP-annotated VCF files.**





