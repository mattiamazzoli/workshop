# Installation


Install anaconda  
https://docs.anaconda.com/anaconda/install/  

from terminal  
$ conda create --name workshop --file requirements.txt  

$ conda activate workshop  
$ jupyter notebook  

Open the InstallationTest.ipynb and test the notebook



in alternative:  

$ conda create -c conda-forge -n workshop "pymc>=5"  
$ conda install -c anaconda jupyter notebook  
$ conda install aesara  
$ conda install geopandas  



Check Packages Versions

pymc       5.23.0
jupyter    1.1.1 
arviz      0.21.0
geopandas  1.1.0
scipy      1.15.2
