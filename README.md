# [Urban Nature Recommender](https://nbscbs.herokuapp.com/)

The Urban Nature Recommender (UNR) is an expert system that facilitates knowledge acquisition from an NBS case repository. The UNR is a hybrid system integrating a black-box Artificial Neural Network (ANN) with a white-box Case-Based Reasoning model. UNR can be accessed using this link: https://nbscbs.herokuapp.com/

The system involves:

1-	a repository that stores the information of past NBS projects;

2-	an input collection component, guiding the collection and encoding of the user’s inputs;

3-	a classifier that predicts solutions (i.e., generates a hypothesis), based on user input (target case), drawing on a pre-trained ANN model to guide the case retrieval;

4-	a case retrieval engine that identifies cases similar to the target case;

5-	a case adaption and retainment process in which the user assesses the provided recommendations and retains the solved problem as a new case in the repository.

![Figure1-01](https://user-images.githubusercontent.com/38989883/185086506-04f84384-454b-4f29-a68d-98f617f44a83.jpg)
