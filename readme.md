# Diagnosis of Toxoplasmosis in Cat Feces

Toxoplasmosis is a disease resulting from infection of the parasite Toxoplasma gondii, which can be found in animals' bodies, including cats. When cats are infected with it, they normally shed the parasite through their feces. 
This is a serious threat to cat owners who are pregnant or have a compromised immune system. Even with healthy individuals, if left untreated, it can increase the risk for serious mental diseases, one of the most prominent being Schizophrenia. It can also lead to numerous other symptoms, such as seizures, blindness, and also lowered levels of dopamine which is an enorphin commonly related to happiness.
To solve this problem, I developed an image recognition algorithm that would connect to a live video feed or pictures of cat feces under a microscope. This way, it could diagnose whether a cat has toxoplasmosis in the early stages and greatly reduce the risk of both human infection and a deceased cat.

Here is a picture of my test output (it is classified correctly):
(https://imgur.com/a/BQm0pNe)

## The Algorithm

This algorithm runs by learning from all the photos (using a python code, which I have attached above) 

## Running this project

Note: my project was too big to upload onto GitHub, so the only thing I could upload onto my repository was the picture of my test output. However, here is a link to my dataset: https://zenodo.org/record/4479724#.Ytr1mezMK3I

1. To run this project:
     a. connect a photo/video/live camera feed of subject (cat feces, in this instance) under a microscope to the terminal (by wget {website} or connecting a camera).
     b. use scp to see the photo/video with the label (for me, I used *scp nvidia@192.168.55.1:/home/nvidia/jetsoninference/python/training/classification/data/final_project/testoutput.jpg ./Downloads* for my test output (using the paths throught the directories to get a test output), but the path through directories could be replaced with whatever fits the user's situation better.
     
2. For someone to run the project, they would need Googlenet and PyTorch installed. They would also need to have the dataset downloaded.

[View a video explanation here](video link)
