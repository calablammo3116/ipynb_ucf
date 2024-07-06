## [Google Drive folder link](https://drive.google.com/drive/folders/17i_SkxAR7scvtvQZlb8xqPwhom36NJyI?usp=sharing)


### [Homework 1 link](https://colab.research.google.com/drive/1NiU4wrZ9qu7zKcsFC47O2JlHBRNPFeff?usp=sharing)

Basic image processing homework with an emphasis on color channel manipulation (RGB, LAB), using OpenCV, NumPy, pandas, and skimage (Scikit Image), plus matplotlib for color channel visualization and plotting.


### [Homework 3 link](https://colab.research.google.com/drive/1LQo2dtdS_8MB3weTKGyi0FK7pIIDCbdR?usp=drive_link)

Kernel filtering and edge detection homework using skimage, NumPy, and OpenCV, plus Matplotlib for visualization.


### [Homework 4 link](https://colab.research.google.com/drive/1oyuwF5Yb0-lVqk0s9BbId2j53aQwkSsj?usp=sharing)

Image warping homework using NumPy, plus Matplotlib for visualization.


### [Project 1 folder link](https://drive.google.com/drive/folders/1BQ6YVudmx0lp6WO2xm8rgMl9vD3sS3Mp?usp=sharing)

[Project 1 notebook link](https://colab.research.google.com/drive/118LOrJXSSQ7cNWaoTUS_AuYUvWMeelM8?usp=sharing) . Image warping project, specifically with a focus on image projection (projecting a different perspective) using four point pair correspondences. Question 1 is comprised of code to compute the homography matrix for and to display the projected perspective of [an input image](https://drive.google.com/file/d/1ArklJhwOQ9WpaJzi65ZXqKmlV_YFUZO5/view?usp=sharing) (another image can be used instead of this one, if desired). This project uses NumPy, PIL's Image, and io's BytesIO, plus OpenCV for testing the homography matrix and Matplotlib for visualization.

Question 2 is an attempt to find the edges of a piece of paper, in a manner similar to a document-to-PDF scanner or Camscanner. In the future, this could be improved with better edge detection and perhaps distance ratio detection using trigonometry to determine where the edges of the paper lie (this, of course, would be paper-geometry-dependent; for example, it would need to be specified whether this is generic 11"-8.5" letter paper or paper with some other dimensions, and, if so, what those dimensions are).


### [Project 2 link](https://colab.research.google.com/drive/1kcRjNBJ2eKCQAh2tb1sQOLDukZwZtLCq?usp=sharing)

Deep learning, using conventional feed-forward neural networks using only linear layers, as well as Convolutional Neural Networks (CNNs), project, using PyTorch and NumPy, plus Matplotlib for visualization. 

Multiple runs for different model types were conducted, with training and testing accuracies evaluated in each epoch. Different hyperparameters were tested (hyperparameter tuning) for Model Options 2 and 3 for the MNIST dataset. 

For both sets of models - the models trained on the MNIST handwritten digits dataset *and* the models trained on the CIFAR-10 dataset - observations were made and conclusions were drawn about each model option after running them.

In retrospect, developing a single general-purpose `run_main()` function for both datasets evaluated (making one for the MNIST-trained models, not only one for the CIFAR-10-trained ones) would have reduced the number of lines of code and made the code more readable.

