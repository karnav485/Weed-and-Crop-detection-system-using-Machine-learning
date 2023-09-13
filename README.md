# Weed-and-Crop-detection-system-using-Machine-learning
Created Weed (unwanted plants) and crop detection model using CNN and YOLOv3 algorithm using machine learning on agriculture image data.
The aim of this project is to distinguish between weed and crop in agriculture farming and to minimize usage of fertilizers in farming. 
Technology used: CNN, YOLOv3, Python, Pytorch, Jupyter Lab.

 # How to use this repo?

  This Repository is diveded in two part:-

    1. Training 
    2. Performig detection using pre train model
        - Using pytorch
        - Using openCV (skip installation using requirements.txt file)


## Training:-
 
 * For traning you have to make **Agriculture** folder on your google drive, open clone repo and copy all files from `Crop_weed_detection_training` folder and paste it in google drive.

 * Now from drive open crop_weed_detection.ipynb file and you will get all documentation regarding it within the file.
 * ### setting up environment:-

 * First of all you need anaconda, if you don't have click here for [Download](https://www.anaconda.com/products/individual) and install.

    * Now open Anaconda Prompt and clone this repo
   ```
   (base) C:\Users\user> git clone [https://github.com/karnav485/Weed-and-Crop-detection-system-using-Machine-learning]
    ```  
     - (Optional) If you get any error like **git is not recogize internal command** than run below command
          ```
            (base) C:\Users\user> pip install git
          ``` 
      
    * change your working directory to clone repo
      ```
      (base) C:\Users\user>cd Crop_and_weed_detection
      (base) C:\Users\user>cd Crop_and_weed_detection
      ```
    * After that you have to create environment to install require libraries. Follow the steps:-
       1. open Anaconda Prompt and write below command for install requirements.
           ```
            (base) C:\Users\user\Crop_and_weed_detection> conda create -n pytorchenv python=3.7.7
           ```
      2. After creating environment you have to activate it.
          ```
          (base) C:\Users\user\Crop_and_weed_detection> conda activate pytorchenv
         ```
      3.  Now run below command for install libraries
          ```
          (pytorchenv) C:\Users\user\Crop_and_weed_detection> pip install -r requirements.txt 
          ```
   * Now your environment is ready to roar:)
  
   * If you have any doubts feel free to ask any quesion at any time:)
  
   *  Linkdin - https://www.linkedin.com/in/arnav-kumar-503092268/
  
   *  THANK YOU
