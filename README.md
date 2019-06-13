# reinforcement-learning-course
Code from exercises and other documents related to following this course can be stored here.


## Extra material for advanced reinforcement learning course

### Course information
Udemy online course "Advanced AI: Deep Reinforcement Learning in Python".  
Course link: https://www.udemy.com/deep-reinforcement-learning-in-python/  
Code: https://github.com/lazyprogrammer/machine_learning_examples/tree/master/rl2

### Necessary background knowledge
Next to general knowledge/experience with deep learning the course asks for hands-on experience with
+ Markov Decision Proccesses (MDPs)
+ Dynamic Programming, Monte Carlo, and Temporal Difference Learning to solve MDPs

The course contains a brief review section, but only enough to recap. 
The idea is to list further material for a quick introduction to the necessary background knowledge here.
But also add links to code examples, vidos, articles etc. that might be usefull during the course...

## Extra material from HSE "Practical RL" course
The "Practical RL" course by HSE and coursera contains quite a lot of interesting links, materials, code, videos etc.
The level of the course is somewhere between the 1st and 2nd Udemy/lazy-programmer RL course, so it covers a lot of the background in more detail, such as MDPs, Qlearning etc.).  
Course link: https://www.coursera.org/learn/practical-rl

+ Corresponding github repo: https://github.com/yandexdataschool/Practical_RL
Containing interesting notebooks, code, links etc. 

## Extra material (from other RL courses)
+ 'Awesome' list of RL related links: https://github.com/aikorea/awesome-rl/
+ UC Berkeley course CS294-112: http://rail.eecs.berkeley.edu/deeprlcourse/

## Extra material (miscellaneous)
### Q-learning:
+ Interactive example for q-learning (playing snake): https://italolelis.com/snake
+ Good illustrative (simplest possible) example of q-learning: https://blog.valohai.com/reinforcement-learning-tutorial-part-1-q-learning
+ Brief introduction with some pseudo-code: https://towardsdatascience.com/practical-reinforcement-learning-02-getting-started-with-q-learning-582f63e4acd9

### Q-learning with **RBFs** (radial basis functions):
+ In the mountain car example. RBFs are used to get features. See also.:   
https://pdfs.semanticscholar.org/4786/0a6648aca90e48ca9a18432b17d5da6d63fb.pdf or   
http://alborz-geramifard.com/Files/13FTML-RLTutorial.pdf


#### MDPs (Markov Decision Proccesses)
+ Quick to read, accessible blog post on MDPs: 
https://towardsdatascience.com/reinforcement-learning-demystified-markov-decision-processes-part-1-bf00dda41690

+ **NOT** quick to read, but used as resource in both the coursera/HSE and the Udemy/lazyprogrammer course:
A full textbook on reinforcement-learning by Sutton & Barto. Theory/math heavy. 
http://incompleteideas.net/book/the-book-2nd.html   
(pdf: http://incompleteideas.net/sutton/book/RLbook2018.pdf)

### Tensorflow:
The course uses Theano or Tensorflow. We'll stick to tensorflow...  
An introduction to Tensorflow is not part of the course. To get used to it, see elsewhere:
+ Documentation and tutorial links from Tensorflow itself: https://www.tensorflow.org/
+ Needs some getting used to, because Tensorflow works based on computational graphs (https://adventuresinmachinelearning.com/python-tensorflow-tutorial/).  
This, however, seems to change! Current versions already allow to avoid the static graphs by using the Eager API (https://adventuresinmachinelearning.com/tensorflow-eager-tutorial/).  
In the upcoming Tensorflow 2.0, the **Eager execution will apparently even become the standard!**
