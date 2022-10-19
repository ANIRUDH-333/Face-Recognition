# Face-Recognition
A simple demonstration of face recognition with face-recognition package. We created a dataset of single facial images and tried testing if the image detected in the webcam is same as that in the dataset or not.

## Error installing the face-recognition package ??
I am adding this section since I had issues installing it.

### [Direct installation](https://pypi.org/project/face-recognition/) of the package
``` 
pip install face-recognition
```

Not able to install directly ?

### Installing the package in environment
I solved the above problem by creating an environment since I had issues installing the dlib package which is essential for the face-recognition package.

Creating the conda environment
```
conda create -n <package_name> python=3.8
```
Give a package name of your choice and the I recommend the python version to be 3.8.

now, clone [this](https://github.com/RvTechiNNovate/face_recog_dlib_file) repository and go the the ```face_recog_dlib_file``` folder to access the files there.
```
git clone https://github.com/RvTechiNNovate/face_recog_dlib_file.git
cd face_recog_dlib_file
```

Now install the dlib package and the cmake package usinjg pip
```
pip install dlib-19.19.0-cp38-cp38-win_amd64.whl
pip install cmake
```

The final part is to install the face-recognition package. We have installed the other dependencies which are required to install this package.
Now, install this package using pip.
```
pip install face-recognition
```
