# Data Science Crash-Course
As part of my continued research for automated testing, I've created a compilation of online resources from colleagues, data scientists, QA testers, and more that I believe is thorough to get started on machine learning and testing.  This list is a work in progress, and I expect to add more resources over time.

![Alt Text](https://media.giphy.com/media/OFIsBxe3v7mKI/giphy.gif)

## Getting started with Python
Python lays down the foundation in a language that is more popular with data science.  Most data science materials out there is taught in Python - even if you're familiar with the language, getting a solid foundation in Python syntax will help you understand the intricasies of working with a dynamic language in scripting.

https://www.codecademy.com/learn/learn-python

 In addition to the fundamental data structures, understanding Pandas and data frames and translating those into other languages becomes challenging, the fundamental building blocks of AI.  Haven't found materials for that yet but will update when I get the chance. 

## Stats and Machine Learning

### MIT 6.0002 Introduction to Computational Thinking and Data Science
Shoutout to MIT for posting their full course online on YouTube - hooray for accessibility for computer science education! Each lecture is roughly 50 minutes and there's a total of 15. So far, I really like the contents of this course. I've personally hated everything stats/modeling-related and not only does MIT have a habit of explaining things simply, but they take a computer science approach that revolves data structures around real-world problems.  My kind of psuedo-science!

**Playlist**: https://www.youtube.com/playlist?list=PLUl4u3cNGP619EG1wp0kT-7rDE_Az5TNd

**Corresponding Notes and Python Files to Lectures:** https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0002-introduction-to-computational-thinking-and-data-science-fall-2016/lecture-slides-and-files/

**Topics Covered**
 1.  Introduction and Optimization Problem
 2.  Optimization Problems
 3.  Graph-theoretic Models
 4.  Stochastic Thinking
 5.  Random walks
 6.  Monte Carlo Situation
 7.  Confidence Intervals
 8.  Sampling and Standard Error
 9.  Understanding Experimental Data
 10. Understanding Experimental Data (cont.)
 11. Introduction to Machine Learning
 12. Clustering
 13. Classification
 14. Classification and Statistical Sins
 15. Statistical Sins and Wrap Up

### Thomas Nield's Kotlin Science Data Resources 
Data Science for statically-typed folks (those with Java or Kotlin backgrounds). 

https://github.com/thomasnield/kotlin-data-science-resources

### Jeff Nymen's __Stories from a Software Tester__ & his series on Machine Learning
* [Demystifying Machine Learning, Part 1](http://testerstories.com/2018/09/demystifying-machine-learning-part-1/)
* [Demystifying Machine Learning, Part 2](http://testerstories.com/2018/09/demystifying-machine-learning-part-2/)
* [Demystifying Machine Learning, Part 3](http://testerstories.com/2018/09/demystifying-machine-learning-part-3/)
* [Demystifying Machine Learning, Part 4](http://testerstories.com/2018/09/demystifying-machine-learning-part-4/)
* [Demystifying Machine Learning, Part 5](http://testerstories.com/2018/09/demystifying-machine-learning-part-5/)
* [Demystifying Machine Learning, Part 6](http://testerstories.com/2018/09/demystifying-machine-learning-part-6/)

### Kaggle
[Kaggle](https://www.kaggle.com/) is a platform for predictive modeling and analytics competitions in which companies and researchers post data and statisticians and data miners compete to produce the best models for predicting and describing the data.

### Tensorflow Learn and Use ML
* [Basic Classification](https://www.tensorflow.org/tutorials/keras/basic_classification)
* [Text Classification](https://www.tensorflow.org/tutorials/keras/basic_text_classification)


### Google Developers Guide to Machine Learning
* [Rules of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml/)
* [Text Classification](https://developers.google.com/machine-learning/guides/text-classification/)

### Convolutional Neural Networks (CNN)
* [Convolutional Neural Networks explained](https://deeplizard.com/learn/video/YRhxdVk_sIs)
* Most popular for analyzing images
* Some kind of neural networking that has some type of specialization for being able to detect patterns

What makes CNN stand out from a multilayered perceptron (MLP)?
    * A CNN has hidden layers, or convolutional layers. They may also have non-convolutional layers
* What do convolutional layers do?
    * Just like any other layer, a convolutional layer receives input then  transforms the input in some way and then outputs the transform input to the next layer
    * With the convolutional layer, the transform is a convolution operation
    * With each convolutional layer we need to specify the number of layers a filter should have. These filters are what are able to be able to detect patterns
        * What kind of patterns?
            * Edges (Edge detectors) - circles, squares, edges
            * Deeper layers can detect more sophisticated objects
    * A filter is a matrix where the value of the matrix are initialized with random numbers.
        * That filter, whatever the initialized form is (i.e 3 x 3) will slide over every possible block (3 x 3 set) of pixels in an image: the sliding of the image convolves 
        
 * [Practical Deep Learning for Coders: Collaborative Filtering, Embeddings, and More](https://www.youtube.com/watch?v=V2h3IOBDvrA)
 * Take this one with a grain of salt: [StackOverflow: Analysis of Convoluted Layers (for a first layer)](https://stackoverflow.com/questions/959524/basic-complexity-question-convolution)



