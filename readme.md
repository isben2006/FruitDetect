# FruitDetect

This project consists of a script that opens a camera and is able to detect and recognise three different types of fruit: Apples, bananas and lemmons. This can be used in agriculture as farmers can use this tool to detect the grown crops with a camera so they don't have to check everyday walking through the crops.



## The Algorithm

This project uses the detectnet model to identify this three fruits. It was trained with 300 images, 100 per class and 10 epochs to make it precise and accurate. This project also includes a script to run the camera and test the model.

## Running this project

1. Install git and cmake if you don't have them yet.
```     
sudo apt install git all
sudo apt install cmake
```

2. Clone the jetson-inference folder into your home directory.
```
git clone https://github.com/dusty-nv/jetson-inference
cd jetson-inference
```

3. Inside your jetson-inference folder clone this project
```
git clone https://github.com/isben2006/FruitDetect
```

4. Connect your usb camera, move to the FruitDetect project and run the script.
```
python3 fruit-detect.py
```
[View a video explanation here](video link)
