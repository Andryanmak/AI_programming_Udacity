# Use a Pre-Trained Image Classifier to Identify Dog Breeds (AI_programming_with_python_Udacity)
<img width="766" alt="udacity_project" src="https://github.com/Andryanmak/AI_programming_Udacity/assets/76160546/4acfd483-f9b4-4d88-b51f-b7d4242105e8">
This is the first project I worked on while taking the 'AI Programming with Python' nanodegree program at Udacity.
#Languages/Tools
![python-original](https://github.com/Andryanmak/AI_programming_Udacity/assets/76160546/8eea6f4f-ac49-45de-9676-be404f978f0e)
![68747470733a2f2f7777772e766563746f726c6f676f2e7a6f6e652f6c6f676f732f7079746f7263682f7079746f7263682d69636f6e2e737667](https://github.com/Andryanmak/AI_programming_Udacity/assets/76160546/19c6a144-34a1-4b1f-87b8-740acd17d3ec)

## Project Description
The capstone project required us to do the following:

  1. Time the program
        -> Use Time Module to compute program runtime
  2.Get program Inputs from the user
        -> Use command line arguments to get user inputs
  3.Create Pet Images Labels
        -> Use the pet images filenames to create labels
        -> Store the pet image labels in a data structure (e.g., a dictionary)
  4. Create Classifier Labels and Compare Labels
        -> Use the Classifier function to classify the images and create the classifier labels
        -> Compare Classifier Labels to Pet Image Labels
        -> Store Pet Labels, Classifier Labels, and their comparison in a complex data structure (e.g. dictionary of lists)
  5. Classifying Labels as 'dogs' or 'not Dogs'
        -> Classify all Labels as 'dogs' or 'not dogs' using a dognames.txt file
        -> Store new classifications in the complex data structure (e.g. dictionary of lists)
  6. Calculate the Results
        -> Use Labels and their classifications to determine how well the algorithm worked on classifying images
  7. Print the Results
The tasks in 1-7 were to be repeated for each of the three image classification architectures mentioned above.
## Project Goal
The project goal was to improve our programming skills in Python utilising a created image classifier to identify dog breeds. The image classifier used a deep learning model called a convolutional neural network (CNN). The CNN had already learnt the features relevant to the identification of dogs from a dataset of 1.2 million images, ImageNet. The main focus of the project was on Python and not on the actual classifier.


# Your Tasks:
Using your Python skills, you will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".
Determine how well the "best" classification algorithm works on correctly identifying a dog's breed. If you are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example, a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly.
Time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.
For further clarifications, please check our FAQs here.

# Questions
Questions regarding Uploaded Image Classification:

1. Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed? If not, report the differences in the classifications.

Answer: Yes.


2. Did each of the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed of dog as that model architecture classified Dog_02.jpg? If not, report the differences in the classifications.

Answer: ALexNet and VGG identified Dog_01.jpg and Dog_02.jpg as 'bull mastiff'. Resnet classified Dog_01.jpg as 'bull mastiff' and Dog_02.jpg as 'french bulldog'.


3. Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg to not be dogs? If not, report the misclassifications.

Answer: All three model identified images as non-dog images. lion picture was classified correctly as tiger(I used 'lion' name to check  the working) but all three were confused in classifying toy image.
For toy image : 
		VGG : pencil, Sharpener
        Alexnet : ocarina, sweet potato
        ResNet : piggy bank, penny bank


4. Based upon your answers for questions 1. - 3. above, select the model architecture that you feel did the best at classifying the four uploaded images. Describe why you selected that model architecture as the best on uploaded image classification.

Answer: I will not choose Resnet as it missclassified the breed of Dog_02.jpg
VGG and AlexNet identified the dog images and classified them correctly. The non-dog images are classified as non-dog images. Tiger was identified as tiger but toy was identified as non-dog but all have different prediction. Even I don't know what was that. 
So given this, I will choose AlexNet according to result shown on uploaded Image Classifcation as it takes least time(0:0:1).
