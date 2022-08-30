# pretrained-model-dog-classification
 
Project Goal
Improving your programming skills using Python.
In this project, you will use a created image classifier to identify dog breeds. We ask you to focus on Python and not on the actual classifier.

Description:
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.

You need to use an already developed Python classifier to make sure the participants are dogs.

Note, you DO NOT need to create the classifier. It will be provided to you. You will need to apply the Python tools you just learned to USE the classifier.

Your Tasks:
Using your Python skills, you will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".
Determine how well the "best" classification algorithm works on correctly identifying a dog's breed. If you are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example, a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly.
Time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.

# Questions regarding Uploaded Image Classification:

1. Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed? If not, report the differences in the classifications.

Answer: the model was able to identify only dog_01.jpg as labrador but its classification result actually came out to be labrador retriever


2. Did each of the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed of dog as that model architecture classified Dog_02.jpg? If not, report the differences in the classifications.

Answer: the model was able to identify the two dog images but was unable to identify the breed of dog_02.jpg


3. Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg to not be dogs? If not, report the misclassifications.

Answer: yes, they were able to classify them correctly


4. Based upon your answers for questions 1. - 3. above, select the model architecture that you feel did the best at classifying the four uploaded images. Describe why you selected that model architecture as the best on uploaded image classification.

Answer: we consider vgg to be the best model as it was able to classify the images better than the other models, although some of its classfications is not completely accurate, it still stands out from the other models
