# [23fall] CS5489-机器学习：算法与应用

For English version, please click [here](readme.md).

## 简介

这门课程是香港城市大学（City University of Hong Kong）电脑科学系（Department of Computer Science）开设的一门研究生级别的课程，为CS系博士生、研究型硕士生的必修课，以及授课制硕士生的选修课。

我于2023年秋季学期选修了这门课程，这个仓库将存放我在这门课程中完成的Tutorials、Assignments和Project的代码和报告，这些都是我（及组员）自己完成的，而*不是*标准答案。此外，我会存放一些往年的试卷以便复习。

这门课的所有练习和作业都是经过精心准备的，你可以从这门课中学到很多东西。

## 内容介绍及索引

### Tutorials

每一次课程结束后会有一个Tutorial环节，内容和这门课程有关，考试前会给出所有tutorial的参考答案用于复习。Tutorial中只需要提交单个的Jupyter文件。10次Tutorials的位置如下：

| Tutorials                               | 位置                      |
| --------------------------------------- | ------------------------- |
| [Tutorial 1](Tutorials/tutorial1.ipynb) | Tutorials/tutorial1.ipynb |
| [Tutorial 2](Tutorials/tutorial2.ipynb) | Tutorials/tutorial2.ipynb |
| [Tutorial 3](Tutorials/tutorial3.ipynb) | Tutorials/tutorial3.ipynb |
| [Tutorial 4](Tutorials/tutorial4.ipynb) | Tutorials/tutorial4.ipynb |
| [Tutorial 5](Tutorials/tutorial5.ipynb) | Tutorials/tutorial5.ipynb |
| [Tutorial 6](Tutorials/tutorial6.ipynb) | Tutorials/tutorial6.ipynb |
| [Tutorial 7](Tutorials/tutorial7.ipynb) | Tutorials/tutorial7.ipynb |
| [Tutorial 8](Tutorials/tutorial8.ipynb) | Tutorials/tutorial8.ipynb |
| [Tutorial 9](Tutorials/tutorial9.ipynb) | Tutorials/tutorial9.ipynb |
| [Tutorial 10](Tutorials/tutorial10.ipynb) | Tutorials/tutorial10.ipynb |

我在tutorial 2和tutorial 6中各扣了1分，其余的都是满分。

### Assignments

Assignment则和tutorial不同，每一次Assignment会给出一个特定的机器学习场景（通常，Assignment 1是文本分类问题，Assignment 2是音频分类问题），你需要在给定的题目背景条件和有限的指引下，自行编写解决方案，并根据少部分训练数据来预测未标定y的数据集，将结果csv提交到课程Kaggle上。

你需要提交三个文件，包括最终结果的csv文件、生成这个csv文件的jupyter文件（来验证这个csv结果是否是可重复的），以及一份完整的报告（需要记录为了生成最终结果的所有尝试）。

我完成的两次Assignments的位置如下：

| 内容                                                         | 位置                                        |
| ------------------------------------------------------------ | ------------------------------------------- |
| [Assignment 1 Report](Assignment 1/Assignment1-2023A-report.ipynb) | Assignment 1/Assignment1-2023A-report.ipynb |
| [Assignment 1 Final Solution](Assignment 1/Assignment1-2023A-Final.ipynb) | Assignment 1/Assignment1-2023A-Final.ipynb  |
| [Assignment 1 Prediction Result](Assignment 1/final_submission.csv) | Assignment 1/final_submission.csv           |
| [Assignment 2 Report](Assignment 2/Assignment2-2023A-report.ipynb) | Assignment 2/Assignment2-2023A-report.ipynb |
| [Assignment 2 Final Solution](Assignment 2/Assignment2-2023A-Final.ipynb) | Assignment 2/Assignment2-2023A-Final.ipynb  |
| [Assignment 2 Prediction Result](Assignment 2/final_submission.csv) | Assignment 2/final_submission.csv           |

我的assignment 1扣除了2分（1分是因为报告讨论不够insightful，1分是因为kaggle排名在1%以外），而assignment 2扣除了0.5分（因为kaggle排名不在0.5%内）。

### 小组项目

对于Group Project，你可以选择和另一个同学组队完成。Project的内容类似Assignment，题目是开放的，你可以从给定的现有Kaggle竞赛中任选，也可以自己选一个题目完成。

我们当时选的题目是[LLM - Detect AI Generated Text](https://www.kaggle.com/competitions/llm-detect-ai-generated-text)，我们的结果文件位于目录`Group Project`下，您可以在`Group Project/Course Project-2023A.ipynb`阅读我们的[报告](Group Project/Course Project-2023A.ipynb)。

### 往年考试试卷

在 23fall 中，本课程的期中考试将涵盖前五章，期末考试将涵盖后五章。考试全部采用闭卷形式，但允许在考试中使用一页（期中考试）或双页（期末考试）手写 A4  cheatsheet。

目前，共有5套[期中考试题](Past Exam Papers\Midterms)，他们都包含了问题和答案，您可以在`Past Exam Papers\Midterms`查看它们。此外，共有2套[期末考试题](Past Exam Papers\Finals)，但是只有问题没有答案，您可以在`Past Exam Papers\Finals`查看它们。

注意：之后的考试题型和内容可能有所变化或采取其他形式。

## 其他有用的信息

这门课着重讲解机器学习的实际应用环节，涵盖了机器学习的方方面面，课程的工作量极大。本门课程的授课、平时练习、作业和Project全部基于Jupyter Notebooks，CS系会提供在线的Jupyter Lab（包括GPU资源）以供使用，当然也可以使用自己的电脑完成作业。

在23年秋季学期中，这门课的成绩组成如下：

| 内容           | 占比 | 备注                  |
| -------------- | ---- | --------------------- |
| Tutorials 1-10 | 10%  |                       |
| Assignment 1   | 10%  |                       |
| Assignment 2   | 10%  |                       |
| Group Project  | 30%  | 至少拿到30%才可以通过 |
| Midterm        | 10%  | 23fall平均分49.2/100  |
| Final Exam     | 30%  | 至少拿到30%才可以通过 |

其中，小组项目和期末考试需要得到至少30%才能通过这门课。

## 声明

我将**不会**在这个仓库中存放*Tutorial的参考答案、课件和课程录屏*。

本仓库中的文件和本Readme文件中的内容**仅供参考**，请不要直接使用本仓库中的*任何*文件。

我将*不会*对因使用本仓库中的任何内容导致的任何后果负责。