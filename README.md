#  YOUNG RESEARCHERS EVENT 2022 🏝
## New digital tools to study the brain

**Introduction to the ENIGMA and BrainStat Toolboxes** | 🧰 | Surface data visualisation and multiscale neural contextualisation

- [ ENIGMA Toolbox ](https://enigma-toolbox.readthedocs.io/en/latest/)

    Larivière S, Paquola C, Park BY, Royer J, Wang Y, Benkarim O, Vos de Wael R, Valk SL, Thomopoulos SI, Kirschner M, Lewis LB. The ENIGMA Toolbox: multiscale neural contextualization of multisite neuroimaging datasets. _Nature Methods_. 2021 Jul;18(7):698-700.
    
- [ BrainStat ](https://brainstat.readthedocs.io/en/master/)

    Larivière S, Bayrak Ş, Vos de Wael R, Benkarim O, Herholz P, Rodriguez-Cruces R, Paquola C, Hong SJ, Misic B, Evans A, Valk S. BrainStat: A toolbox for brain-wide statistics and neuroscientific contextualization. _Under review (NeuroImage)_.

---

 
### 🐍 Python installation
To do the tutorials in `python`, clone and install the ENIGMA Toolbox repository:
```
git clone https://github.com/MICA-MNI/ENIGMA.git
pip install /path/to/<ENIGMA>
```
Also clone the current repository and install the requirements:
```
git clone https://github.com/saratheriver/YRE-2022.git

cd /path/to/<YRE-2022>/
python -m pip install -r requirements.txt
```
 <br>

### 🌋 Matlab installation
To do the tutorials in `matlab`, clone the current repository:
```
git clone https://github.com/saratheriver/YRE-2022.git
```
Also clone the ENIGMA Toolbox and BrainStat repositories and add their paths in matlab:
```
git clone https://github.com/MICA-MNI/BrainStat.git
git clone https://github.com/MICA-MNI/ENIGMA.git

addpath(genpath('/path/to/<ENIGMA>/matlab/'))
addpath(genpath('/path/to/<BRAINSTAT>/brainstat_matlab/'))
```

---

### 🔗 Tutorial links
> [ | 🐍 | ENIGMA Toolbox tutorial](./python_tuts/01.ENIGMA-Tutorial.ipynb) <br/>
> [| 🌋 | ENIGMA Toolbox tutorial](./matlab_tuts/01.ENIGMA-Tutorial.mlx) <br/>
> [ | 🐍 | BrainStat tutorial](./python_tuts/02.BRAINSTAT-Tutorial.ipynb) <br/>
> [| 🌋 | BrainStat tutorial](./matlab_tuts/02.BRAINSTAT-Tutorial.mlx) <br/>
