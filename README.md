# Deep Learning & Applied AI @Sapienza

Course material, 2nd semester a.y. 2021/2022, Dept. of Computer Science

### News

- **13/04/2022:** Please fill out the OPIS questionnaire (instructions [here](https://www.uniroma1.it/sites/default/files/field_file_allegati/guided_path_to_access_student_s_opinions_questionnaire_2021_2022.pdf)). The code for this course is X6SYL1ZK.
- **13/04/2022:** The lecture of April 14th is cancelled due to Easter holidays, as per the academic calendar.
- **05/02/2022:** The course website is online. Welcome to DLAI 2021/22!

### Logistics

**Lecturer:** Prof. Emanuele Rodolà

**Assistants:** Dr. Luca Moschella, Dr. Donato Crisostomi

**When:** Wednesdays 16:00--19:00 and Thursdays 10:00--12:00 ([official schedule](https://www.studiareinformatica.uniroma1.it/laurea-magistrale/orario-lezioni))

**Where:**

Physical classrooms (capacity: 100%): Aula 2 (Wednesdays) and Aula 1 (Thursdays) - Aule L Via del Castro Laurenziano 7a

Virtual classroom: [Zoom](https://zoom.us/j/4752349941?pwd=U0doeGFLWFFDSWlzWWxvd0JGMDRndz09), Meeting ID: 475 234 9941, Passcode: 3K7xrM.

The lectures will not be recorded.

**Q & A:** Please use the Discussions system of Github. [Here](https://github.com/erodola/DLAI-s2-2022) is the link to the course repository.

### Pre-requisites

Programming fundamentals in **Python**; calculus; linear algebra.

### Textbook and reading material

Due to the continuously evolving nature of the topic, there is no fixed textbook as a reference. Specific material in the form of scientific articles and book chapters will be given throughout the lectures.

In addition, you can find [here](https://github.com/erodola/DLAI-s2-2022/blob/main/resources/Course_notes_Crisostomi.pdf) some supplementary course notes.

### Grading

Evaluation proceeds according to the following steps:

- A midterm self-evaluation test (optional, does not concur to the final grade)
- A final written exam (**mandatory**, accounts for 60% of the final grade)
- A project (**mandatory**, accounts for 40% of the final grade)
- An oral exam (optional, attributes at most 3 points, added to or subtracted from the final grade)

The _cum laude_ can be obtained only by taking the oral exam. For students who already have a very high score with written exam + project, the oral exam is meant to confirm the high score.

The list of projects will be published at a later time.

Here you can find some example sheets of past written exams:

- [June 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/June-2021.pdf)
- [July 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/July-2021.pdf)
- [September 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/September-2021.pdf)
- [October 2021](https://github.com/erodola/DLAI-s2-2021/raw/main/exams/October-2021.pdf)

### Lectures

**Date** | **Topic** | **Reading** | **Code & Data**
------------ | ------------- | ------------ | ------------
Wed 23 Feb | Introduction | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/01_intro/01-intro.pdf) |
Thu 24 Feb | Data, features, and embeddings | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/02_data/02-data.pdf) |
Wed 02 Mar | Tensor manipulation |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/01/01_Tensor_basics_2022.ipynb)
Thu 03 Mar | Linear algebra revisited | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/03_linalg/03-linalg.pdf); [notes on matrix meta-mechanics](https://github.com/erodola/DLAI-s2-2022/raw/main/03_linalg/03b-matrix.pdf) |
Wed 09 Mar | Tensor operations |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/02/02_Tensor_operations_2022.ipynb)
Thu 10 Mar | Linear regression, convexity, and gradients | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/04_linear/04-linear.pdf) |
Wed 16 Mar | Linear models and Pytorch Datasets   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/03/03_Linear_models_and_Pytorch_Datasets_2022.ipynb) |
Thu 17 Mar | Overfitting and going nonlinear | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/05_nonlinear/05-nonlinear.pdf) |
Wed 23 Mar | Logistic Regression and Optimization |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/04/4_Logistic_Regression_and_Optimization.ipynb) |
Thu 24 Mar | Stochastic gradient descent | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/06_sgd/06-sgd.pdf) |
Wed 30 Mar | Autograd and Modules | | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/05/5_Autograd_and_Modules_2022.ipynb)
Thu 31 Mar | Multi-layer perceptron and back-propagation | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/07_mlp/07-mlp.pdf) |
Wed 06 Apr | Convolutional Neural Networks   |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/06/6_Convolutional_Neural_Networks_2022.ipynb) |
Thu 07 Apr | Convolutional Neural Networks | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/08_cnn/08-cnn.pdf) |
Wed 13 Apr | Regularization, batchnorm and dropout | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/09_regular/09-regular.pdf) |
Wed 20 Apr | TBD |  |
Thu 21 Apr | TBD |  |
Wed 27 Apr | Invited lecture |  |
Thu 28 Apr | Midterm self-evaluation |  |
