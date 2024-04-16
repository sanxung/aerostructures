# Aerostructures

Aerostructures is a Python package based on the OpenMDAO framework (https://github.com/OpenMDAO/OpenMDAO1) for aerostructural analysis and optimization problems using NASTRAN-95 (https://github.com/nasa/NASTRAN-95) and PANAIR (http://www.pdas.com/panair.html).

The aerostructures package was initially developed by Joan Mas Colomer during a PhD thesis at ONERA and ISAE.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install aerostructures.

```bash
git clone https://github.com/sanxung/aerostructures.git
cd aerostructures

conda create -n aerostructures_py38 python=3.8
conda activate aerostructures_py38

pip install . -i https://pypi.tuna.tsinghua.edu.cn/simple
```

## License information

See the [LICENSE.txt](LICENSE.txt) file for information on the license used for this package as well as on the licenses of the derived work from other packages.
