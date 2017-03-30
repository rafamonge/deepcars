# deepcars

Course website: http://cars.mit.edu

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

```shell
chocolatey install anaconda3
conda create -n tensorflow python=3.5 anaconda
activate tensorflow
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.0.1-cp35-cp35m-win_amd64.whl --proxy="http://proxy-chain.intel.com:911"

#install open cv2
- Goto http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
- Download opencv_python-3.2.0+contrib-cp35-cp35m-win_amd64.whl  (cp 35 = python 3.5. I think)
pip install opencv_python-3.2.0+contrib-cp35-cp35m-win_amd64.whl 


```