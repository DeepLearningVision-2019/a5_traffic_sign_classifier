# Assignment 5: Traffic Sign Classifier

---

Using computer vision, deep learning, and convolutional neural networks, create a pipeline that classifies traffic signs.  Train and validate a model so it can classify traffic sign images using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). After the model is trained, test it on images of traffic signs that you find on the web.

The goals of this project are the following:

- Load the data set
- Explore, summarize and visualize the data set
- Design, train and test a model architecture
- Use the model to make predictions on new images
- Use data augmentation and transfer learning
- Analyze the softmax probabilities of the new images
- Summarize the results of each step with a written report

The writeup should be included in additional cells within the notebook. Some sample cells are included so that you have a guide of what is expected of the writeup. Additionally, add a README file with an introduction to what you developed, as well as the steps needed to run it.

**Notes:** 
- Unless you have set up a GPU on a desktop with all the needed packages, train the model using a GPU enabled google colab environment.
- Once you have completed all of the code implementations, you need to finalize your work by exporting the iPython Notebook as an HTML document. Before exporting the notebook to html, all of the code cells need to have been run.

**Rubric:**

1. Uploaded the notbook with all cells executed and the writeup cells, and the HTML output of the code.
2. Downloaded and loaded the dataset. There was a description of the data, and a visualization of one image of each category.
3. Preprocessed the data, and provided a description of the preprocessing steps taken. Use data augmentation to improve the available data.
4. Defined a model architecture using Convlolutional layers. Justified the model architecture based on other models, such as VGG or GoogleNet.
5. Described how the model was trained, mentioning how the hyperparameters (optimizer, batch size, loss function, etc) were selected, and what tests / modifications to the model you performed.
6. Tested the model on a subset of the data set and measure performance. 
7. Included images of traffic signs found from the web in a different folder, and tested the model on said images. Those images were visualized, and a discussion as to why those were chosen was included.
8. Measured the performance on the new images and compared it to the test dataset.
9. For the new images, output of the top 5 softmax predictions was included, and mentioned why you think those predictions were made.
10. Achieved at least 80% accuracy on the test images.
11. Create an additional model using transfer learning to try to improve performance.
12. Saved the model and weights to a file for later use.

**Deadline:** 18/03/19
