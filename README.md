This is an *unofficial* web-home for the University of Edinburgh's ML-for-NLP reading group. 

This reading group focuses on Machine Learning techniques that may be applied to the field of Natural Language Processing. Participants are encouraged to suggest topics, papers, or tutorials (which need not involve any current application in NLP).

We also have an ML-for-NLP channel in IF slack http://web.inf.ed.ac.uk/infweb/admin/communications/useful-links

### Paper proposal
To propose a paper for a weekly meeting open an issue or add a comment to an existing one. 
At the end of the week (Friday) the paper with the most votes will be chosen (vote using thumbs-up in a comment).
Suggesting a paper does not constitute any sort of commitment to presenting that paper.


### Time and place
Meetings are approximately every week on Mondays at 15:00 (GMT+1) unless otherwise stated. Announcements for this group will be made by email, and it is possible to sign up to the mailing list [here](http://lists.inf.ed.ac.uk/mailman/listinfo/ml-for-nlp).

The meetings usually take place in the Informatics forum room 3.02, but during the covid-19 lockdown the meetings have moved online: https://meet.google.com/jie-cnji-dok

---

## June 29, 2020

Propose/vote a paper here: https://github.com/cbaziotis/ml-for-nlp/issues/1


## June 22, 2020

**Paper**: [Bootstrap Your Own Latent: A New Approach to Self-Supervised Learning](https://arxiv.org/abs/2006.07733)

**Abstract**: We introduce Bootstrap Your Own Latent (BYOL), a new approach to self-supervised image representation learning. BYOL relies on two neural networks, referred to as online and target networks, that interact and learn from each other. From an augmented view of an image, we train the online network to predict the target network representation of the same image under a different augmented view. At the same time, we update the target network with a slow-moving average of the online network. While state-of-the art methods intrinsically rely on negative pairs, BYOL achieves a new state of the art without them. BYOL reaches 74.3% top-1 classification accuracy on ImageNet using the standard linear evaluation protocol with a ResNet-50 architecture and 79.6% with a larger ResNet. We show that BYOL performs on par or better than the current state of the art on both transfer and semi-supervised benchmarks.


## June 15, 2020

**Paper**: [Residual Energy-Based Models for Text Generation](https://openreview.net/forum?id=B1l4SgHKDH)

**Short talk**: https://iclr.cc/virtual_2020/poster_B1l4SgHKDH.html

**TL;DR**: We show that Energy-Based models when trained on the residual of an auto-regressive language model can be used effectively and efficiently to generate text.

**Keywords**: energy-based models, text generation

**Abstract**: Text generation is ubiquitous in many NLP tasks, from summarization, to dialogue and machine translation. The dominant parametric approach is based on locally normalized models which predict one word at a time. While these work remarkably well, they are plagued by exposure bias due to the greedy nature of the generation process. In this work, we investigate un-normalized energy-based models (EBMs) which operate not at the token but at the sequence level. In order to make training tractable, we first work in the residual of a pretrained locally normalized language model and second we train using noise contrastive estimation. Furthermore, since the EBM works at the sequence level, we can leverage pretrained bi-directional contextual representations, such as BERT and RoBERTa. Our experiments on two large language modeling datasets show that residual EBMs yield lower perplexity compared to locally normalized baselines. Moreover, generation via importance sampling is very efficient and of higher quality than the baseline models according to human evaluation.


## June 4, 2020

**Paper**: [Your Classifier is Secretly an Energy Based Model and You Should Treat it Like One](https://arxiv.org/abs/1912.03263)

**Abstract**: We propose to reinterpret a standard discriminative classifier of p(y|x) as an energy based model for the joint distribution p(x,y). In this setting, the standard class probabilities can be easily computed as well as unnormalized values of p(x) and p(x|y). Within this framework, standard discriminative architectures may beused and the model can also be trained on unlabeled data. We demonstrate that energy based training of the joint distribution improves calibration, robustness, andout-of-distribution detection while also enabling our models to generate samplesrivaling the quality of recent GAN approaches. We improve upon recently proposed techniques for scaling up the training of energy based models and presentan approach which adds little overhead compared to standard classification training. Our approach is the first to achieve performance rivaling the state-of-the-artin both generative and discriminative learning within one hybrid model.

Here some extra material for preparing:
 - http://yann.lecun.com/exdb/publis/pdf/lecun-06.pdf
 - https://www.youtube.com/watch?v=A7AnCvYDQrU&t=3071s


