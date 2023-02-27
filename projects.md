---
layout: post
title: Projects
permalink: /projects
---
## Selected Projects
### Real Analysis Problem Set (实分析习题讲义) 
[github链接](https://github.com/kumiko-euphonium/Real-Analysis-Problem-Set-LaTeX)

本项目为开源的实分析习题集, 大家可以直接编辑.tex文件, 打造最适合自己的习题集. 
大量的自定义命令位于macros.tex中, 请大家复制一份以保证我写的部分能够正常运行, 同时写一份自己喜欢的自定义命令.

部分习题取自各大实分析经典教材, 包括但不限于Stein的实分析, Folland的实分析, 周民强的实变函数论. 

部分习题取自UW-Madison的分析学博士资格考试. 我参加了2022年暑假的备考强化课程, 由Jacob Denson主讲, 讲义见他的个人主页 [Jacob Denson](https://docs.google.com/viewer?url=https://github.com/jdjake/Notes/raw/master/Math/Analysis/2021_SEP.pdf). 该讲义是部分往年资格考试题的解答, 质量极高. 完整的资格考试试卷见[Qualifying Exams](https://www.library.wisc.edu/amp/services/course-reserves-exams/).

部分习题取自UW-Madison 2022 Fall的研究生实分析课程(Math 721)的作业题, 教授为Andreas Seeger. 

模板为[ElegantBook](https://github.com/ElegantLaTeX/ElegantBook).



### Real Analysis Lecture Notes (实分析讲义) 
[github链接](https://github.com/kumiko-euphonium/Real-Analysis-Lecture-Notes)

这是我2022年4月~2023年1月自学实分析时录制的视频的配套讲义. 实分析1, 2为手写笔记, 实分析3为pdf讲义. 


## All Projects
<ul>
    {% for project in site.projects %}
    <li><a href = "{{ project.url }}" class = "project-preview">{{ project.title }}</a></li>
    {% endfor %}
</ul>