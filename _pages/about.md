---
permalink: /
title: "简介"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

姚璜，武汉大学工学博士（导师：龚健雅 院士），华中师范大学人工智能教育学部数字媒体技术专业副教授，依托教育大数据应用技术国家工程研究中心、人工智能与教育新形态教育部哲学社会科学实验室、华中师范大学前沿交叉研究院等平台长期开展机器学习、VR/AR、人工智能+教育方向的科研和教学工作。当前研究领域包括计算机视觉（动作质量评价(Action Quality Assessment)/遥感影像分类）, 人机交互（教育智能体，VR教育应用）， 人地耦合关系研究（地理信息系统GIS/基于智能体的建模ABM）等。

教育经历
======
- *2001 - 2005*，武汉大学，工学学士 
- *2005 - 2007*，武汉大学，工学硕士
- *2007 - 2011*，武汉大学，工学博士

工作经历
======
- *2012 - now*，华中师范大学
- *2017 - 2018*，俄亥俄州立大学
  
在研项目
======
1.国家自然科学基金联合基金重点项目课题，青藏高原南部旧石器人群高寒环境适应过程与机制（U2574202）
2.国家重点研发计划课题，多语种多模态语料库众智化生成与虚拟交互系统（2023YFC3305601）
3.虚实融合智能交互实验教学关键技术研究及应用（CCNU25ZDPY012）
4.智能分析与个性化导学智能体研发（KJH2025-0023）
5.文档页面图片智能几何校正技术研发（KJH2025-0061）

论文发表
======
1.Tian, Yuan, Cai, Hang, Yao, Huang, Chen, Di, Facial Expression Recognition Method Based on Octonion Orthogonal Feature Extraction and Octonion Vision Transformer, International Journal of Intelligent Systems, 2025, 6388642, 13 pages, 2025. https://doi.org/10.1155/int/6388642.
2.Yao, H.; Yang, X.; Chen, D.; Wang, Z.; Tian, Y. Facial Expression Recognition Based on Fine-Tuned Channel–Spatial Attention Transformer. Sensors 2023, 23, 6799. https://doi.org/10.3390/s23156799.
3.Liu, L.; Wei, Y.; Wang, Y.; Yao, H.; Chen, D. Using Double-Layer Patch-Based Contrast for Infrared Small Target Detection. Remote Sens. 2023, 15, 3839. https://doi.org/10.3390/rs15153839 .
4.Yao, Huang, Liping Liu, Yantao Wei, Di Chen, and Mingwen Tong. 2023. "Infrared Small-Target Detection Using Multidirectional Local Difference Measure Weighted by Entropy" Sustainability 15, no. 3: 1902. https://doi.org/10.3390/su15031902.
5.Hu, Meijia, Yantao Wei, Mengsiying Li, Huang Yao, Wei Deng, Mingwen Tong, and Qingtang Liu. 2022. "Bimodal Learning Engagement Recognition from Videos in the Classroom" Sensors 22, no. 16: 5932. https://doi.org/10.3390/s22165932.
6.X. Zhang, Y. Wei, W. Cao, H. Yao, J. Peng and Y. Zhou, "Local Correntropy Matrix Representation for Hyperspectral Image Classification," in IEEE Transactions on Geoscience and Remote Sensing, vol. 60, pp. 1-13, 2022, Art no. 5525813, doi: 10.1109/TGRS.2022.3162100.
7.Xiao G, Wei Y, Yao H, et al. Hierarchical broad learning system for hyperspectral image classification[J]. IET Image Processing, 2021.
8.Zhang X , Wei Y , Yao H , et al. Locally Homogeneous Covariance Matrix Representation for Hyperspectral Image Classification[J]. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2021, PP(99):1-1.
9.Zhang X, Wei Y, Yao H, et al. Improved Local Covariance Matrix Representation for Hyperspectral Image Classification[C]//IGARSS 2020-2020 IEEE International Geoscience and Remote Sensing Symposium. IEEE, 2020: 68-71.
10.Yao, H., et al. (2020). "Broad Learning System with Locality Sensitive Discriminant Analysis for Hyperspectral Image Classification." Mathematical Problems in Engineering.

------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
