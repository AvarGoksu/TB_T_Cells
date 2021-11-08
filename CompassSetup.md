1) `COMPASS` is dependent on `cplex`. `cplex` currently doesn't work for python 3.7 and above. So if you don't have a python 3.6 environment, create a new conda environment with python 3.6:

`conda create --name py36 python=3.6`

2) Run this:

`exec "$SHELL"`

3) Activate the environment:

`conda activate py36`

4) Install `cplex`:

`conda install -c ibmdecisionoptimization cplex`

5) Install `numpy`:

`python -m pip install numpy`

6) Install `scanpy`:

`pip install scanpy`

7) Install `COMPASS`:

`python -m pip install git+https://github.com/yoseflab/Compass.git --upgrade`

8) Install jupyter lab and other desired packages, run jupyter lab, see if cplex and compass are imported without error.
