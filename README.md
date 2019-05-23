# MACS 30200 - Perspectives on Computational Research (Spring 2019)

* Instructor: [Benjamin Soltoff](http://www.bensoltoff.com), Lecturer in [Computational Social Science](http://macss.uchicago.edu)
* Meeting day/time: MW 11:30-1:20pm (Saieh Hall of Economics 247)
* Office hours: Th 12:30-2:30pm (McGiffert House 209)

## Course description

This course focuses on applying computational methods to conducting social scientific research through a student-developed research project. Students will identify a research question of their own interest that involves a direct reference to social scientific theory, use of data, and a significant computational component. The students will collect data, develop, apply, and interpret statistical learning models, and generate a fully reproducible research paper. We will identify how computational methods can be used throughout the research process, from data collection and tidying, to exploration, visualization and modeling, to the final communication of results. The course will include modules on theoretical and practical considerations, including topics such as epistemological questions about research design, writing and critiquing papers, and additional computational tools for analysis.

## Grades

|     Assignment              | Points | Quantity | Total points |
|-----------------------------|--------|----------|--------------|
| Proposal                    |    10  |      1   |        10    |
| Literature review           |    15  |      1   |        15    |
| Methods/initial results     |    15  |      1   |        15    |
| Peer evaluations of posters |     2  |      5   |        10    |
| Poster presentation         |    30  |      1   |        30    |
| Final paper                 |    40  |      1   |        40    |
| Problem set                 |    10  |      3   |        30    |
| **Total Points**            |        |          |       150    |

* All assignments related to the final project will be turned in via their own public GitHub repositories. You can create this repository [here](https://classroom.github.com/a/QnC7JReS).
* Each problem set will be submitted via pull request to individual repositories (e.g. `hw01`, `hw02`, `hw03`)

## Late Problem Sets

Late problem sets will be penalized 1 point for every hour they are late. For example, if an assignment is due on Monday at 11:30am, the following points will be deducted based on the time stamp of the last commit.

| Example PR last commit | Points deducted |
| ---------------------- | --------------- |
| 11:31am to 12:30pm     | -1 point       |
| 12:31pm to 1:30pm       | -2 points       |
| 1:31pm to 2:30pm       | -3 points       |
| 2:31pm to 3:30pm       | -4 points       |
| 9:30pm and beyond      | -10 points (no credit) |

## Disability services

If you need any special accommodations, please provide me (Dr. Soltoff) with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.

## Course schedule (lite)

| Date | Day | Topic | Reading | Slides | Assignment due dates |
|--------|-----|--------------------------------------------------|-------------------------------------------------------|------------------------------------------------------------------------|---------------------------------------------------------|
| Apr 1 | Mon | Overview/reproducibility in science |  | [Slides](https://model.uchicago.edu/slides/intro-reproducibility.html) |  |
| Apr 3 | Wed | Identifying a research question | CR ch 3-6 | [Slides](https://model.uchicago.edu/slides/identify-a-question.html) |  |
| Apr 8 | Mon | Writing the literature review/theory sections |  | [Slides](https://model.uchicago.edu/slides/theory-section.html) |  |
| Apr 10 | Wed | Methods/results section |  | [Slides](https://model.uchicago.edu/slides/data-methods-results.html) | [Research proposal](assignments/project-proposal.md) |
| Apr 15 | Mon | Individual meetings - proposal feedback |  |  |  |
| Apr 17 | Wed | Dealing with missingness | [Notes](https://model.uchicago.edu/notes/imputation/) | [Slides](https://model.uchicago.edu/slides/imputation.html) |  |
| Apr 22 | Mon | Deep learning fundamentals | ESL ch 11; DLPyR ch 1-2 | [Slides](https://model.uchicago.edu/slides/what-is-deep-learning.html) |  |
| Apr 24 | Wed | Deep learning fundamentals | ESL ch 11; DLPyR ch 1-2 | [Slides](https://model.uchicago.edu/slides/what-is-deep-learning.html) |  |
| Apr 29 | Mon | Deep learning and Keras/Tensorflow | ESL ch 11; DLPyR ch 3-4 | [Slides](https://model.uchicago.edu/slides/building-blocks.html) |  |
| May 1 | Wed | Class cancelled |  |  | [Lit review draft](assignments/lit-review.md) |
| May 6 | Mon | Individual meetings - literature review feedback |  |  |  |
| May 8 | Wed | Deep learning - texts and sequences | DLPyR ch 6 | [Slides](https://model.uchicago.edu/slides/sequential-data.html) | [HW01](assignments/hw01.md) |
| May 13 | Mon | Data visualization and evaluating statistical graphs |  | [Slides](https://model.uchicago.edu/slides/design-eval.html) |  |
| May 15 | Wed | Best practices in designing statistical graphics |  | [Slides](https://model.uchicago.edu/slides/best-practices.html) | [HW02](assignments/hw02.md) |
| May 20 | Mon | Class imbalance (Sushmita) |  | [Slides](https://github.com/sushmitavgopalan16/talks/blob/master/MACSS%20%20Class%20Imbalance.pptx) |  |
| May 22 | Wed | Effective presentations |  | [Slides](https://model.uchicago.edu/slides/present-research.html) | [Methods/results draft](assignments/methods-results.md) |
| May 27 | Mon | No class (Memorial Day) |  |  |  |
| May 29 | Wed | No class (out of town) |  |  | [HW03](assignments/hw03.md) |
| Jun 3 | Mon | Writing the abstract/intro/conclusion |  |  |  |
| Jun 5 | Wed | Poster session |  |  | [Research poster](assignments/poster.md) |
| Jun 12 | Wed |  |  |  | [Final paper (5pm)](assignments/final-paper.md) |

## References and Readings ##

All readings are required unless otherwise noted. Adjustments can be made throughout the quarter. Be sure to check this repository frequently to make sure you know all the assigned readings.

* Data/methods/results sections
    * [Broockman, D. E., & Skovron, C. (2018). Bias in Perceptions of Public Opinion among Political Elites. *American Political Science Review*, 1-22.](https://www.cambridge.org/core/journals/american-political-science-review/article/bias-in-perceptions-of-public-opinion-among-political-elites/2EF080E04D3AAE6AC1C894F52642E706/share/1bd83a8a05b6ac177c51e7a19aee1c55f3ef4b97)
* [DLPyR] Deep learning with Python/R
    * [Chollet, F. (2017). *Deep learning with Python*. Manning Publications.](https://www.manning.com/books/deep-learning-with-python)
    * [Chollet, F. with J.J. Allaire (2018). *Deep learning with R*. Manning Publications.](https://www.manning.com/books/deep-learning-with-r)
* [CR] Booth, W. C., Colomb, G. G., Williams, J. M., Bizup, J., & FitzGerald, W. (2016). *The craft of research*. University of Chicago press.
    * [eBook available through the UChicago library](https://ebookcentral.proquest.com/lib/uchicago/detail.action?docID=4785166)
* [Kastellec, J., & Leoni, E. (2007). Using Graphs Instead of Tables in Political Science. *Perspectives on Politic*s, 5(4), 755-771. Retrieved from http://www.jstor.org/stable/20446574](https://www.jstor.org/stable/20446574?seq=1#metadata_info_tab_contents)
