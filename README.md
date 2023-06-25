# Visually-Glasses-Try-on
This Python script utilizes OpenCV to create a real-time glasses try-on application. It detects faces in a live video stream from a webcam and overlays various glasses images onto the detected faces. The script leverages a pre-trained face cascade classifier and facial landmarks to accurately position the glasses on the faces.
# Requirements:
```
  Python 3.x
  OpenCV
  NumPy
```
# Clone the repository or download the script.
Install the required dependencies using pip:
``` pip install opencv-python numpy ```

Ensure that you have glasses images with alpha channels (transparency) available.
Specify the file paths for the glasses images in the glasses_images dictionary in the code.
Run the script:
python glasses_try_on.py
The script will activate the webcam and open a video window.
You will see your live video stream with faces detected and glasses overlayed on them.
To change the glasses style, modify the glasses_choice variable (options: 'Glasses 1' to 'Glasses 4').
Press 'q' to quit the application.
Feel free to experiment with different glasses images and try on virtual glasses in real-time!
