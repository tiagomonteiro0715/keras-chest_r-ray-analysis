# keras-chest_x-ray-analysis

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)

![brain scan image](https://image.freepik.com/free-photo/radiology-doctor-examining-chest-x-ray-film-patient-health-care-clinic_224098-127.jpg)

-----
### What this is

A tensorflow model written in Python

### What this does

In particular, it uses a dataset of images to create a model that can distinguish between chest images that have and don't have cancer.


### Motivation and what I have learned

Tensorflow 2.4 was implemented as part of this project to gain a deeper understanding of the software and to serve as an example for other similar projects in the future.

As a programming enthusiast in this subfield, I considered tensorflow to be the best machine learning framework available. My choice of technology is based on this.

Besides learning more about the framework and machine learning, I also gained a better understanding of programming and how it works in real time. 

### Main difficulties and how it stand out

To be able to complete the project, I had to figure out and comprehend what had to be written.

This project stands out from the crowd due to its concise code. Furthermore, the model is easy to use and intuitive.  

-----

### Install dependencies

#### Upgrade pip and install [pipenv](https://pipenv.pypa.io/en/latest/)

```
pip install --upgrade --user pip

pip install --upgrade virtualenv
```



Create and activate the virtual enviroment.The python version already needs to be installed in your pc

I am using this python version because at the moment this python version is  compatible with tensorflow and keras

```
virtualenv envname
```



#### Activate it:

Windows:
```
envname\Scripts\activate
```
macOS/Linux:
```
envname/bin/activate
```
#### Install necessary modules and activate it

```
pip install tensorflow==2.4.1 pandas==1.2.4 numpy==1.2 ipykernel
```

#### Make sure the code runs on a jupyter notebook

```
python -m ipykernel install --name=envname
```
#### Start jupyter notebook

```
cd ../..

jupyter notebook
```
-----

Dataset used: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
