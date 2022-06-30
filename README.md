## Intro

This repo includes

- slides of **basicRL** tutorials made by Judy
- reading notes and some python implementations from **Reinforcement Learning an Introduction 2nd Edition** by Sutton and Barto
- machine learning basics and their numpy examples
- some interesting extensions and papers throughout the reading

Here are some detailed notes of **basicRL**:

- [\[Basic Reinforcement Learning\]](https://ha5ha6.github.io/judy_blog/basicrl/)

- [\[Temporal-Difference Learning\]](https://ha5ha6.github.io/judy_blog/td/)

- [\[Policy Gradient and Actor-Critic\]](https://ha5ha6.github.io/judy_blog/pgac/)

Here are some classic implementations of **RL in control**:

- [\[All About Cartpole\]](https://ha5ha6.github.io/judy_blog/cartpole/)

Let me know if you found any typo or mistakes :)

## Contents of Slides

**basicRL_1** - explanations of basic RL concepts: agent-environment interactions, (discrete/continuous) states, (discrete/continuous) actions, (the art of) rewards, (deterministic/stochastic) policies, (deterministic/stochastic) dynamics, and MDP

**basicRL_2** - explanations of the goal of RL: episode, history trajectory, return, discounting factor, value functions, optimal value functions and optimal policy

**basicRL_3** - explanations of the learning mechanism of RL: Bellman equations, one-step update rules, generalized policy iteration, Q-learning and Cliff Walking example

**basicRL_4** - explanations of policy-based RL: the concepts of objective function and gradient descent using linear regression example, REINFORCE, REINFORCE-baseline in Short Corridor and Cartpole-gym example

**basicRL_5** - preparations for deep RL: logistic regression, Bernoulli distribution, Maximum Likelihood Estimation, cross entropy loss, batch, mini-batch and stochastic gradient descent and their implementations with two-feature Iris dataset

**basicRL_6** - preparations for deep RL: softmax (multiclass logistic) regression, Multinomial distribution, MLE for softmax regression, feedforward neural networks (MultiLayer Perceptron), activation functions, loss functions, optimizers for nn, back-propagation, MNIST keras example, weights visualization

**basicRL_6** - preparations for deep RL: convolution of two functions, convolution in images, convolution layer and max-pooling layer, convolutional neural networks (cnn), cnn in keras MNIST, visualizations of activations, filter visualizations of AlexNet, VGG, etc

## Interesting Papers

Dulac-Arnold, Gabriel, et al. "Deep reinforcement learning in large discrete action spaces." arXiv preprint arXiv:1512.07679 (2015).

Haarnoja, Tuomas, et al. "Learning to walk via deep reinforcement learning." arXiv preprint arXiv:1812.11103 (2018).

Frémaux, Nicolas, Henning Sprekeler, and Wulfram Gerstner. "Reinforcement learning using a continuous time actor-critic framework with spiking neurons." PLoS computational biology 9.4 (2013): e1003024.

Parisi, Simone, et al. "Long-Term Visitation Value for Deep Exploration in Sparse-Reward Reinforcement Learning." Algorithms 15.3 (2022): 81.

Sugiyama, Masashi, et al. "Geodesic Gaussian kernels for value function approximation." Autonomous Robots 25.3 (2008): 287-304.

Osogami, Takayuki, and Makoto Otsuka. "Seven neurons memorizing sequences of alphabetical images via spike-timing dependent plasticity." Scientific reports 5.1 (2015): 1-13.

Deisenroth, Marc Peter, Gerhard Neumann, and Jan Peters. "A survey on policy search for robotics." Foundations and trends in Robotics 2.1-2 (2013): 388-403.

Kober, Jens, J. Andrew Bagnell, and Jan Peters. "Reinforcement learning in robotics: A survey." The International Journal of Robotics Research 32.11 (2013): 1238-1274.

Schulman, John, et al. "High-dimensional continuous control using generalized advantage estimation." arXiv preprint arXiv:1506.02438 (2015).

Sutton, Richard S., et al. "Policy gradient methods for reinforcement learning with function approximation." Advances in neural information processing systems 12 (1999).

## Further Reading

**Neuro-Dynamic Programming** by Dimitri Bertsekas

**Algorithms for Reinforcement learning** by Csaba Szepesvari

**Markov Decision Processes in Artificial Intelligence** by Olivier Sigaud, Olivier Buffet

**Dynamic Programming and Optimal Control** by Dimitri Bertsekas

**Pattern Recognition and Machine Learning** by Christopher Bishop

**The Elements of Statistical Learning** by Jerome H. Friedman, Robert Tibshirani, and Trevor Hastie

**Machine Learning: a Probabilistic Perspective** by Kevin Patrick Murphy

**Deep Learning** by Aaron Courville, Ian Goodfellow, and Yoshua Bengio

**Optimization for Machine Learning** by Suvrit Sra, Sebastian Nowozin and Stephen J. Wright

**Convex Optimization** by Stephen Boyd, Lieven Vandenberghe

**Introduction to Autonomous Mobile Robots** by Roland Siegwart, Illah Reza Nourbakhsh and Davide Scaramuzza

**Probabilistic Robotics** by Dieter Fox, Sebastian Thrun, and Wolfram Burgard

## Useful Resources

[\[RL Course by David Silver's\]](https://www.youtube.com/watch?v=2pWv7GOvuf0)

[\[Denny Britz's GitHub repository\]](https://github.com/dennybritz/reinforcement-learning)

[\[The Deep RL Bootcamp\]](https://sites.google.com/view/deep-rl-bootcamp/lectures)

[\[RL Udacity\]](https://www.udacity.com/course/reinforcement-learning--ud600)

[\[Deep Reinforcement Learning Hands-On 1st Edition\]](https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On)

[\[Deep Reinforcement Learning Hands-On 2nd Edition\]](https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On-Second-Edition)

[\[Dive into Deep Learning\]](https://www.d2l.ai/index.html)

[\[OpenAI Baselines\]](https://github.com/openai/baselines)

[\[OpenAI Spinning Up\]](https://spinningup.openai.com/en/latest/)

[\[Berkeley AI Research Blog\]](https://bair.berkeley.edu/blog/)

[\[Mathematics For Machine Learning\]](https://github.com/mml-book/mml-book.github.io)

[\[The Mathematical Engineering of Deep Learning\]](https://deeplearningmath.org/)

[\[Marc Toussaint's teaching page \]](https://www.user.tu-berlin.de/mtoussai/teaching/)

[\[Ashwin Rao's teaching page\]](https://stanford.edu/~ashlearn/)

[\[Stanford cs231n\]](http://cs231n.stanford.edu/index.html)

[\[Stanford cs229\]](https://cs229.stanford.edu/)

[\[Stanford AI courses\]](https://ai.stanford.edu/courses/)

[\[ML Glossary\]](https://ml-cheatsheet.readthedocs.io/en/latest/index.html#)

[\[Python Programming And Numerical Methods: A Guide For Engineers And Scientists\]](https://pythonnumericalmethods.berkeley.edu/notebooks/Index.html)

[\[Wolfram Alpha\]](https://www.wolframalpha.com/)

## Useful Resources for CNN

[\[Student Notes: Convolutional Neural Networks (CNN) Introduction\]](https://indoml.com/2018/03/07/student-notes-convolutional-neural-networks-cnn-introduction/)

[\[CS231n CNN for Visual Recognition\]](https://cs231n.github.io/convolutional-networks/)

[\[How convolutional neural networks see the world\]](https://blog.keras.io/how-convolutional-neural-networks-see-the-world.html)

[\[Visualizing what convnets learn\]](https://keras.io/examples/vision/visualizing_what_convnets_learn/)

[\[Applied Deep Learning - Part 4: Convolutional Neural Networks\]](https://towardsdatascience.com/applied-deep-learning-part-4-convolutional-neural-networks-584bc134c1e2)

[\[Feature Visualization - How neural networks build up their understanding of images\]](https://distill.pub/2017/feature-visualization/)

[\[Understanding Neural Networks Through Deep Visualization\]](https://yosinski.com/deepvis)

[\[Convolutional Neural Network Visualizations\]](https://github.com/utkuozbulak/pytorch-cnn-visualizations)

[\[Inceptionism: Going Deeper into Neural Networks\]](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html)

[\[Understanding your Convolution network with Visualizations\]](https://towardsdatascience.com/understanding-your-convolution-network-with-visualizations-a4883441533b)
