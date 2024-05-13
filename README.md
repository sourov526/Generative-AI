# activate anaconda base 
source /home/sourov/anaconda3/bin/activate

# The base environment is activated by default
conda config --set auto_activate_base True

# The base environment is not activated by default
conda config --set auto_activate_base False

# Line 5 and line 8 only work if conda init has been run first
# conda init is available in conda versions 4.6.12 and later

------------------------------------------------

# create conda virtual env
conda create -p venv python=3.9 -y    # you can use any version of python
# activate the venv
conda activate venv/