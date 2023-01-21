# Benoit Muller
Master student in applied mathematics at EPFL, sepcialized in numerical analysis.
## Usefull links
[GitHub Profile](https://github.com/Benoit-Muller) –
[Linkedin profile](https://www.linkedin.com/in/benoitmueller/?locale=en_US)

## Some of my projects

### Low-rank Optimal Transport and Application to Color Transfer 
[PDF](https://benoit-muller.github.io/Low_Rank_Approximation_Techniques_Project/publication.pdf) – [GitHub repository](https://github.com/Benoit-Muller/Low_Rank_Approximation_Techniques_Project)
<br />
**Abstract:** In this project, we aim to solve an entropy regularized version of the Kantorovich optimal transport problem, by using a low-rank approximation technique on Sinkhorn algorithm. We apply the method to color transfer for images. We obtain newly colored images, and by using the low-rank approximation technique with a rank of only 4% of the dimension, we obtain visually similar images with a time computation reduced by half.

### Fairness of Decision Algorithm in Machine Learning
[PDF](https://benoit-muller.github.io/Stat_ML_Project/report.pdf)
<br />
**Abstract:** 
In this report, we present a definition of fairness associated to a predictor function in a decision problem of machine learning. We then propose a post-processing step that can be used for a binary classification, that satisfy the notion of fairness. Lastly, we apply this method on a real data set about credit card default prediction and show the benefits of this method.

### Predicting if two frames are part of the same video
`[PDF](https://benoit-muller.github.io/Predicting%20if%20two%20frames%20are%20part%20of%20the%20same%20video.pdf)`
<br />
**Abstract:** 
In this project, we tackle the problem of pre- dicting whether two frames come from the same video or not. The motivation is to assess how similar two images are, which could find applications, for instance, for story visualization or video generation. To do so, we use a dataset of videos, we define a class to dynamically extract a pair of frames from the same video or from two different ones. Then, we use the CLIP image encoder (vision transformer) to extract meaningful image features. We then implement two classification methods, a cosine similarity based approach and a neural network with two hidden layers. They take as input our pair of features, and they output the classification prediction, i.e. whether the two frames belong to the same video or not. We find that the cosine similarity method and the neural network trained for 2 epochs have approximately the same accuracy of 88%.
