# EuBIC2024-APD
AlphaPeptDeep notebooks for EuBIC-2024 Winterschool

* Install Anaconda from https://www.anaconda.com/download or Miniconda from https://docs.conda.io/projects/miniconda/en/latest/. Set conda as the default Python environment during installation.

* Install VSCode from https://code.visualstudio.com/. 

* Install VSCode extensions: `Python` and `Jupyter`.

* In VSCode, open `Terminal -> New Terminal` to start a conda terminal (or start an anaconda prompt) then run `conda create -n eubic2024 python=3.10`.

* Install required Python packages, run `notebooks/0.pip_install.ipynb`, select `eubic2024` as the python interpreter.

* Download required data from https://datashare.biochem.mpg.de/s/PQl8nyqfHVZZHte. It contains:
  * `dda` folder with files: `HeLa_500ng.raw`, `HeLa_500ng.raw.hdf`, `MaxQuant_msms.txt`, and `pFind-Filtered.spectra`.
  * `ProteomeKindom` folder with many txt files.

#### Then follow exercises (ipython notebooks) in the `notebooks` folder.
