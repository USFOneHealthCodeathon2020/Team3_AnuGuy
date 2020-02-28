# ProjectZer0 - a microbiome data bank
 
Say something about ProjectZer0. Maecenas porta risus ut convallis hendrerit. Aenean aliquet, dolor lobortis blandit laoreet, mauris nulla interdum odio, in lacinia libero quam feugiat augue. Fusce dapibus tristique dui, quis interdum ipsum aliquet nec. 

Requirements:
- bash
- conda 4.7.12
- python 3.6.9
- tensorflow (>=2.1.0)
- django 2.2.5
- R 3.6.2
- dada2 1.14.1

## Installation Instructions
    
### Download and Install Conda
https://www.anaconda.com/distribution/
   
### Download projectZer0
    wget https://github.com/USFOneHealthCodeathon2020/projectZer0/raw/master/projectZer0.tar.gz
    
### Decompress the tarball
    tar -vxzf projectZer0.tar.gz
    
### Create a new environment in Conda with the required dependencies
    cd projectZer0 && conda create -n Zer0 python=3.6.9 --file requirements.txt
    
### Activate the Zer0 Enviroment
    conda activate Zer0
    
### Launch the Zer0 Djano WebApp
    python manage.py runserver
    
### Connect to WebApp
   Use a web browser* to access Zer0 locally at http://localhost:8000 or http://127.0.0.1:8000
    
   *google chrome preferred
 
## Examples

### Data Preperation
  The purpose of this part of the task is to analyze the raw microbiome sequencing data and acquire the bacterial counts in   each sample.

The requirements:
- Paired-end fastq files for each sample

Data format for each sample:
- Forward fastq: xxxx_R1_001.fastq
- Reverse fastq: xxxx_R2_001.fastq

The way the files should be kept:
- All the fastq files should be demultiplexed and stored in one folder
- The folder may be uploaded to the server in zipped format

### Subsampling:(Optional)
Users can subsample a certain number of reads from each sample to reduce the data volume
They can do it using seqtk tool which is available here:
https://github.com/lh3/seqtk

Does it need anything else?
No, everything else is already in the server

Generate bacterial counts table:
The pre-loaded scripts can give the following results:
1) How many sequences in each sample had at the beginning and how many remained at each of the processing step
1) The sequences of each Amplicon sequence variants (ASVs) in fasta format
2) The bacterial count table for all the samples (ASV counts in rows and samples in the columns)
3) The taxonomies (upto genus or species level) of each ASV based on Silva Database v.132

### Data Visulization

Luctus quis. Vivamus ut consectetur orci, vel venenatis lacus. 

    aliquam sapien velit vehicula posuere accumsan eleifend
    
Gravida quis purus: 

    nunc sagittis pellentesque metus eu sagittis felis commodo vel
    
    
## References

If you use projectZero in your research, please cite:

*Manuscript in Preperation
