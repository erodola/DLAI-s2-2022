# Deep Learning & Applied AI @Sapienza

Course material, 2nd semester a.y. 2021/2022, Dept. of Computer Science

### News
- **05/05/2022:** Today's lecture will be streamed in the following Zoom meeting 909 702 0027, passcode: 887440
- **03/05/2022:** The midterm grades are now published.
- **26/04/2022:** The lectures of the 27th and 28th will regard an invited lecture and the midterm respectively, both during the standard lecture hours. The invited lecture will be given in the usual hybrid setting, so you can either come in presence or follow it remotely; the midterm will instead be performed remotely. The following Zoom meeting will be used for both lectures: Meeting ID: 889 5007 5810 Passcode: 774414.
- **21/04/2022:** The list of projects is now published, please scroll down for more details.
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

The list of **projects** is now published; please connect to the discord server to download the list. Each project must be accompanied with code + a 2 page report using a fixed template, also shared on the discord server. Projects can be made in groups of at most 2 students, but in this case, you must motivate this decision and get our approval beforehand.

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
Wed 20 Apr | Uncertainty, regularization and the deep learning toolset | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/labs/07/ML%20Tooling%202022.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/07/7_Uncertainty,_regularization_and_the_deep_learning_toolset.ipynb) | 
Thu 21 Apr | Deep generative models | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/10_generative/10-generative.pdf) |
Wed 27 Apr | Invited lecture: _Antonio Norelli: "Towards an artificial scientist"_ | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/11_invited/invited_lecture_Norelli.pdf) |
Thu 28 Apr | **Midterm self-evaluation** | [sheet](https://github.com/erodola/DLAI-s2-2022/raw/main/midterm/sheet.pdf); [grades](https://github.com/erodola/DLAI-s2-2022/raw/main/midterm/evaluations.pdf) |
Wed 04 May | Variational AutoEncoders |  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/08/8_Variational_Autoencoders_(VAEs).ipynb)
Thu 05 May | Geometric deep learning | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/11_geometric/11-gdl.pdf); [video](https://youtu.be/w6Pw4MOzMuo) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/10/Geometric_deep_learning.ipynb) |
Wed 11 May | Self-attention and transformers | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/12_trans/12-trans.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/erodola/DLAI-s2-2022/blob/main/labs/11/Transformers_2022.ipynb)
Thu 12 May | Adversarial training | [slides](https://github.com/erodola/DLAI-s2-2022/raw/main/13_adversarial/13-adversarial.pdf) |
Wed 18 May |  |  |

**End**
