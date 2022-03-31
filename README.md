# pandapower-short-circuit-analysis

Experimenting with pandapower capability on solving short circuit analysis.

This tutorial use:

* Windows operating system
* VSCode Terminal (PowerShell)
* Python 3.8 as IPython kernel
* Jupyterlab installed outside `.env`

## Environment

```powershell
py -3.8 -m virtualenv env
env\Scripts\Activate.ps1
pip install pandapower ipykernel
py -m ipykernel install --name "py3.8-pandapower"
```

## Package used

```plaintext
pandapower==2.9.0
ipykernel==6.10.0
matpower==7.1.0.2.1.1
oct2py==5.5.1
numba==0.55.1
```