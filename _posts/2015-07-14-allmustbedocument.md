--- 
layout: post
title: 内部系统介绍
date: 2015-07-14 13:37:26
categories:
    - 工作
tags:
    - test
---
"所有的工作内容都项目化，可视化，文档化。"

* 无论多么零碎的内容都可以(必须)属于一个项目。

* 可视化是指工作内容和成果可在以后追溯的。

* 每一项内容都有记载，可以查看到历史记录。

就 IT 开发项目来讲，包括整个团队的管理都可以使用一些基本工具来简化、优化一些日常事务。简单介绍一下由我搭建的一些内部用系统。这些工具有 redmine、phabricator 等。

* redmine
用来项目管理。传统意义上的开发项目当然以项目单位来管理，出此之外一些看上去不成项目的任务也根据它们的性质划分成特殊的项目。成员每开始一次任务都必须先在 redmine 中建任务，这样的好处是为了方便任务的追踪和总结。

* phabricator
代码审查。另外它的 task 和 pholio 也很好用，基本是配合 redmine 使用的。

* svn
源代码管理。用的是 VisualSVN server，傻瓜操作。 svn 的 repo 是和 redmine/phabricator 联动的，方便查看。

* gitlab
源代码管理，逐渐替代了先前使用比较多的 svn。 git 的 repo 也是和 redmine/phabricator 联动的。



