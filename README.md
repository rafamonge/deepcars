# deepcars 

Course website: http://cars.mit.edu


# Setup guide for windows 10 pro


## installing chocolatey 

- this is a package manager for windows. Used here  for installing anaconda3. Run the following from a cmd.
```shell
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```
## installing tensorflow 

run the following from a cmd as administrator

```shell
#install anaconda3
chocolatey install anaconda3
# create tensorflow environment.  Note: at the time of this writing it has got to version 3.5 of python. no more and no less.
conda create -n tensorflow python=3.5 anaconda
activate tensorflow
#Notes  if you are in an enterprise environment that uses proxies, use --proxy=|proxy| as an additional option
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.0.1-cp35-cp35m-win_amd64.whl 
```

## install open cv2
- Goto http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
- Download opencv_python-3.2.0+contrib-cp35-cp35m-win_amd64.whl  (cp 35 = is for python 3.5, presumably)

run the following from a cmd as administrator

```
pip install opencv_python-3.2.0+contrib-cp35-cp35m-win_amd64.whl 
```
## setting up keras

http://machinelearningmastery.com/setup-python-environment-machine-learning-deep-learning-anaconda/

## Keras book repo

https://github.com/PacktPublishing/Deep-Learning-with-Keras
