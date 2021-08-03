# CarND_ComputerVisionFundamentals

```
git clone https://github.com/udacity/CarND-Term1-Starter-Kit.git
cd CarND-Term1-Starter-Kit
conda env create -f environment.yml - tensorflow==0.12.1

Note: Some Mac users have reported issues installing TensorFlow using this method. The cause is unknown but seems to be related to pip. For the time being, we recommend opening environment.yml in a text editor and swapping
conda env remove -n carnd-term1
```

```bash
# NOTE: This is DIFFERENT from  https://github.com/udacity/CarND-Term1-Starter-Kit.git
git clone https://github.com/udacity/CarND-Term1-Starter-Kit-Test.git
cd CarND-Term1-Starter-Kit-Test

```

conda create -n car_nd tensorflow
conda activate car_nd

pip install --upgrade pip
pip install opencv-contrib-python

conda install -c conda-forge ffmpeg
conda install -c conda-forge moviepy
conda install -c conda-forge jupyterlab

pip install imageio
pip install matplotlib
pip install imageio-ffmpeg

name: carnd-term1
channels: - https://conda.anaconda.org/menpo - conda-forge
dependencies: - python==3.5.2 - numpy - matplotlib - jupyter - pillow - scikit-learn - scikit-image - scipy - h5py - eventlet - flask-socketio - seaborn - pandas - ffmpeg - imageio - pyqt=4.11.4 - pip: - moviepy - opencv-python - requests - tensorflow==1.3.0 - keras==2.0.9
