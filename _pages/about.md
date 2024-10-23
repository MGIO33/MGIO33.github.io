---
permalink: /
title: "WEICOME TO MY HOMEPAGE！"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


About Me
======
您好！欢迎来到我的主页！我叫刘伟涛，来自湖南株洲，生日是2003.10.24。
目前（2024.10.23）我是湘潭大学数学与应用数学专业的一名大四学生。我喜欢听[音乐](https://music.163.com/#/user/home?id=315677040)，Yellow，Photograph是我的最爱； 中长距离跑步，目前的目标是跑完一次10000m；踢足球，但是水平比较低，但我很喜欢在场上和朋友一起奔跑的感觉；看比赛，包括但不限于英雄联盟，瓦洛兰特，CS，足球，篮球；看电影小说，我喜欢看故事，所以文艺性比较强的电影和文学性太强的书我不感兴趣，看到那些精彩的故事是让我体验一种不同的人生；打游戏，包括但不限于英雄联盟的各种模式（id：自由是遗忘的伴随#85445 大区：艾欧尼亚）瓦洛兰特（ id：MGIO#26019）[Steam](https://steamcommunity.com/profiles/76561199028423416/) 如果您有想进一步了解我的想法可以添加我的QQ：2821968474，我们可以进一步交流了解，也许我们能成为朋友。

我的一天非常简单， 起床，洗漱，（也许吃个早饭），学习或者打游戏，吃中饭，学习或者打游戏，跑步，吃晚饭，（处理琐事如洗衣服，洗澡，购物，回复消息，打电话给爸妈等等), 学习或者打游戏， 上床玩手机，睡觉。 一般而言非比赛日只有在床上的时候我才会有大片的时间玩手机(>30min),  我不（极少极少）玩手机游戏，一般而言是刷虎扑，[b站](https://space.bilibili.com/170010528?spm_id_from=333.999.0.0)，[知乎](https://www.zhihu.com/people/ao-zang-43)或者去外面逛一逛。碎片化的用手机时间我一般会逛数学帖子，看知乎，和别人聊天。

制作这个主页的目的主要是：
1.收集数学资料包括（自己制作的和别人的）
1.向不熟悉的人介绍自己
1.未雨绸缪
1.找乐子
特别是借助网络资源辅助自己学习数学。 我的人生理想之一是做出属于自己的数学成果，但是目前我的数学水平并不高，我还需要学习很多很多。我的数学兴趣主要偏代数方向，会基础的LaTeX(PDF与PPT), 一点点C++语言(托高中信息竞赛的福), 一点点MMA. 外语方面，听：基本能听懂本科生阶段的网课，但是报告基本听不懂(也许是南美口音和数学水平的问题), 说：没有和外国人口头交流过数学，读：不使用(极少极少)使用翻译软件能看懂notes, textbook or paper ，写：写过中英混杂的notes, 在MSE上提过问题并且用英语书面交流问题。 法语：还在入门。
Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
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

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
