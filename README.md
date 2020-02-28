# ProjectZer0 - a microbiome data bank
 
Say something about ProjectZer0. Maecenas porta risus ut convallis hendrerit. Aenean aliquet, dolor lobortis blandit laoreet, mauris nulla interdum odio, in lacinia libero quam feugiat augue. Fusce dapibus tristique dui, quis interdum ipsum aliquet nec. 

Requirements:
- conda 4.7.12
- python 3.6.9
- tensorflow (>=2.1.0)
- django 2.2.5
- R 3.6.2
- dada2 1.14.1

## Installation Instructions
    
### Download and Install Conda
    wget https://repo.anaconda.com/archive/Anaconda3-2019.10-MacOSX-x86_64.sh && bash Anaconda3-2019.10-MacOSX-x86_64.sh 
   
### Download projectZer0
    wget https://github.com/USFOneHealthCodeathon2020/projectZer0/raw/master/projectZer0.tar.gz
    
### Decompress the tarball
    tar -vxzf projectZer0.tar.gz
    
### Create a new environment in Conda with the required dependencies
    cd projectZer0 && conda create -n Zer0 python=3.6.9 --file requirements.txt
    
### Activate the Zer0 Enviroment
    conda activate zer0
    
### Launch the Zer0 Djano WebApp
    python manage.py runserver
    
### Connect to WebApp
   Use a web browser* to access Zer0 locally at <a href="localhost:8000">localhost:8000</a> or <a href="127.0.0.1:8000">127.0.0.1:8000</a>
    
   *google chrome preferred
 
## Examples

### Ut Ultricies 

Vel ex in consectetur:

    urabitur eu dui quis nisi iaculis

Faucibus nec a erat: 

    pellentesque imperdiet enim eu velit mollis a viverra dolor sodales donec commodo risus 
      sed purus fermentum vitae posuere odio malesuada nullam cursus rhoncus ex

### Id Imperdiet Metus 

Luctus quis. Vivamus ut consectetur orci, vel venenatis lacus. 

    aliquam sapien velit vehicula posuere accumsan eleifend
    
Gravida quis purus: 

    nunc sagittis pellentesque metus eu sagittis felis commodo vel
    
    
## References

If you use projectZero in your research, please cite:

*Manuscript in Preperation
