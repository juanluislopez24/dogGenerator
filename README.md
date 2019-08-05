# dogGenerator
This is an approach to generate dog images with a GAN based on DCGAN using Tensorflow2. 

## Locally
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

## Colab
Colab is a very nice alternative if you dont have gpu on your local computer, besides its free to use. You get the advantage of fast internet connection and easy integration with Drive, so you can persist your trainingCheckpoints. 

The colab file is shared through this link:
https://colab.research.google.com/drive/1prk_A5iEQFfS8blMkSGER5zsjuAdYRXZ

or...
You can use this repo or a fork and import it through colab, or upload dogGeneratorLocal.ipynb to your colab instance.
