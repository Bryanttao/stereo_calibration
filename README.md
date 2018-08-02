# stereo_calibration
双目相机标定
# install
```
      mkdir build
      cd build
      cmake ..
      make
```
# run 
./stereo_calib -w=<board_width default=9> -h=<board_height default=6> -s=<square_size default=1.0> <image list XML/YML file default=../data/stereo_calib.xml>
