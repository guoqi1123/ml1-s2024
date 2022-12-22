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

The final project will be a critical pillar of this course. As the lecture and homework will mostly focus on the mathematical foundation of the machine learning models, the final project will help you combine the mathematical foundation with the practical domain of these machine learning models, by writing a machine learning model and a paper yourself. 

The topic of the final project are restricted to the ten papers listed on this website. These papers are carefully selected, and contain the most famous and useful machine learning models nowadays. I understand you might want to have a more open-ended project. Unfortunately, we will be unable to provide useful feedbacks for you to learn and ensure fairness given the size of the class. However, you are encouraged to bring your own data to your project to tested your implemented machine learning model.

The final project will be **individual**, meaning everyone needs to write their own code and final report. Do not panic and feel you are on your own. As our final project will be restricted to ten papers, for each project, there will be 8 to 10 students working on it. You are encouraged to form study groups with those working on the same project. We allow and encourage discussion among students, sharing useful online resources, and providing peer-reviews of final reports. You just need to acknowledge all the help you receive. However, it is NOT allowed to use code written by other students in the class, and everyone needs to write their own report. You need to write an acknowledge section in your final report (not counted towards 10 pages) to list all help you receive from other students in the class. Every report will be graded using the same criteria.


## Requirements

The final projects requires you to re-implement the machine learning method described in the the paper we assign you, use your re-implementation to perform experiments of your choice to demonstrate the re-implementation is successful, and write a report. 

There will be code for these papers online, and you are encouraged to first play with these codes before implementing your own. Do not copy or modify any code from these existing implementations as your final project; we will be able to use code plagiarism detectors to find it. The purpose of requiring you write everything from scratch is to help you learn how to overcome practical problems that people never talk about in their papers. It is not enough to only understand the mathematical insight of a machine learning model. To build a machine learning model that works in real life, you will face a lot of problems that are not reflected in the mathematical derivation, and need to know how to tackle them. 

We understand that everyone has a different background in the field. Therefore, you can simplify the problem based on your capability. For example, you can have extra assumptions on the data your model will work on, or you can reduce the complexity of your re-implemented machine learning model, etc. You will have to clearly state what kind of simplification you have made in your final report. Don't overclaim. In academia, your integrity reputation will be severely damaged if you overstate what you can do. In his class, we will **heavily penalize** overstatement. 

Your final report will be in the form of an academic paper that needs to be in the format below. Your submitted final report will be independently reviewed by the teaching staff, and rated according to the following criteria:

- Does the paper clearly state the problem that the implemented machine learning model targets? You will have to use your own language to describe the problem. **Heavy penalty** will be added for copying (with moderate modification of) the original paper. 

- Does the paper identify and clearly descirbe similar works in the related work, and lists their advantages and disadvantages? 

- Does the paper explain the mathematical derivation well? You will have to use your own language to form the mathematical derviation. **Heavy penalty** will be added for copying (with moderate modification of) the original paper. 

- Does the paper clearly state the technical difficulties in the reimplementation and possible solutions?

- Does the paper identify, describe, and analyze the effect of different engineering practices, e.g., implementation tricks and parameter/hyperparameter choices, using scientific languages?

- Does the student train the implemented model using the dataset they select, and identify and solve issues that prevent the model from convergence? 

- Does the paper analyze the experimental behaviors of their model on selected application and compare with baselines?

- Are there sufficient experiments demonstrating the success of re-implementation? 

- Are the limitations/assumptions clearly stated in the paper? Are there overclaim?  **Heavy penalty** will be added for overclaim.

- The amount of work in the reimplementation.

- Is the paper easy to read? Are your ideas elaborated clearly?


## Instructions
Your report (aka paper) should have the following sections.

**Introduction.** In the introduction section, you need to define the problem, and justify why it is a valuable problem to investigate. In each of the topics below, you are likely going to pick one or two sub-topics to investigate. In the introduction, I want to see your explanation of why do you pick those sub-problems. You can explain their significance, e.g., by solving this problem we will gain certain insights. Think about a conference reviewer. Why would somebody accept your paper? It has to be relevant, and useful.

**Related work.** This is the literature review section. Demonstrate to me that you have read several papers, and you are able to summarize them into meaningful categories. A good literature survey should articulate the limitations of the existing work, and highlight the new findings of your work. Try not to give a laundry list of papers, because they are not very useful.

**Method.** The heading of this section is up to you. I call it “method”, but you can call it whatever you want. This is the main part of your paper. If you are proposing a new idea, you need to explain your idea. If you are studying some phenonomenon, you need to explain the insights behind the phenonomenon. A good method section should contain a few very carefully drawn figures to illustrate your ideas. Depending on the nature of your project, you may want to combine this section with the experiment section. If this appears necessary for your work, please make your best judgement.

**Experiment.** As the heading suggests, this is the place where you put all your experimental results. If you are comparing with other methods, you need to define the evaluation metric. If you conduct an ablation study, explain why your ablation study is fair and meaningful. Memember, experiments are presented in order to show evidence of anything you claim. If you claim something, you'd better have an experiment to support.

**Conclusion.** People are sometimes confused about the conclusion section. In my opinion, conclusion is not the same as summary. Yes, you need to summarize the paper in this section. But more importantly, you want to explain the limitations of your findings. You also need to suggest future directions of your work. Sometimes, you may have found some unexpected outcomes. Then in the conclusion you may want to comment on them.

**Acknowledgement.** Acknowledge all the help you receive from others throughout the project.

Every paper is unique, and so you need to make the best judgement of what to include and what not to include in the paper. The above outline is recommended, but not mandatory. However, based on my past experience in reviewing papers, serving as program chairs and journal editors, the recommended outline is quite robust. So if it is your first time writing, please consider it.

## Deadlines

Apr 30, Sunday, **4:59pm** Eastern Time.

Hard deadline. No extension.

This is the paper that we will grade.

Please submit through gradescope.

## Submission Format
Please use the official ICML 2021 LaTeX template to type your report. You can download the template at https://icml.cc/Conferences/2021/StyleAuthorInstructions

Page length: no more than 10 pages. References do not count towards the 10 pages.

No supplementary materials. All reports have to be self contained.

Do not change the margin, font size, etc.

