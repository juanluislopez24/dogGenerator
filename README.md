# dogGenerator
This is an approach to generate dog images with a GAN, based on DCGAN

The file dogGeneratorLocal.ipynb is made to run the program locally, just install the dependencies with conda:

```
conda create -y --name dogGenerator python==3.7
conda install -f -y -q --name py37 -c conda-forge --file requirements.txt
conda activate dogGenerator
````
Or simply create a new environment with the dependencies:
```
conda env create -f dogGenerator.yml
conda activate dogGenerator 
```


