# My Tensoflow study projects
Since: 26 Aug 2018<br>
By: michael@designquest.com.hk

# Install
References: https://www.tensorflow.org/install/install_mac

## If no pip
    sudo easy_install pip

## If no virtualenv
    pip install --upgrade virtualenv

## Create a Virtualenv environment
    virtualenv --system-site-packages -p python3 ./

## Activate virtualenv
    source ./bin/activate

## Ensure pip ≥8.1 is installed (in Virtualenv)
    easy_install -U pip

## Install TensorFlow and all the packages that TensorFlow requires (in Virtualenv)
    pip3 install --upgrade tensorflow

## Install Jupyter Notebook (in Virtualenv)
    pip3 install --ignore-installed ipython
    pip3 install --ignore-installed jupyter

# Activate

## Activate virtualenv
    source ./bin/activate

## Start jupyter server
    jupyter notebook

## Quit virtualenv
    deactivate