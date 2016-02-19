---
title: Rutgers ML Reading Group
layout: default
---

# Rutgers Machine Learning Reading Group

>A talk series and reading group for deep networks and other machine learning topics.
>Meetings are weekly on Thursdays at 5 pm (2016 Spring) in CBIM.

* TOC
{:toc}


## Upcoming Schedule

| Date | Person | Information |
| ---  | ---  | --- |
| Jan 28 | Dong Yang | [Fully convolutional networks for semantic segmentation](http://arxiv.org/abs/1411.4038)|
|||[Semantic image segmentation with deep convolutional nets and fully connected crfs](http://arxiv.org/abs/1412.7062)|
|||[Learning Deconvolution Network for Semantic Segmentation](http://arxiv.org/abs/1505.04366)|
| Feb 9(Special, 5pm) | Mohamed Elhoseiny | [Zero-Shot Event Detection by Multimodal Distributional Semantic Embedding of Videos](http://arxiv.org/abs/1512.00818) |
| Feb 11 | Babak Saleh | [Toward a Taxonomy and Computational Models of Abnormalities in Images](http://arxiv.org/abs/1512.01325) |
| Feb 18 | Aditya Chukka | [Unifying distillation and privileged information](http://arxiv.org/abs/1511.03643) |
| Feb 25 | Brian McMahan | [Deep Compositional Question Answering with Neural Module Networks](http://arxiv.org/abs/1511.02799) [Learning to Compose Neural Networks for Question Answerin](http://arxiv.org/abs/1601.01705)|
| Mar 3 |  | |
| Mar 10 |  | |
| Mar 17 | Qi Chang | Ischemic Stroke Detection using Image Processing and ANN |
| Mar 24 | Shailesh Goel | |
| Mar 31 | Debanjan Ghosh | |
| April 7 | Han Zhang | |
| April 14 | Colin Rennie | |
| April 21 | Zacharias Psarakis | |



## Reading Stack
>*put interesting papers here that people can choose from or know about*

#### Tutorials
1. [Caffe]( http://tutorial.caffe.berkeleyvision.org/)
2. [Deeplearning.net tutorials](http://deeplearning.net/reading-list/tutorials/)

#### RNN (theory and hands-on)
[Neural Turing Machines](http://arxiv.org/abs/1410.5401) Alex Graves, Greg Wayne, Ivo Danihelka

[An Empirical Exploration of Recurrent Network Architectures](http://machinelearning.wustl.edu/mlpapers/paper_files/icml2015_jozefowicz15.pdf)  JOZEFOWICZ, ZAREMBA, SUTSKEVERAR

[hands on torch demo for LSTM from oxford machine learning class](https://github.com/oxford-cs-ml-2015/practical6/blob/master/practical6.pdf)



#### Memory Networks
[Memory Networks](http://arxiv.org/abs/1410.3916) Jason Weston, Sumit Chopra, Antoine Bordes

[End-To-End Memory Networks](http://arxiv.org/abs/1503.08895) Sainbayar Sukhbaatar, Arthur Szlam, Jason Weston, Rob Fergus

#### Deep Learning Theory
1. [On the saddle point problem for non-convex optimization](http://arxiv.org/abs/1405.4604)
    - Related: [ Identifying and attacking the saddle point problem in high-dimensional non-convex optimization](http://arxiv.org/abs/1406.2572)

#### Structured Prediction
1. [State of the art on structured regression using deep models - Advances in Structured Prediction](http://icml.cc/2015/tutorials/AdvancesStructuredPrediction.pdf)

#### Semantic Segmentation
1. [Semantic Image Segmentation via Deep Parsing Network](http://arxiv.org/abs/1509.02634)

#### Attention-based models

#### Bayesian Neural Networks

#### Variational Inference & Variational Autoencoders

#### Image Captioning
1. [Image captioning with emotion](http://arxiv.org/pdf/1510.01431.pdf)

#### Hallucination & Dreaming

#### Deep Networks & NLP
1. [Learning Distributed Word Representations for Natural Logic Reasoning](http://arxiv.org/abs/1410.4176)
2. [Skip-Thought Vectors](http://arxiv.org/abs/1506.06726)
3. [A Diversity-Promoting Objective Function for Neural Conversation Models](http://arxiv.org/pdf/1510.03055.pdf)
4. [Do Deep Nets Really Need to be Deep?](http://papers.nips.cc/paper/5484-do-deep-nets-really-need-to-be-deep)

#### Kernel Methods
1. [A new learning paradigm: Learning using privileged information](http://www.sciencedirect.com/science/article/pii/S0893608009001130)

#### Datasets
1. [Vision and Language](http://visionandlanguage.net/)

#### Other links
1. The awesome series
    - [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
    - [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision)
    - [Awesome RNN](https://github.com/kjw0612/awesome-rnn)
2. [Colah's Blog](http://colah.github.io/)

## Past Meetings
| Date | Person | Information |
| ---  | ---  | --- |
| October 26th | Shaojun Zhu | **Recent applications of deep learning in robotics<br>(Perhaps focusing on grasping)**  <br> Some relevant papers: [[1]](http://arxiv.org/pdf/1301.3592.pdf)[[2]](http://arxiv.org/abs/1412.3128)[[3]](http://www.cs.columbia.edu/~allen/PAPERS/iros15_grasp_varley.pdf)[[4]](http://arxiv.org/pdf/1509.06825v1.pdf)[[5]](http://arxiv.org/pdf/1504.00702v3.pdf).  <br>[1-4] are on detecting grasping locations for robots using deep learning.  The last one for Pieter Abbeel's group in Berkeley is more interesting in the sense that it tries to learn control policies directly from visual input.  His group is one of the first advocates for deep learning in robotics and has a series of related work.  I have not read about it in details, so I may not cover it this time. |
| November 9th | Yan Zhu | **RNN and memory network**<br>I will basically go over these two excellent blogs: [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) by Andrew Karpathy and [Understanding LSTM networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) by Christopher Olah. Then will cover my understanding for the memory networks (see the reference paper below). | 
| November 16th | Brian McMahan | **Reinforcement Learning with Neural Nets**<br>I will discuss the recent improvements of neural networks and reinfrocement learning. Specifically, I will go over [Willians (1992)](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf) who introduced the REINFORCE algorithms for combining reinforcement learnign with neural network backpropagation.  This is the algorithm that underlies the model of [Minh, Heess, Graves, and Kavukcuoglu (2014)](http://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf): Recurrent Models of Visual Attention. If there is time or interest, I will also talk about [Deep-Q learning](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf). I can also do an overview of RL if there is interest. |
| November 23rd | Babak Saleh | "A Unified Framework for Fine-art Painting Classification". In this talk I will go through some basics in "Metric Learning", and show their applications in my research on fine-art painting analysis.|
| November 30th | Amr Bakry | This talk will be about the work during my PhD on using Image Manifold Analysis for solving couple of computer vision problems. More specifically, I will talk about lip-reading in videos and object recognition and pose estimation in images. | 
| December 7th | Chetan Tonde | "Do Deep Nets Really Need to be Deep?" and "A new learning paradigm: Learning using privileged information" related papers presented together.|

## Members and their presentation dates <br> (upcoming and archived)
> [copy-pastable email list here](/private/rml_members.html)

| Person | Dates |
| ------ | ----- |
| Shaojun Zhu | |
| Dong Yang | |
| Yan Zhu | | 
| Brian McMahan | |
| Babak Saleh | |
| Amr Bakry | |
| Ramakanth Vemula | |
| Malihe Alikhani | |
| Abhijit Shanbhag | |
| Ana Echavarria Uribe | |
| Shahab Raji | |
| Aditya Chukka | |
| Behnam Babgholami Mohamada | |
| Alireza Naghizadeh | |
| Rajyavardhan Handa | |
| Qi Chang | |
| Bhuvan Chandra Inampudi | |
| Han Zhang | |
| Teng Long | |
| Chetan Tonde | |
| Shailesh Goel | |
| Debanjan Ghosh | |
| Mohamed Elhoseiny | |
| Colin Rennie | |
| Zacharias Psarakis | |


## Rules

1. Members of the reading group will take turns presenting a paper or their own work to the group
2. There are no 'bystander' attendees.  
3. Presenting a paper does not have to be an immense endeavor.  Reading a paper and telling the group what it is about is necessary and sufficient.

### FAQ
1. How is the presenters' order generated?
    - The presenters' order is generated from the member list in a FIFO manner. 
2. Who is responsible if I can not present at the schedule time?
    - Yourself.  
3. What should I do if I can not present at the scheduled time?
    - First, let the organizer know your situation, as early as possible.  Second, contact other presenters on the list and see if they are willing to swap with you.
4. What happens if a new event takes place and we have to change the schedule?
    - To minimize disturbance, the conflicted spot will be moved to the rear of the list after confirmed with the original presenter, while all other schedules remain unchanged.  
5. How do I do X?
    - [There is a how to page](http://ada.cs.rutgers.edu/howto.html)
    - If something isn't on there, email vincentzhu122[at]gmail[dot]com or brian[dot]c[dot]mcmahan[at]gmail[dot]com

