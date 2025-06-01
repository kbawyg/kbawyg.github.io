---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

王元刚，博士，讲师，硕士研究生导师。2012年获[大连民族大学](www.dlnu.edu.cn)软件工程专业工学学士学位，2014年获[大连海事大学](www.dlmu.edu.cn)计算机技术专业工学硕士学位，2018年获[大连理工大学](www.dlut.edu.cn)控制理论与控制工程专业工学博士学位，2019年进入大连民族大学[计算机科学与工程学院](https://new.dlnu.edu.cn/comd/)从事科研与教学工作。主要研究方向为可解释建模方法和情感计算，具体包括公理模糊集理论、深度模糊系统、神经符号学习和人格特质计算等。迄今已在IEEE-TFS、IEEE-TCYB、Elsevier-ESWA、Elsevier-ASOC、Elsevier-NEUCOM、WIREs-DMKD和ICIC等期刊和会议发表论文10余篇。**欢迎电子信息类别人工智能专业硕士研究生，以及计算机类和电子信息类本科生加入课题组，一起“做科研”和“打比赛”。**

新闻近况
=
* 【2025-05-19】研究生姜雪婷、申博文获得[第十六届蓝桥杯全国软件和信息技术专业人才大赛（项目实战赛——智能体开发赛项）](https://dasai.lanqiao.cn/notices/1782/)省级二等奖，研究生贺鑫诚、本科生尚佳乐和赵杨俊雅获得省级三等奖。
* 【2025-05-19】本科生陈国民等人组成的队伍获得[2025年辽宁省普通高等学校本科大学生计算机设计竞赛](https://cxcy.upln.cn/competitionDetails?id=e8690455ffa2950b4e95771c82330c97)省级三等奖。
* 【2025-05-16】本科生王发兴等人组成的“It's my AC”队伍获得[第十六届蓝桥杯全国软件和信息技术专业人才大赛（项目实战赛——人工智能赛项）](https://dasai.lanqiao.cn/notices/1781)省级三等奖。
* 【2025-04-30】本科生刘梦岩、骆城峰获得[第十六届蓝桥杯全国软件和信息技术专业人才大赛](https://dasai.lanqiao.cn/notices/1774)省级二等奖，苏振函、于娜获得三等奖。
* 【2025-04-28】硕士生贺鑫诚等人撰写的论文“Neural Rule Learning with Network Architecture Search for Interpretable Classification”被ICIC 2025（CCF-C）录用为Poster Paper。
* 【2025-03-27】本科生郭莹莹等人、硕士生贺鑫诚等人组成的两支队伍分别获得[“2024亚太地区大学生数学建模竞赛”](http://m.saikr.com/contest/notice_detail/27342)国家级三等奖。
* 【2025-01-13】硕士生姜雪婷获得[“2024华为辽宁省大学生信息化技能大赛”](https://cxcy.upln.cn/competitionDetails?id=ef2a6cc91e255a240b4d351cdf2861cd)省级一等奖，硕士生贺鑫诚、薛佳宇获得省级二等奖。

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
