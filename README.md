# Some Crazy Python Experiments

I use Jupyter Notebook to experiment with things in Python, libraries and concepts.

Here is a dump of some interesting experiments hopefully will help inspire a few.

### Instructions

Download and install [Anaconda](https://www.anaconda.com/download) on your system. (I am on the Python 3 version).

Comment: This way you get to create different python environments without impacting the one
on your system. It also comes with a bunch of handy data science libraries.
You can always add more packages to your conda environment by doing `conda install <package>`.

Git clone this repository (to somewhere appropriate on your system)

```
git clone https://github.com/Atlas7/python-wow
```

Navigate to the repository root:

```
cd python-wow
```

Create a new python environment by doing this:

```
conda env create -f py36-python-wow.yml
```

Activate Conda:

```
source activate
```

Then activate the environment by doing this:


```
source activate py36-python-wow
```

Now, fire up Jupyter Notebook:

```
jupyter notebook
```

Access Jupyter Notebook at [http://localhost:8888/](http://localhost:8888/) and start playing!
