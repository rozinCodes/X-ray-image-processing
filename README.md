
# This repo is a fork of the  [TorchXRayVision](https://github.com/mlmed/torchxrayvision) 📝  



Modifications
* added bulk and single image processing option
* processed data will be saved in a csv file along with filenames

* //currently working on the excel format with the images included in the file

#I used Python 3.8 64 bit version and pip version 23.0.1


Clone the project  
~~~bash 
git clone https://github.com/rozinCodes/X-ray-image-processing.git
~~~

Install the necessary packages

~~~bash
pip install -r requirements.txt
~~~

Place some image(s) in the images folder

~~~bash
cd scripts
~~~

Run the image process file
~~~bash
python process_image.py
~~~

There will be a prompt asking you to select if you want to process a single image or process mutiple images together

If you select Bulk image processing, images in the images/ folder will start being processed one after another.
There is an option to choose from images when selecting single image processing.

After the processing is finished, the data.csv file will be saved in the processed_data folder

# Contributions
Any code optimization contributions or features are always welcome