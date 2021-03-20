# AI_Sudoku_Solver

Sudoku a puzzle in which players insert the numbers one to nine into a grid consisting of nine squares subdivided into a further nine smaller squares in such a way that every number appears once in each horizontal line, vertical line, and square.

Here, using OpenCV, DeepLearnng and Backtracking Algorithm is used to solve the puzzle. First, build the Character Recognition model that can extract digits from a Sudoku grid image and then work on a backtracking approach to solve it.

# Dependencis

Deep Learning based AI_Sudoku_Solver architecture uses [OpenCV](https://opencv.org/) (opencv==4.2.0) and Python (python==3.7). The model Convolution Neural Network(CNN) uses [Keras](https://keras.io/) (keras==2.3.1) on [Tensorflow](https://www.tensorflow.org/) for Digit Recognition.

# How to execute code:

1. You will first have to download the repository and then extract the contents into a folder.
2. Make sure you have the correct version of Python installed on your machine. This code runs on Python 3.6 above.
3. Now, install the required libraries.
4. Now, you can use pretrained digit recognition model, it's inside `Resources` Folder. The [MNIST](https://en.wikipedia.org/wiki/MNIST_database) is used for digit recognition using Deep Learning CNN model. 
5. Now, Open terminal and type the following command:
> `python Main.py -i <path to sudoku image>`

The above command is used for solving sudoku in images, and for real time sudoku solver, use webcam (Opencv for capturing Video).

# Results

1. Sudoku Solver in Images.

![Output](https://github.com/Devashi-Choudhary/AI_Sudoku_Solver/blob/main/Resources/output.JPG)


# References

1. [Sudoku Solver](https://github.com/murtazahassan/OpenCV-Sudoku-Solver)
2. [Digit Recognition](https://github.com/kurapan/CNN-MNIST)
3. [BackTracking Algorithm](https://techwithtim.net/tutorials/python-programming/sudoku-solver-backtracking/)
