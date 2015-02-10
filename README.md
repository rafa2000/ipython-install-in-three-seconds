# IPython - Install in three seconds

``` bash
# These commented instruction are needed to install Python and virtualenv. 
# The last instruction (uncommented), plus the PipFile,  is all that you need
# to install Ipython if you are not using a virtual environment.
# (Polish this instructions).
#
# Install Python...
# Install disttools...
# Install virtualenv
#    pip install virtualenv
# Create a virtualenv
#    virtualenv venv
# Spawn the virtualenv
#    source venv/bin/activate
# Install dependencies for IPython
pip install -r Pipfile
# Invoke Ipython notebook
ipython notebook
# or invoke Ipython with pylab (scipy + graphs)
ipython --pylab notebook
# + work in ipython
# + save your notebooks
# + exit IPython
# Exit from the virtualenv
#   deactivate
```
