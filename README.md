# Simulome 

Simulome provides a powerful and easy to use tool for creating pseudo-genomes and mutated variants for prokaryotes.  Simulome makes it possible to create genomes based on any bacterial species, while controlling for a variety of factors.  Furthermore, it provides a range of options that can be used in combination to create mutated variants of the simulated genome, which allows for controlled testing of specific genomic conditions.  Simulome can be used in combination with reads generated from next-generation sequencing platforms or alternatively with NGS read simulation packages.  

For more information about the usage of Simulome, [see the simulome wiki](https://github.com/price0416/Simulome/wiki).

Please cite Simulome if you use it in your research!

## Requirements
- Python >= 3.8.5
- Biopython >= 1.78 
- BLAST >= 2.10.1

## Installing Requirements
```bash
conda install -c conda-forge biopython
conda install -c bioconda blast
```
If you are not using an Anaconda environment you can install Biopython with `pip install biopython` and install Blast  with `brew install blast`