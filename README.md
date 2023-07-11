# abo-analysis

Analysis of ABO MinION sequences

ABO sequences were aquired from the NCBI dbRBC database:

<https://www.ncbi.nlm.nih.gov/projects/gv/mhc/xslcgi.cgi?cmd=bgmut/home>

# The nextflow workflow

Input files and output directory can be defined in the config files or provided directly in the commandline.
To analyse files, run `nextflow run main.nf -resume` (override inputs and output using `--reads '*.fastq' --outdir 'ABO_results'`)
