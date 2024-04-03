Project Overview:

This project focuses on implementing a machine learning model for object detection in multimodal remote sensing imagery. The approach involves training various models such as YOLOv5S, YOLOv5M, YOLOv5L, YOLOv5X, YOLOv5x6, YOLOv3, YOLOv4, and a hybrid algorithm called Super Yolo for object detection. Additionally, a super resolution branch is utilized to enhance the resolution of low-resolution input images. The resulting images display the confident scores of detected objects.



Technologies Used:

1.	Python (Anaconda distribution recommended)
2.	Jupyter Notebook
3.	Database SQLlite3
4.	HTML
5.	CSS
6.	JavaScript




Module Running:

Open the anaconda prompt 3 
Navigate to the project directory: cd SRAOD-Super Resolution Assisted Object Detection in Multimodal Remote Sensing Imagery
Run the python file app.py using the command: python app.py
Activate the environment: Anaconda activates the environment in the server http://127.0.0.1:5000/
Authentication: Signing up as a new user and log in to the environment
Input image data: Upload the image in the form of JPEG/JPG
Displaying output: Output image is displayed with the confident score of each object present in that image
Run Jupyter Notebook: jupyter notebook
Open and execute the notebooks for training the models and implementing object detection with super resolution.




Workflow:

Data Preparation:

1.	Collect multimodal remote sensing imagery and preprocess the data, including cleaning, resizing, and formatting data for training.
2.	Split the data into training, validation, and testing sets.
   
Model Training:
1.	Train the following models for object detection: YOLOv5S, YOLOv5M, YOLOv5L, YOLOv5X, YOLOv5x6, YOLOv3, YOLOv4, and SuperYolo hybrid algorithm.

Super Resolution Branch:
1.	Implement a super resolution branch to enhance the resolution of low-resolution input images.
2.	Integrate the Super Resolution Branch into the model pipeline to handle low-resolution content to high- resolution content.
   
Object Detection:
1.	Implement object detection algorithms to identify and localize objects within the multimodal remote sensing images.
2.	Process input images through the trained models.
3.	Detect objects in the images using the implemented algorithms.

Result Visualization:
1.	Display the resultant images with detected objects and their corresponding confidence scores.



Jupyter Environment
Evaluation:
1.	Evaluate the performance of the trained model using appropriate metrics. Such as Confusion Matrix, Precision graph, recall graph, F1 Score and Performance evaluation of all the objects. 
2.	Fine-tune the model parameters for better accuracy and efficiency.





Setup Instructions:

Install Anaconda:

Download and install Anaconda, a package manager, and virtual environment manager for Python.
Create Anaconda Environment:
Set up a new Anaconda environment for the project to manage dependencies.
Install Required Libraries:
Install necessary libraries such as TensorFlow, Keras, and OpenCV using Anaconda's package manager or pip.
Download Datasets:
Obtain multimodal remote sensing imagery datasets containing objects for training and testing purposes.
Run Jupyter Notebook:
Launch Jupyter Notebook and open the project notebook to access the code and execute the workflow steps.
Execute Code Cells:
Execute each code cell in the Jupyter Notebook sequentially to preprocess data, train the model, implement super resolution, perform object detection, and visualize results.
Interpret Results:
Analyse the results displayed in the output to evaluate the performance of the object detection model and the super resolution technique.


Conclusion:
The Super Resolution based Object Detection in Multimodal Remote Sensing Imagery project aims to enhance the accuracy of small object detection in remote sensing imagery by incorporating super resolution techniques. By following the provided workflow and setup instructions, users can implement and evaluate the proposed solution effectively.
