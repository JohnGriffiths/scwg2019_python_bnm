# Scientific Computing Working Group Workshop on large-scale brain network modelling in Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JohnGriffiths/scwg2019_python_bnm/master)


### Developed by
- John Griffiths

( With essential contributions from: Julie Courtiol, Amanda Easson, Kelly Shen, Jerry Jeyachandra )


## Getting workshop material for SciNet workshops

*** 

### If you're using SciNet's Jupyter System

Open up a terminal and enter the following:
```bash
  ssh <user>@teach.scinet.utoronto.ca
  module load anaconda3
  source /scinet/course/ss2019/3/9_brainnetwork/miniconda3/bin/activate tvb_py2
  python -m ipykernel install --user --name tvb_py2
```

Open a new terminal and enter the following:
```bash
  ssh -L 8888:jupyterhub<X>:8000 <user>@teach.scinet.utoronto.ca -N
```

Where `<X>` is a number between 1-6. 

If nothing happens that's great! Now open up your favourite browser and enter the following in your address bar:

```
  https://localhost:8888
```

Finally: open up a terminal in jupyter, clone the repo for this course, and cd into there

```bash
git clone https://github.com/JohnGriffiths/scwg2019_python_bnm
```

Ok, you're ready to go!

***




### If you're running locally on your machine

Mooch on over to the [scwg python neuroimaging course github repo](https://github.com/jerdra/scwg2018_python_neuroimaging) and follow the alternative setup instructions in the README. You'll have to make a few (fairly obvious) adaptions, namely replacing the url of that repo with the url of this one. 






