---
layout: page
title: Project
parent: Assignments
nav_orders: 3
---

# Final Project

## Updates: Final Project Logistics

Based on last week's survey, final project will still be **individual** project. Meanwhile, certain "collaborations" will be encouraged. This includes discussion among students, sharing useful online resources, and providing peer-reviews of final reports. However, it is NOT allowed to use code written by other students in the class, and everyone needs to write their own report. You need to write an acknowledge section in your final report (not counted towards 10 pages) to list all help you receive from other students in the class. Every report will be graded using the same criteria.

The goals of the final project are to maximize everyone's learning experiences and ensure fairness. In the survey, the majority (79.5%) of the class expressed preference to do final projects on their own. Many expressed concern of fairness of allowing pair projects, which includes concern of unfair grading criteria for pairs and free-riders. Meanwhile, some proposed ideas of getting peer-feedbacks from each other. Therefore, I decide to keep the previous format of individual final project, but I will encourage students
to interact with each other in the aforementioned ways. 

There is also a popular voice in the survey to broaden topics for the project. Unfortunately, in this way we will not be able to provide useful feedbacks for you to learn and ensure fairness given the size of the class. However, you are encouraged to bring your own data to your project as long as the machine learning models you use belong to the four topics we list below. 


## Overview
The course has an open-ended project, with the objective of giving you an opportunity to learn something hands-on. My expectation on your projects is high. It is not because that I want to give you a hard time, but it is because that I hope to bring you one step closer to the machine learning community. (Yes, by the machine learning community I really mean the real one. There are many gobbly goop in our times, and you know what I mean.) If your career goal is to pursue a data science, computer vision, or deep learning type of jobs, it is better to understand their expectations sooner than later.

With this goal in mind, I will aim for a standard in par with ICML, NeurIPS, ICLR, CVPR, ICCV, ECCV, etc. I will ask you to write a 10-page paper. The teaching staff will act like the reviewers of your paper.

You need to choose one of the topics below. There are specific suggestions for each topic.

## Instructions
Your report (aka paper) should have the following sections.

**Introduction.** In the introduction section, you need to define the problem, and justify why it is a valuable problem to investigate. In each of the topics below, you are likely going to pick one or two sub-topics to investigate. In the introduction, I want to see your explanation of why do you pick those sub-problems. You can explain their significance, e.g., by solving this problem we will gain certain insights. Think about a conference reviewer. Why would somebody accept your paper? It has to be relevant, and useful.

**Related work.** This is the literature review section. Demonstrate to me that you have read several papers, and you are able to summarize them into meaningful categories. A good literature survey should articulate the limitations of the existing work, and highlight the new findings of your work. Try not to give a laundry list of papers, because they are not very useful.

**Method.** The heading of this section is up to you. I call it “method”, but you can call it whatever you want. This is the main part of your paper. If you are proposing a new idea, you need to explain your idea. If you are studying some phenonomenon, you need to explain the insights behind the phenonomenon. A good method section should contain a few very carefully drawn figures to illustrate your ideas. Depending on the nature of your project, you may want to combine this section with the experiment section. If this appears necessary for your work, please make your best judgement.

**Experiment.** As the heading suggests, this is the place where you put all your experimental results. If you are comparing with other methods, you need to define the evaluation metric. If you conduct an ablation study, explain why your ablation study is fair and meaningful. Memember, experiments are presented in order to show evidence of anything you claim. If you claim something, you'd better have an experiment to support.

**Conclusion.** People are sometimes confused about the conclusion section. In my opinion, conclusion is not the same as summary. Yes, you need to summarize the paper in this section. But more importantly, you want to explain the limitations of your findings. You also need to suggest future directions of your work. Sometimes, you may have found some unexpected outcomes. Then in the conclusion you may want to comment on them.

Every paper is unique, and so you need to make the best judgement of what to include and what not to include in the paper. The above outline is recommended, but not mandatory. However, based on my past experience in reviewing papers, serving as program chairs and journal editors, the recommended outline is quite robust. So if it is your first time writing, please consider it.

## Deadlines
The project will be graded in a two-phase process.

**Phase 1:** Initial Submission (Optional)

Apr 17, Sunday, **4:59pm** Eastern Time.

This submission is voluntary.

If you like to receive initial feedback from the teaching staff, you can submit in this phase.

The teaching staff will give you some rough suggestions, of whether you are on track, or if there are things you need to improve.

To participate in the initial submission cycle, you need to really write a full paper. If you submit only an abstract or a half-way done paper, we will not offer any feedback.

The teaching staff will read and offer suggestions by Apr 22.

Please submit through gradescope.

**Phase 2:** Final Submission

May 2, Monday, **4:59pm** Eastern Time.

Hard deadline. No extension.

This is the paper that we will grade.

Please submit through gradescope.

## Grading Criteria
Review Process:

Each report will be graded by the instructor and the TA independently according to the following criteria:

- How well do you understand the literature?

- What are the new findings you have?

- Is there any innovative ideas?

- How deep is your analysis?

- Are the experimental results complete?

- Do you have justification for things you claim?

- Is your paper easy to read? Are your ideas elaborated clearly?

## Research opportunities beyond the course:

Depending on how much you have accomplished and how much innovations you have demonstrated, I may encourage you to submit your project paper to real conferences.

I am always looking for good students. This could be an opportunity for you to demonstrate your capability.

## Submission Format
Please use the official ICML 2021 LaTeX template to type your report. You can download the template at https://icml.cc/Conferences/2021/StyleAuthorInstructions

Page length: no more than 10 pages. References do not count towards the 10 pages.

No supplementary materials. All reports have to be self contained.

Do not change the margin, font size, etc.

This is an individual project. If you work with a friend, acknowledge the person. You need to write your own report.

## Topic 1: Self-supervised learning for image denoising
(Tag: Deep learning, experimental, image processing.)

Self-supervised learning is gaining some good momentum over the past 2-3 years. One of the things that catches my attention is noise2noise. What the paper says is that in the context of image denoising, instead of training the model via clean-noisy pairs, we use noisy-noisy pairs. The idea is interesting, and the results look promising. It will be a good project to explore.
You can explore one or more of the following problems:
- Re-implement Noise2Noise, and test the performance limit as noise level increases.

- Comparison with supervised learning approaches.

- Does the model capacity affect the generalization? Ie, if we use a bigger model, will we do better?

- Does noise2noise work for other types of noise?

- Can we do noise2noise for dynamic scenes?

- Propose new methods to improve the existing approaches, in terms of better reconstruction quality.

Main Reference:

- [Noise2Noise: Learning Image Restoration without Clean Data](https://arxiv.org/abs/1803.04189)

Other References:

- [Dynamic Low-light Imaging with Quanta Image Sensors](https://arxiv.org/abs/2007.08614)

- [Image Classification in the Dark using Quanta Image Sensors](https://arxiv.org/abs/2006.02026)

- [Learning to See in the Dark](https://arxiv.org/abs/1805.01934)

## Topic 2: Plug-and-Play Analysis
(Tag: Classical, experimental, can be theoretical, inverse problem.)

I was fortunate to be one of the first researchers working on the Plug-and-Play ADMM algorithm, which turned out to be a useful tool in the computational imaging community today. Many of my colleagues (at Purdue and in other instuitions) are making very good progress to this problem. Despite the many great progress that has been made, I have a (small) conjecture/question that I have not been able to conclude: Does a better denoiser give us a better PnP algorithm?

I need to define what is good. A denoiser is better than another denoiser when the mean squared error on testing is uniformly lower at each testing noise level. Think about a DnCNN and a non-local means. The former is a deep neural network whereas the latter is a deterministic algorithm. If you test them at a noise level of 10 out of 255, you can see that DnCNN is better. If you test them at a noise level of 50 out of 255, DnCNN is still better. In fact, no matter what noise level you test, DnCNN is always better. So we say that DnCNN is uniformly better than non-local means.

So, if we plug DnCNN into the PnP framework, will it always generate a better PnP solution? Intuitively I would think yes. But my dear friend Charlie Bouman has been very skeptical about this. I do not know the answer, but I think it would be worth of exploring.

Since this is an open ended problem, I expect you to explore the different facets of the problem, instead of aiming to reach a YES or NO conclusion. I am suggesting a few directions you can explore. You can pick one or more to investigate.

- Develop a comprehensive comparison among different denoisers, for several standard inverse problems.

- Train the same denoiser with different model capacity, and report your findings.

- Fix the model, but train it using different number of training samples. See what will happen.

- Theoretical derive some results, if you are able to.

- Perhaps create a counter example to prove that this conjecture is wrong.

Main Reference:

- [Plug-and-Play ADMM for Image Restoration: Fixed Point Convergence and Applications](https://arxiv.org/abs/1605.01710)

- [Performance Analysis of Plug-and-Play ADMM: A Graph Signal Processing Perspective](https://arxiv.org/abs/1809.00020)

Other References:

- [An Online Plug-and-Play Algorithm for Regularized Image Reconstruction](https://arxiv.org/abs/1809.04693)

- [The Little Engine that Could: Regularization by Denoising (RED)](https://arxiv.org/abs/1611.02862)

- [Provable Convergence of Plug-and-Play Priors with MMSE denoisers](https://arxiv.org/abs/2005.07685)

- [Software package by Charlie Bouman](https://engineering.purdue.edu/~bouman/Plug-and-Play/)

- [MATLAB implementation](https://www.mathworks.com/matlabcentral/fileexchange/60641-plug-and-play-admm-for-image-restoration)

## Topic 3: Consistent adversarial training for defending against attacks
(Tag: Deep learning, experimental, adversarial attack, sample distribution.)

In Part 4 of our course we study adversarial attack. We have studied various ways to attack, and various ways to defend. The objective of this project is to study a related problem.

Let us use projected gradient descent by Madry et al. as the main attack strategy, and adversarial defense as the main defense strategy. For simplicity you can report results on the MNIST or the CIFAR datasets. You can pick a simple model (eg a few convolutional layers) or more classical approaches.

Imagine that you do adversarial training to your model. If you adversarially train your model by assuming a specific attack strength, say epsilon = 0.1, you will do very well for attacks with strength of epsilon = 0.1. As soon as the attack is stronger (or weaker) than this trained level, your defense will not be as effective. The project asks the question: Can we do adversarial training across several attack strengths, while maintaining a consistent performance?

This project is an extension of an ICML 2020 paper my student Abhiram did. We worked on the standard denoising problem, and I think it will be interesting to see how much benefit it can offer to adversarial training. Specifically, you can explore one or more of the following questions:

- Confirm that the same phenomenon reported in our ICML 2020 paper also appears in adversarial attack.

- Re-implement our ICML 2020 paper, in the context of adversarial training.

- Instead of adjusting the training sample allocation, consider adjusting the loss function.

- Propose a new idea that can improve our paper.

Main Reference:

- [One Size Fits All: Can We Train One Denoiser for All Noise Levels?](https://arxiv.org/abs/2005.09627)

Other References:

- [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083)

- [MNIST challenge dataset and code](https://github.com/MadryLab/mnist_challenge)

## Topic 4: Learning in the presence of label noise
(Tag: Classical / deep learning, experimental, label noise.)

In modern datasets, it is quite common to see that some samples are mis-labeled. Through my interactions with the industry, this problem appears to be a very big issue because the models can suffer a lot. How do we do supervised learning when the labels are wrong?

Learning from noisy labels is big topic. You can easily find a lot of papers in this area. Since many of you are beginners to the problem, I think it will be educationally most valuable if you can study one or two representative paeprs to gain some ideas. Here I am suggesting two papers (please choose one):

- [Learning to Reweight Examples for Robust Deep Learning.](https://arxiv.org/pdf/1803.09050.pdf)  
This paper is more experimental. You can consider studying one or more of the followings:

    - Re-implementing their method, and try to reproduce their results.

    - Download their code, and fine-tune it on another dataset.

    - Investigate the limit of this method. That is, when will it fail?

    - Propose improvements.

- [Learning with Noisy Labels](https://proceedings.neurips.cc/paper/2013/file/3871bd64012152bfb53fdf04b401193f-Paper.pdf)  
This is a theoretical paper, but they have some non-deep neural network experiments. You can explore one or more below:

    - Try to explain the core ideas behind the theory.

    - See if you can reproduce their synthetic experiments using SVM.

    - Perhaps try another linear classifier.

Other References:
- [Github for learning to reweight](https://github.com/uber-research/learning-to-reweight-examples)



