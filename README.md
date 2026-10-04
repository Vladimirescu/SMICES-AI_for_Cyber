# ETTI, SMICES: *​Introduction in Artifical Intelligence for cybersecurity​*, Fall 2026

This repository will contain all lectures, labs and project resources, code templates and (maybe) some solutions.

## Courses:

| **Nr.** | **Date** |       **Topic**       |**Materials** |
|:-------:|:--------:|:---------------------:|:-------------:|
|    1    |   7.10  |  _Intro & AI Ethics_  |  [slides](course/C0%20-%20Intro&Ethics.pdf)
|    2    |  14.10  | _Optimization & Linear Networks_ | |
|    3    |  28.10   | _Deep Neural Networks_ | |
|    4    |  11.11   | _Convolutional Neural Networks_ |  |
|    5    |  25.11   | _**Written Mid-term Exam**_ |  |
|    6    |  9.12  | _Recurrent Neural Networks_ |  |
|    7    |  13.01  | **Lab Homework Presentations** | |    
|    8    |  20.01    | **Lab Homework Presentations** |  |  
|    -    |  **TBA**    | **Written Final Exam** |    |

## Labs:

**❗Each lab will have 1 or more corresponding available homeworks - you will have to choose one of them to do and present at the end of the semester.**

| **Nr.** | **Date** |        **Topic**        | 
|:-------:|:--------:|:-----------------------:|
|    0    |    -     | _Lab Setup_ |   
|    1    |   4.11  | _DNNs_ |   
|    2    |   18.11   | _CNNs_ |   
|    3    |   2.12  | _CNNs++_ |   
|    4    |   16.12  | _RNNs_ |  


## Lab Homework Rules:

1. Each homework should be composed of a single Jupyter Notebook containing your code, results, and explanations.
2. You may create your homework by building upon the lab notebook, but only your additions will be graded.
3. If your homework requires any additional external files (e.g. `.py`), you'll store everything into a `.zip` archive of the form:
`Name_L[x].zip`, where `x` is the lab number.
4. Do not include any datasets in the archive. All homeworks are based on the datasets discussed at lab, therefore it is
recommended to use the already defined `torch.utils.data.Dataset` with the appropriate path of your dataset folder. Or, if you consider necessary to use any external data, add the corresponding `wget` or `curl` commands into your notebook for downloading the additional files $+$ the corresponding pre-processing.
5. ❗**The homework notebook must run seamlessly. Please ensure your archive includes any local dependencies, as well as all necessary ```!pip install ...``` commands for any additional packages you use.**
6. ❗**Before saving the notebook for submission, make sure the outputs of all cells are visible.**
7. ❗**All experiments and results must be accompanied by explanations in adjacent notebook cells.**
8. ❗**The homework assignment must be completed individually and presented in class to receive a grade. A high score is contingent upon a successful presentation.**

## Deadlines & Important dates:

| **Name** | **Date** |
|:-------:|:--------:|
|  Lab Homework Submission  |  11.01.2027, 23:59  |
|  Lab Homework Presentation |  13.01.2027 / 20.01.2027, live @ ETTI  |
___

Contact us if you have any questions via:
- [ana_antonia.neacsu@upb.ro](mailto:ana_antonia.neacsu@upb.ro)
- [vlad.vasilescu2111@upb.ro](mailto:vlad.vasilescu2111@upb.ro)

or make a post on the courses' Team.

___

## Recommended References:
- [CY 4100: AI Security and Privacy --  Northeastern University](https://www.ccs.neu.edu/home/alina/classes/Fall2025/)
- [Adversarial Machine LearningA Taxonomy and Terminology of Attacks and Mitigations](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf)
- [Convex Optimization – Boyd and Vandenberghe](https://stanford.edu/~boyd/cvxbook/)
- [Berkley Convex Optimization and Approximation course](https://ee227c.github.io)
- [EPFL Optimization for ML Course](https://github.com/epfml/OptML_course)
- [MIT Deep Learning Book - Ian Goodfellow, Yoshua Bengio and Aaron Courville](https://github.com/janishar/mit-deep-learning-book-pdf)
- [Neural Networks and Deep Learning - A Textbook](https://www.charuaggarwal.net/neural.htm)
- [Awesome Deep Learning - A curated list of awesome Deep Learning tutorials and projects](https://github.com/ChristosChristofidis/awesome-deep-learning)
