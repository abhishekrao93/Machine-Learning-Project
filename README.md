# Problem Statement 


## Description of the Major Project
# Introduction
In the major project, we will be specifying datasets for you to work with.  You will choose a dataset from either the image domain or the language domain.  You will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset.  The statistical approaches should cover both conventional machine learning, from the first half of the unit, and deep learning from the second half.  Which methods you choose are entirely up to you; a goal of the project is for you to explore the approaches you've been taught, or perhaps beyond those, in order to build a high-performing system.

We're specifying image and language datasets as these are the types of data to which deep learning has been most extensively applied, as in the MNIST dataset used as a running example in the Geron textbook.

The image and language datasets will have an associated classification task.  The goal of your statistical learning approaches is to build models that will perform well on your chosen classification task.  To evaluate how well you do, we'll be using both a public test set and a private test set.  You'll have access to the public test set for the whole duration of the project, so you can see how well your system is performing.  The private test set, which will only be released at the end of semester for a limited period, is to see how well your system generalises to an unseen dataset.

## Project Tasks
Image Dataset and Task
For this, you'll be working with the CelebA dataset, a widely used dataset of celebrity faces.  Your task is to predict the hair colour of the celebrity, which will be one of black, brown, blond or gray.

We expect that, by default, you'll be developing your solutions under Google Colab.  Images are relatively large data items, so we've produced a cut-down version of the dataset that should not cause any problems with Colab's memory limits.  It's cut down both in terms of image size, and number of items in the dataset.  We've also removed images that are labelled with more than one colour.  This reduced dataset is available in iLearn, although you can use whatever data you like to train your model.  We also make available a devset that's separate from the training set.

For testing, there'll be a public test set and a private test set.  The public test set is the standard one used for CelebA.  The private test set will stay private.

## Language Dataset and Task
For this, you'll be working with a dataset from the Affect in Tweets task at SemEval in 2018.  We've simplifed the task there: we took the dataset EI-oc from the emotion intensity classification task, and transformed it into an emotion type classification task (i.e. just identify which one of four emotions a tweet represents: anger, fear, joy, or sadness).  The modified dataset is available in iLearn, although you can use whatever data you like to train your model.  We also make available a devset that's separate from the training set.

For testing, there'll be a public test set and a private test set.  The public test set is the test set used with EI-oc, transformed into the four-way classification task.  The private test set will stay private.

## Note
You are not restricted to using the datasets provided.  You can use any other dataset that could be useful in building your model.  This use of additional datasets could be especially helpful for your deep learning approach.

## What to Submit
You'll be submitting the following things for this project:

As often as you like, up to twice a day, you can submit predicted labels for the items in the public test set, via the Kaggle InClass competition submission.  You'll get feedback on how well your systems perform on this public test set.  You'll do this for both a conventional machine learning system and a deep learning system.  You are required to make an initial submission by Friday 1 May (changed) at the latest, for just the conventional machine learning approach.  The final submission will be on Monday 1 June.
Once, at the end of the project period (i.e. week 13), you'll submit predicted labels for items in the private test set.  This private test set will be released for a period of 8 hours on Monday 1 June, and you will have to submit predicted labels for this private test set within this 8 hour period.  At the end of this period of 8 hours, the private test set will no longer be available, and it will not be possible to submit predicted labels for it.  You can just submit your best model for this dataset (changed).
For your overall solution, you'll be submitting a Jupyter notebook with the code you used to produce your predicted labels.  You'll submit this by Friday 5 June.  You don't need to submit a Jupyter notebook for your initial submission.
Jupyter Notebook
This Jupyter notebook should contain all the code you use to train your model(s) and make predictions on the test set, for both the conventional machine learning approach and the deep learning approach.  You only need to provide the code for the final models you submitted to Kaggle for evaluation (i.e. there will be code for two models, one for the conventional ML and one for deep learning).

It should also contain text blocks with comments explaining what each segment of code does.  There should also be at least one text block discussing the choices you made in building your system.  (For example, you first tried a particular set of features with an SVM, and this performed poorly; selecting features in a different manner produced better results; your final logistic regression model performed better still, with a similar pattern of performance with respect to the features.)  The discussion should also include some reflection about the implementation and relative performance of your conventional machine learning and deep learning approaches.

There's no specific format for this.  However, I've made available a sample template notebook for reference as one possibility.

If you have used code from elsewhere, you should note this in a text block comment, with a link to that code (e.g. its URL).
