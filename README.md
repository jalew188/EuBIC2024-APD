# EuBIC2024-APD
AlphaPeptDeep notebooks for EuBIC-2024 Winterschool

## Preliminary programming experience

* Python, Jupyter notebooks
* Numpy
* Pandas
* VSCode

PyTorch experience is not necessary, but audiences need to know a bit about deep learning or machine learning.

## Preparation

* Install Anaconda from https://www.anaconda.com/download or Miniconda from https://docs.conda.io/projects/miniconda/en/latest/. Set conda as the default Python environment during installation.

* Install VSCode from https://code.visualstudio.com/. 

* Install VSCode extensions: `Python` and `Jupyter`.

* In VSCode, open `Terminal -> New Terminal` to start a conda terminal (or start an anaconda prompt) then run:
```
conda create -n apd python=3.10
conda activate apd
```

* Install required packages in the `apd` terminal environment, run:
```
pip install -U peptdeep plotly alphatims alpharaw
# If you have GPU:
#pip install -U torch --index-url https://download.pytorch.org/whl/cu118
```

Due to the possible internet issue, we may be not able to install packages during the conference. ~~Install required Python packages, run `notebooks/0.pip_install.ipynb`, select `eubic2024` as the python interpreter.~~

* Download this repository via `git clone https://github.com/jalew188/EuBIC2024-APD`. Or download the zip file at https://github.com/jalew188/EuBIC2024-APD: Click `Code` -> `Download zip`.

* Download required data from https://datashare.biochem.mpg.de/s/PQl8nyqfHVZZHte into the `test_data` folder. It contains:
  * `dda` folder with files: `HeLa_500ng.raw`, `HeLa_500ng.raw.hdf`, `MaxQuant_msms.txt`, and `pFind-Filtered.spectra`.
  * `phos` folder with files: `20171001_QE3_nLC7_DBJ_SA_LFQphos_Tech_Rep_03.raw`, `20171001_QE3_nLC7_DBJ_SA_LFQphos_Tech_Rep_03.raw.hdf`, and `MaxQuant_msms.txt`.
  * `ProteomeKingdom.zip`. Unzip to to get `ProteomeKingdom` folder with many .txt files in truncated MaxQuant msms.txt format.

#### Then follow exercises (ipython notebooks) in the `notebooks` folder.


## If participants have their own data or properties to train and predict, we will also help.