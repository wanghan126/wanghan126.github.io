---
permalink: /
title: ""
excerpt: ""
author_profile: true
---

{% include base_path %}

**王晗（Han Wang）：上海交通大学电子信息与电气工程学院电气工程系助理研究员** <br>[[学校官网个人主页]](https://eei.sjtu.edu.cn/faculty-detail.php?id=1411)

主要研究方向
------
* __电力系统不确定性分析__
* __微电网潮流分析__
* __交通网-配电网耦合分析与协同运行__


工作经历
------
* 2022/07-现在&ensp;&ensp;&nbsp;&nbsp;&nbsp;&nbsp;**助理研究员**
  * 上海交通大学&nbsp;电子信息与电气工程学院电气工程系
  
* 2020/07-2022/06&nbsp;&nbsp;**博士后**
  * 上海交通大学&nbsp;电子信息与电气工程学院电气工程系

* 2019/05-2020/01&nbsp;&nbsp;**访问学者**
  * 美国伊利诺伊理工大学&nbsp;电气与计算机工程系

学习经历
------
* 2015/09-2020/06&nbsp;&nbsp;上海交通大学&nbsp;&nbsp;电气工程&ensp;&ensp;**博士**
* 2011/09-2015/06&nbsp;&nbsp;浙江大学&nbsp;&nbsp;电力系统及其自动化&nbsp;&nbsp;**学士**

学术论著 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/publications)
------

<!--
  <blockquote> <p>专著</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "book" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "book" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>
-->

  <blockquote> <p>英文期刊论文</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "journal-en" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "journal-en" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>

  <blockquote> <p>中文期刊论文</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "journal-zh" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "journal-zh" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>
<!--
  <blockquote> <p>中文期刊论文</p> </blockquote>
  <ol>
  {% for post in site.publications reversed %}
  {% if post.type == "conference-en" %}
    {% if post.corresponding %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  
  {% for post in site.publications reversed %}
  {% if post.type == "conference-en" %}
    {% if post.corresponding %}
	{% else %}
	  {% include archive-single-cv.html %}
	{% endif %}
  {% endif %}
  {% endfor %}
  </ol>
-->

<!--  
学术报告 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/talks)
------
  <ol>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ol>
-->

科研项目 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/projects)
------
   {% include_relative projects/projects_content.html %}

专利 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/patents)
------
  <ol>{% for post in site.posts reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

荣誉奖励 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/prizes)
------
   {% include_relative prizes/prizes_content.md %}

社会兼职 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/positions)
------
   {% include_relative positions/positions_content.md %}
   
<!--
课程教学 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/teaching)
------
   <ul>{% for post in site.teaching reversed %}
       {% include archive-single-cv.html %} 
       {% endfor %}</ul>

研究生 [<img src="images/skip_to.jpg" width="20" alt="详细情况" />](/graduates)
------
   {% include_relative graduates/graduates_content.html %}
-->
