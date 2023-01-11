## Welcome to STATS 315 / DATA SCI 315

This is an introductory deep learning course using the Python programming language and the TensorFlow deep learning library.

- **Textbook**: We will not follow any one textbook too closely. Here are a few references we will use:
  - _Dive into Deep Learning_ by Zhang, Lipton, Li and Smola. An advanced text from research scientists at Amazon. It weaves together math, figures, and code in an interactive online resource available [here](https://d2l.ai/). Code examples are provided in three frameworks: MXNet, PyTorch and TensorFlow. 
  - _Deep Learning with Python (2nd edition)_ by Chollet. A solid hands-on guide oriented towards programmers from the creator of the Keras deep learning library. Ebook and print versions are available from [Manning Publications](https://www.manning.com/books/deep-learning-with-python-second-edition)  
  - _Deep Learning_ by Goodfellow, Bengio and Courville. Written by three top deep learning researchers, this comprehensive book is required reading if you want to pursue your study of deep learning at a more advanced level. Print version is available from [MIT Press](https://mitpress.mit.edu/books/deep-learning) and an online version is [here](https://www.deeplearningbook.org/).
  
- **Undergraduate Courses on Deep Learning**: Many universities now offer an introductory deep learning course, e.g., [Berkeley](https://c.d2l.ai/berkeley-stat-157/), [CMU](https://deeplearning.cs.cmu.edu/), [MIT](http://introtodeeplearning.com/), [Stanford](https://cs230.stanford.edu/)
- **Canvas**: You should access the [Canvas class page](https://umich.instructure.com/courses/578445) for this course frequently. It will let you access important announcements and track course deliverables. (requires UM login)
- **Slack**: The course slack workspace is at [um-wn23-stats315.slack.com](https://um-wn23-stats315.slack.com) (requires UM login)
- **Days and Times**: Tuesdays and Thursdays, 1-2:30
- **Location**: [170 WEISER](https://maps.studentlife.umich.edu/building/weiser-hall) (links for virtual lectures, if any, will be saved in canvas and slack)

## Instructor Information

**Name**: Ambuj Tewari  
**Office Hours**: currently by appointment, regular hours to be posted soon  
**Email**: [tewaria@umich.edu](mailto:tewaria@umich.edu)

## GSI Information

**Name**: Unique Subedi (Lab 002 Thu 08:30-10:00 in WH335)  
**Email**: [subedi@umich.edu](mailto:subedi@umich.edu)

**Name**: Jacob (Jake) Trauger (Lab 003 Thu 2:30-4:00 in USB2234)    
**Email**: [jtrauger@umich.edu](jtrauger@umich.edu)

**Name**: Sahana Rayan (Lab 004 Thu 4:00-5:30 in EH1084)  
**Email**: [srayan@umich.edu](mailto:srayan@umich.edu)



**Lab webpage** (also has GSI office hours info): [link](https://docs.google.com/document/d/18vlonVMuDHjXH-fNCiqLvYFHnZhQerjssNHdeXQbKP8/edit?usp=sharing)

## Grading

- Canvas quizzes (20%): Will drop two lowest scores
- Homeworks (30%): Assigned roughly every other week. Will drop one lowest score
- Midterm Exam (20%): In class, timed, multiple choice, open book
- Final Exam (30%): In class, timed, multiple choice, open book

## Academic Integrity

The University of Michigan community functions best when its members treat one another with honesty, fairness, respect, and trust. The college promotes the assumption of personal responsibility and integrity, and prohibits all forms of academic dishonesty and misconduct. All cases of academic misconduct will be referred to the LSA Office of the Assistant Dean for Undergraduate Education. Being found responsible for academic misconduct will usually result in a grade sanction, in addition to any sanction from the college. For more information, including examples of behaviors that are considered academic misconduct and potential sanctions, please see [https://lsa.umich.edu/lsa/academics/academic-integrity.html](https://lsa.umich.edu/lsa/academics/academic-integrity.html)

## Accommodation for Students with Disabilities

If you think you need accommodation for a disability, please let me know at your earliest convenience. Some aspects of this course, the assignments, the in-class activities, and the way the course is usually taught may be modified to facilitate your participation and progress. As soon as you make me aware of your needs, we can work with the Office of Services for Students with Disabilities (SSD) to help us determine appropriate academic accommodations. SSD (734-763-3000; [http://ssd.umich.edu/](http://ssd.umich.edu/)) typically recommends accommodations through a Verified Individualized Services and Accommodations (VISA) form. Any information you provide is private and confidential and will be treated as such.

## Mental Health and Well-Being

Students may experience stressors that can impact both their academic experience and their personal well-being. These may include academic pressures and challenges associated with relationships, mental health, alcohol or other drugs, identities, finances, etc. If you are experiencing concerns, seeking help is a courageous thing to do for yourself and those who care about you. If the source of your stressors is academic, please contact me so that we can find solutions together. For personal concerns, U-M offers a variety of resources, many which are listed on the [Resources for Student Well-being](https://wellbeing.studentlife.umich.edu/resources-list) webpage. You can also search for additional well-being resources [here](https://wellbeing.studentlife.umich.edu/well-being-resources). 

## Schedule

DLPy = _Deep Learning with Python (2nd edition)_ by Chollet    
DL = _Deep Learning_ by Goodfellow, Bengio and Courville    
D2L = _Dive into Deep Learning_ by Zhang, Lipton, Li and Smola    

_Note_: A "V" in the date column denotes a virtual lecture.

Lecture No. | Date | Topic | Reading Assignment 
---         | ---  | ---   | ---               
01     | Jan 05 | Course logistics <br/> Introduction <br/> [slides](https://docs.google.com/presentation/d/1WOGiIZUbvj2UjRX3DXsArzvhjBmNAmvZ/edit?usp=sharing&ouid=105036821118529706206&rtpof=true&sd=true) | DLPy, Chap. 1 <br/> DL, Chap. 1 <br/> D2L, Chap. 1
&nbsp; |        | **Linear Algebra Boot Camp** |
B1     | Jan 10 | Linear Algebra <br/> [notebook](https://colab.research.google.com/drive/1RweKeSnQgxCuR25FFEOIwGxAkmeiu5sf?usp=sharing) | D2L Geometry and Linear Algebraic Operations, Sec. 22.1.1-2
B2     | Jan 12 | Linear Algebra (continued) <br/> [notebook](https://colab.research.google.com/drive/1RweKeSnQgxCuR25FFEOIwGxAkmeiu5sf?usp=sharing) <br/> <span style="color:red">TBD due</span> | D2L Geometry and Linear Algebraic Operations, Sec. 22.1.3-5 
B3     | Jan 17 | Linear Algebra (continued) <br/> [notebook](https://colab.research.google.com/drive/1RweKeSnQgxCuR25FFEOIwGxAkmeiu5sf?usp=sharing) | D2L, Sec. 22.1.6-7 <br/> D2L Geometry and Linear Algebraic Operations, Sec. 22.1.9
&nbsp; |       | **Basics** |
02     | Jan 19 | Basic Elements of Linear Regression <br/> [slides](https://ambujtewari.github.io/stats315-winter2023/) | D2L, Sec. 3.1.1
03     | Jan 24 | Regression <br/> Loss functions and gradient descent <br/> [slides](https://ambujtewari.github.io/stats315-winter2023/) | D2L, Sec. 3.1.1
04     | Jan 26 | Regression wrap-up <br/> Classification <br/> [slides](https://ambujtewari.github.io/stats315-winter2023/) | D2L, Sec. 3.1.3-4 <br/> D2L, Sec. 3.4.1
05     | Jan 31 | Softmax Operation <br/> Cross Entropy Loss Function <br/> [slides](https://ambujtewari.github.io/stats315-winter2023/)|  D2L, Sec. 3.4.2-4 <br/> D2L, Sec. 3.4.6.1 
06     | Feb 02 | Softmax Derivatives <br/> Information Theory Basics <br/> [slides](https://ambujtewari.github.io/stats315-winter2023/)|  D2L, Sec. 3.4.6.2-3 <br/> D2L, Sec. 3.4.7
&nbsp; |        | **TensorFlow/Keras** |
07     | Feb 07 | TensorFlow, Keras, Google Colab <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 3.1-4
08     | Feb 09 | First steps with TensorFlow <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 3.5.1-2 <br/> DLPy, Sec. 2.4.4 
09     | Feb 14 | First steps with TensorFlow (continued) <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 3.5.3-4
--     | Feb 15 | <span style="color:red">TBD due</span>
10     | Feb 16 | Getting started with NNs: Classification MNIST <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 2.1
11     | Feb 21 | Getting started with NNs: Classification IMDB <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 4.1
--     | Feb 23 | <span style="color:red">MIDTERM EXAM</span>
--     | Feb 28 | SPRING BREAK |
--     | Mar 02 | SPRING BREAK |
12     | Mar 07 | Getting started with NNs: Regression Boston Housing Price <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 4.3
13     | Mar 09 | Generalization <br/> Evaluating ML models <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 5.1-2
14     | Mar 14 | Improving model fit <br/> Regularizing your model <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 5.3 <br/> DLPy, Sec. 5.4.4
&nbsp; |        | **Convolutional Neural Networks** |
18     | Mar 16 |  From Fully-Connected Layers to Convolutions <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | D2L, Sec. 6.1
19     | Mar 21 | Convolutions for Images <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | D2L, Sec. 6.2 <br/> D2L, Sec. 6.3-4
--     | Mar 23 | TBD | 
20     | Mar 28 | Pooling <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | D2L, Sec. 6.5-6
&nbsp; |        | **Deep Learning for Time Series** |
--     | Mar 30 | TBD <br/> <span style="color:red">TBD due</span> |
21     | Apr 04 | A temperature-forecasting example <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 10.2
22     | Apr 06 | A temperature-forecasting example (continued) <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 10.2
23     | Apr 11 | Understanding recurrent neural networks <br/> Advanced use of recurrent neural networks <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) | DLPy, Sec. 10.3 <br/> DLPy, Sec. 10.4
24     | Apr 13 <br/> V | Recurrent Neural Networks <br/> [notebook](https://ambujtewari.github.io/stats315-winter2023/) |  D2L, Sec. 8.4 <br/> D2L, Sec. 8.7.1
25     | Apr 18 | Course Conclusion <br/> Ask Me Anything! <br/> [slides](https://ambujtewari.github.io/stats315-winter2023/) |
&nbsp; | Apr 20 | <span style="color:red">TBD due</span> 
--     | Apr 26 | <span style="color:red">FINAL EXAM FROM 4 to 6 pm</span> 

