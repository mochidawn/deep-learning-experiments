## Collect some tricks about deep-learning

## OpenCV with customized build
- the resize speed will improve!

git clone https://github.com/opencv/opencv.git <br>
mkdir build <br>
cd build <br>

cmake -D PYTHON3_EXECUTABLE=/home/seanyu/.conda/envs/tf18_keras_opencv/bin/python -D PYTHON_INCLUDE_DIR=/home/seanyu/.conda/envs/tf18_keras_opencv/include/python3.6m -D PYTHON_LIBRARY=/home/seanyu/.conda/envs/tf18_keras_opencv/lib/libpython3.6m.so ../

make <br>
sudo make install <br>
#### IF you dont have sudo previlege
(./configure --prefix=/path/to/install/dir) <br>
(make install) <br>
