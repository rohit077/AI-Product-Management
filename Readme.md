# Udacity | Bertelsmann Tech AI Scholarship

This challenge is the Phase II of Scholarship given by Bertelsmann via Udacity. In this phase, 1k scholars out of 15,000 participants worldwide were selected to learn further in one of fully-funded courses of Udacity's AI Product Manager Nanodegree.

It has two sections, which are the core concept and advance concept. The core concept is about Introduction to AI, Descriptive Statistic, Project Evaluation. The advance concept has three industry level projects. This type of course has a lot of quizzes, practical learnings to help us to have deeper understanding about the concept and practice by solving problems from different point of view.

I created this repository to document notes, approach to the projects and collaborations with my fellow classmates.

## AI Product Manager Nanodegree

This repo contains the project & coursework of AI Project Manager Nanodegree, where the goal is to build **a product that helps doctors quickly identify cases of pneumonia in children**. We want to build a classification system that:
* Can help flag serious cases
* Quickly identify healthy cases
* And, generally, act as a diagnostic aid for doctors

### Project 1: Create a Medical Annotation Job
This project is designed to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images; this can be used by ML engineers later on down the line to build a classification product. The main task will be to create a data labeling job using Appen's(formerly known as Figure Eight) platform. We had to create an [Appen](https://client.appen.com/sessions/new) account to complete this project using [Kaggle chest x-ray dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) designing with CML(Custom Markup Language).

![A labeled, healthy, chest x-ray image. Pay close attention to the two lungs and diaphragm (below the lungs).](https://video.udacity-data.com/topher/2019/April/5cae622b_annotated-chest-xray/annotated-chest-xray.png)

### Project 2: Build a Model
In this project, we are going to build the classification model that would serve as the backbone of this product. For this task, we used Google AutoML, an automated machine learning tool that allowed us to build the model and host it in the cloud. In order to appreciate how training data impact models, we will build models with 4 variants of the dataset. This project is designed as:
* Build a model using Google's AutoML Vision platform, and
* Understand how properties of data impact performance of models.

The four parts of the project are:
1. Create a binary classifier to detect pneumonia using chest x-rays.
2. Create an unbalanced binary classifier.
3. Create a binary classifier with dirty data.
4. Create a three-class model with the classes “normal”, “bacterial pneumonia”, and “viral pneumonia”.

![Score Threshold](https://video.udacity-data.com/topher/2019/May/5ce2fd27_score-threshold/score-threshold.png)

### Project 3: (Capstone Project) Create an AI Product Business Proposal
In this project, we had to develop a business proposal for an AI product. There are several important aspects of product development  to think about and describe, and they are exactly the topics covered in this course. The following are the six parts of the proposal:

1. The Business Goal
2. Success Metrics
3. Data
4. Model
5. Minimum Viable Product (MVP)
6. Post-MVP-Deployment

**Verify Nanodegree Certificate - https://confirm.udacity.com/CKALEJHF**
