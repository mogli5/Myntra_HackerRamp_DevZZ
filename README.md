# Requirements 
 - Python 3.6
 - Selenium
 - Keras
 - TensorFlow
 - Matplotlib
 - Sklearn
 - Numpy
 - Pandas

# Web Scraping
 - This was done using Selenium with Python3
 - We chose these locations to scrape images from, covering a range of multipurpose e-Commerce sites, fashion magazines, catalogues and fashion shopping sites
	 - Vogue India
	 - Flipkart
	   (above can be accessed by running the ```data_collection_fkmyvog.py```)
	 - Amazon (run ```amazon_data_script.py```)
	 - Pinterest Womens Fashion catalogue (run ```pinterest_woman_script.py```)
	 - Pinterest Mens Fashion catalogue (run ```pinterest_man_script.py```)
 
 # Downloading the images and Object Detection
 - The images can be downloaded from the image links stored in the CSV by running the ``` image_download_script.py ```
 - Code for object detection is available at this repository (https://github.com/archana1998/Clothing-Detection), and can be cloned and used by just running the ```new_image_demo.py``` script

# Learning Feature Encodings
 - To create the model, run the script `encoder_training_script.py`
 - Alternatively, download the trained model from - https://drive.google.com/file/d/1DZfGkI306fjILH67ufKVIbZ6W9sTBoGL/view?usp=sharing

# 4. Computing the Popularity Metric (PM)
 - To create and train the model, run `pm_model_train_script.py`
 - Alternatively, you can download the trained model from here - https://drive.google.com/file/d/1ZGJMAn3OVug--jsIYCohgLzM_V461059/view?usp=sharing
 - Once the model is created, you can run `pm_predictor_script.py` to predict the PM for any input image
 
 # 5. Clustering
 - For quick runover and without archiving data, download archived image data from here -  https://drive.google.com/file/d/1B4P4IvKcrv_7cxGrIAvUMslFS5S35cTm/view?usp=sharing
 - This can be done by running `clustering_script.py`
