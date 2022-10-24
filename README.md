# virtual-env-sandbox
Repository to practice creating, activating, deactivating and switching virtual environments on Python.
## Creating a virtual environment using conda

Exercise: create a virtual environment. Install the dependencies as outlined.

The commands below assume you are using a command prompt (Linux, Mac) or the Anaconda prompt on Windows.

```
conda create --name venv0 python==3.7.5

conda activate venv0

pip install -r requirements-0.txt

conda deactivate

```

Repeat the exercise 

```
conda create --name venv1 python==3.7.5

conda activate venv1

pip install -r requirements-1.txt

conda deactivate

```

```
conda create --name venv2 python==3.7.11

conda activate venv2

pip install -r requirements-2.txt

conda deactivate

```

## Playing with different environments