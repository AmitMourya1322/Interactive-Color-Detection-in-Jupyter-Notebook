# Interactive-Color-Detection-in-Jupyter-Notebook
 Interactive Color Extraction in Jupyter by using OpenCv
Before you read start coding make sure you have install ipywidgets , opencv libraray
to install ipywidgets  type (anaconda cmd) : pip install ipywidgets

Steps for color extraction:
Select any image as per your requirement
Create a function f and define input variable as show in video
Convert your image into rgb first (if you are going to show by using cv2 skip this step)
Note : cv2 stores image in BGR format where matplot store image in RGB format that is the reason we have convert it into RGB format
Now convert the image into HSV format (but why )
Now we have to define upper and lower limits of HSV so that we can extract a particular color (Why limits and how it works)
We can use slider (ipywidgets is use to make it) to extract a particular in opencv . But we are using matplotlib to show our image in jupyter

Youtube Link :https://youtu.be/Kr_70Uqy7l8
