---
layout: page
title: Project
parent: Assignments
nav_orders: 3
---

# Final Project

## Learning objectives of the final project
- Understands the machine learning theory behind the method 
    - Can clearly describe the method using rigorous mathematical language in the final report. 
- Can reimplement the method from scratch
    - The student should be able to reimplement the method using only basic Python packages. 
    - The student should be able to identify, describe, and analyze the effect of different engineering practices, e.g., implementation tricks and parameter/hyperparameter choices, using scientific languages.
    - The student should be able to train the implemented model using the dataset they select, and identify and solve issues that prevent the model from convergence.
- Can use the implemented method for custom applications
    - The student should be able to identify a target application of their implemented method and discover the datasets they will use for the project.
    - The student can identify baseline methods as comparison 
    - The student should be able to analyze the experimental behaviors of their model on the target application


## Logistics

The final project will be a critical pillar of this course. As the lecture and homework will mostly focus on the mathematical foundation of the machine learning models, the final project will help you combine the mathematical foundation with the practical domain of these machine learning models for a practical problem. 

The topic of the final project are restricted to the papers listed on this website. These papers are carefully selected. Each one of them contains a reasonable amount of math that you need to understand, and the reimplementation is not so straightforward even popular deep learning packages have already provided you a lot of well-packaged tools. I understand you might want to have a more open-ended project. Unfortunately, we will be unable to provide useful feedbacks for you to learn and ensure fairness given the size of the class. However, you are encouraged to bring your own data to your project to tested your implemented machine learning model.

The final project will be based on **teams**. Each team will consist of five people. Each team only needs to submit one code and final report. You will need to form the team during the first week and I will assign each team the topic on the second week. In the final report, you need to specify clearly the contribution of each team member. The final grade of each student will be the grade of your team's report & code with an individual adjustment based on your contribution. *You may lose points if your contribution is low to the project.* 

## Checkpoints

The final project is an effort throughout the semester. We will ask you submit something at each homework deadline as the checkpoint for the final project. The checkpoint will be worth certain points of the final project, so you need to start working on the project early. The planned checkpoint and their point worth are listed below. The actual checkpoints may deviate from this based on the actual progress of the class.

- Checkpoint 1. Problem Statement. Submit a one-page manuscript that rigorously explain the problem that the paper aims to solve. Answer why this problem is important and what are the applications. You want to use your own word to describe this. Closely resembling the original paper will result in heavy penalty. Due at Homework 2 deadline. (15% of the final project grade)

- Checkpoint 2. Method Description. Submit a one-page manuscript that rigorously explain the method/model of the paper. Also, answer why the proposed method is better than other methods. You want to use your own word to describe this. Closely resembling the original paper will result in heavy penalty. Due at Homework 3 deadline. (15% of the final project grade)

- Checkpoint 3. Solving a Toy Problem. Submit a one-page manuscript that demonstrates solving a toy problem using your reimplementation. A toy problem can be a very simple dataset, e.g., the MNIST, or a hypothetical problem that you create just to demonstrate that your reimplementation works. Due at Homework 4 deadline. (15% of the final project grade)

- Checkpoint 4. Submit a one-page manuscript that describe what real world problem that you propose to solve using your reimplementation, where the data comes from, and what the intended outcome is. Due at Homework 5 deadline. (15% of the final project grade)

- Final report due. Checkpoint 1 to 3 each becomes a section in the final report. Expand checkpoint 4 to include the results you obtain of solving the real world problem. (40% of the final project grade) 

## Grading criteria

Each checkpoint will be graded based on the clarity of the submitted manuscript, whether the team have a thorough understanding of the problem, and whether the team has comprehensively considered the problem they will solve. The instructor will rank the checkpoint manuscripts for each topic based on the above criteria. The grading will be based on your ranking. 

Your final report will be rated according to the following criteria:

- Does the paper clearly state the problem that the implemented machine learning model targets? You will have to use your own language to describe the problem. **Heavy penalty** will be added for copying (with moderate modification of) the original paper. 

- Does the paper identify and clearly descirbe similar works in the related work, and lists their advantages and disadvantages? 

- Does the paper explain the mathematical derivation well? You will have to use your own language to form the mathematical derviation. **Heavy penalty** will be added for copying (with moderate modification of) the original paper. 

- Are there sufficient experiments demonstrating the success of re-implementation? 

- Are the limitations/assumptions clearly stated in the paper? Are there overclaim?  **Heavy penalty** will be added for overclaim.

- The amount of work in the reimplementation.

- Is the paper easy to read? Are your ideas elaborated clearly?


## Presentation
Top teams of each topic will be invited to present their work to the class at the end of the semester. These teams may receive up to 5% bonus to the final project grade based on the quality of their presentation. Details will be announced later. 


## Instructions
Your final report (aka paper) should have the following sections.

**Problem Statement.** This is what you wrote for checkpoint 1. You may want to update it as your understanding of your paper gets deeper through the semester and make it reads smoother with the other sections.

**Method.** This is what you wrote for checkpoint 2. You may want to update it as your understanding of your paper gets deeper through the semester and make it reads smoother with the other sections.

**Experiment.** This is the place where you put all your experimental results. You will put the result of solving the toy problem and the real problem here. You want to have comprehensive description of your experiment, so that people can easily see that your reimplementation is successful and can reproduce your experiment.

**Conclusion.** People are sometimes confused about the conclusion section. In my opinion, conclusion is not the same as summary. Yes, you need to summarize the paper in this section. But more importantly, you want to explain the limitations of your findings. You also need to suggest future directions of your work. Sometimes, you may have found some unexpected outcomes. Then in the conclusion you may want to comment on them.

**Contribution Statement.** Precisely state the contribution of each team member, e.g. who write which sections of the paper, who write which functions in the code, etc. Also, state all the help you receive for the final report. 


## Deadlines

Apr 26, **11:59pm** Eastern Time.

Hard deadline. No extension.

This is the paper that we will grade.

Please submit through gradescope.

## Submission Format
Please use the official ICML 2021 LaTeX template to type your report. You can download the template at https://icml.cc/Conferences/2021/StyleAuthorInstructions

Page length: no more than 8 pages. References do not count towards the 8 pages.

No supplementary materials. All reports have to be self contained.

Do not change the margin, font size, etc.

## Topics
**Neural Ordinary Differential Equations**  
Paper: https://arxiv.org/abs/1806.07366  
Informative video about the paper: https://youtu.be/V6nGT0Gakyg
Note: Using machine learning models to describe differential processes

**Recorrupted-to-Recorrupted: Unsupervised Deep Learning for Image Denoising**  
Paper: https://openaccess.thecvf.com/content/CVPR2021/papers/Pang_Recorrupted-to-Recorrupted_Unsupervised_Deep_Learning_for_Image_Denoising_CVPR_2021_paper.pdf  
Note: Unsupervised image denoising without the presence of clean data

**Learning to Reweight Examples for Robust Deep Learning**  
Paper: https://arxiv.org/abs/1803.09050  
Note: a method to dynamically generate weights for samples when the dataset is not balanced  

**Plug-and-Play ADMM for Image Restoration: Fixed Point Convergence and Applications**  
Paper: https://arxiv.org/abs/1605.01710  
Note: an elegant method for image restoration problems in general  

