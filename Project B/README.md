# Knowledge Distillation project

Project B for ECE 1512

## Information on models-
all the pre trained models are located with the mhist_dataset folder-
1. teacher_res_new- teacher model used for normal knowledge distilation
2. student_mobile- student model train with knowledge distilation
3. mobilenet_no_kd_new- student model trained without Knowledge distilation
4. teacher_test- teacher used for fitnets

## Information on dataset-
the dataset is located in the mhist_dataset folder-
the annotations.csv file is used to split and label all the images in the images folder.

## Information on how to run the notebooks
For both notebooks **Task 1** and **Task 2** -
We recommend running it on Google Colab- for this you will have to download the Project A folder from the repository and upload mhist_dataset into your drive.
After that you will need to change the paths of the **project folder**, **datasets** and **the models** in the code to your locations in your drive. Finally when running the code you can either train the models from scratch or use the pre trained models.


Here are the explanation of the what it is included in the Supplementary file:


    1. mhist_dataset is a folder containing two subfolders, including the images and their annotations, for the MHIST dataset. All 3152 images are in images.zip file. Annotations are included in annotations.csv. Note that this file includes each image file name and its corresponding majority-vote label and degree of annotator agreement expressed as the number of annotators who marked the image as SSA (e.g., 6 indicates 6/7 agreement with a ground truth of SSA and 2 would indicate 5/7 agreement with a ground truth of HP).

    2.Task1.ipynb is a Python notebook showing how the teacher and student models are training in conventional KD framework. You will use this file to implement conventional KD for MNIST dataset.

    3. Project_B_FAQs.pdf is a list of Frequently Asked Questions which try to throw light on (almost) all of your questions and concerns which you may have during the course of Project B.


