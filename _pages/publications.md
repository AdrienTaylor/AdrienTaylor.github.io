---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022,2021,2020,2019,2018,2017]
abbr: [preprint,book,journal,conference,PhDthese]
nav: true
---

**publications policy ---** I do my best to maintain updated versions with possible typo corrections and clarifications on arxiv (both are generally marked in bold and red for easy reference). Therefore, please favor the arxiv versions to the official published ones.

**thesis ---** my thesis (under the supervision of [François Glineur](http://perso.uclouvain.be/francois.glineur) and [Julien Hendrickx](http://perso.uclouvain.be/julien.hendrickx)) had the chance to be awarded the <a href="https://uclouvain.be/en/research-institutes/icteam/icteam-thesis-awards-since-2011.html">ICTEAM thesis award</a> for 2018, the IBM-FNRS innovation award	 for 2018, and to be a finalist for the <a href="http://www.mathopt.org/?nav=tucker">AW Tucker prize</a> for 2018. In addition, we received the [2017 best paper award](https://link.springer.com/article/10.1007/s11590-018-1379-y) in Optimization Letters, for a joint work with [Etienne de Klerk](https://sites.google.com/site/homepageetiennedeklerk/) and [François Glineur](http://perso.uclouvain.be/francois.glineur) (for [this paper](https://link.springer.com/article/10.1007/s11590-016-1087-4)).

**codes ---** see my <a href="https://github.com/AdrienTaylor">github profile</a> for all my codes. The current version of the *Performance EStimation TOolbox* (PESTO) is available from [here](https://github.com/AdrienTaylor/Performance-Estimation-Toolbox) ([user manual](https://github.com/AdrienTaylor/Performance-Estimation-Toolbox/blob/master/UserGuide.pdf), [conference proceeding](https://perso.uclouvain.be/julien.hendrickx/availablepublications/PESTO_CDC_2017.pdf)). The numerical worst-case analyses from PEP can now be performed just by writting the algorithms just as you would implement them in Matlab. The new *PEPit* (performance estimation in Python) is available from [here](https://github.com/bgoujaud/PEPit) (due to the fabulous work of Baptiste Goujaud and Céline Moucer). It is easy to experiment with it using this [notebook](https://github.com/bgoujaud/PEPit/blob/master/ressources/demo/PEPit_demo.ipynb) (see [colab](https://colab.research.google.com/github/bgoujaud/PEPit/blob/master/ressources/demo/PEPit_demo.ipynb)).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.abbr %}
  <h2 class="status">{{y}}s</h2>
  {% bibliography -f papers -q @*[abbr={{y}}]* %}
{% endfor %}

</div>
