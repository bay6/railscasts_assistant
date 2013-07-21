##保持简洁，专注

项目时间： 一周

开发人员： 2-3人 

项目目标： 能有些访问量的网站

项目定位：

    RailsCasts 协助学习网站

一周的任务：

    1 抓取railscasts网页内容，标题图片

    2 用户github登录
  
    3 用户标识项目 “以完成”

    4 用户标识项目 “以掌握” 创建一份问答题，或回答三份问答题

    5 用户可以针对一集railscast 备注

    6 用户可以针对一集railscast 分类

    7 用户可以针对一集railscast 评分评级

    8 用户查看个人学习情况报表

    9 用户查看一集railscast，汇总报告，分类，评分，多少问题
 




##项目目标

整理思路，和存档各种讨论，制定如何开展bay6项目

##当前第一任务

设计和整理一个简洁的需求。用于2-3开发人员，一到二周时间开发能够上线。限制功能。专注主要功能，精简，简洁的功能。

只看这一两周能完成的事。要专注到最有用的，最重要的功能上。

项目的目标是，做一个有访问量的互相学习站点。 


##凌乱的考虑
目标定小一点，再小一点，功能少点，专注一个小事能够做成功。

Railscasts learning assistant。 Rails学习助手
基本功能
 1 记录自己学习railscasts的过程。 过后，学过没有都忘了
 2 给railscasts分级别和rate（以后，就是对更多的rails学习材料的分类和提炼，回答什么是初级水平最好的学习资料的问题）
 3 要不要能够出题？


bay6项目将致力于，social education。专注ruby rails行业。菜于快速开发精简功能的小迭代开发模式。 争取每周有一个版本发布出来。

bay6项目本身，以互相出题的方式促进，rails的学习。以游戏元素中，磨级，长经验的方式，促进学习。 

例如，精简版本可以基于railscasts（如果有违背精简的原则不做railscasts也可以），以选择题的方式出题。完成题目就可以获得一个积分，或者，完成10个exam得到一个奖章。

功能一定要简洁，完成一个功能，不做复杂的没有针对的开发。

也可以抛开railscasts，就做rails的social学习社区。 功能设计为：
用户可以创建exam， exam包括一个视频或者文章源（一集railscasts，一篇railsguide）。exam包括几个多项选择题（以后，题目可以有多种形式）

用户可以回答exam，得到记录证明自己学习了这个视频

用户可以给自己完成的exam评分，分类

## Design & Preparation

1. Would like a simple tool to track the learning progress, which should have report according to day. and also have record to show which episode is already finished

2. Would like a function integrate with github. Such as, you should commit a project at github to confirm you have finished the project

3. Would be better we can confirm with heroku. such as learn from railscast deploy to heroku and confirm learning

railscasts_assistant
====================

a tool to track railscast learning progress
