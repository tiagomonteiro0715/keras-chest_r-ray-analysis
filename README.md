# keras-chest_x-ray-analysis

![brain scan image](https://image.freepik.com/free-photo/radiology-doctor-examining-chest-x-ray-film-patient-health-care-clinic_224098-127.jpg)

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)

-----

The motivation behind this project was to gain a better understanding of tensorflow 2.4 and to serve as an example for future projects of the same tyope. 

Essencially, it takes a dataset of images builds a model that classifies brain images with and without cancer. I used tensorflow because it was, in my pint of view, the best machine lerning framework for programming enthusiatis in this subfield.

Not only I lerned a lot about this framework, but also learned in a pratical way machine lerning. This projects standout by the code being writeen in a way that is easy to understand.

-----

Dataset used: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

-----

Install dependencies:

Upgrade pip and install [pipenv](https://pipenv.pypa.io/en/latest/)

```
pip install --upgrade --user pip

pip install --upgrade virtualenv
```

Create and activate the virtual enviroment.The python version already needs to be installed in your pc

I am using this python version because at the moment this python version is  compatible with tensorflow and keras

```
virtualenv --python=/usr/bin/python3.7 envname
```
Activate it:

```
cd envname/Scripts

activate
```

Install necessary modules and activate it

```
pip install tensorflow==2.4.1 matplotlib==3.3 keras==2.4 ipykernel

```

Install modules to make sure the code runs on a jupyter notebook

```
pip install ipykernel
python -m ipykernel install --user --name ENVNAME --display-name "Python (whatever you want to call it)"
```
After all this, start jupyter notebook

```
jupyter notebook
```

-----

Started on 18/04/2021

Ended 20/04/2021

Archived
