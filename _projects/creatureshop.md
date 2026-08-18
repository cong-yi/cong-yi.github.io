---
layout: page
title: CreatureShop
description: Interactive 3D Character Modeling and Texturing from a Single Color Drawing
img: assets/img/publication_preview/creatureshop.jpg
importance: 1
category: Sketch-based modeling
project_intro: true
github: https://github.com/cong-yi/CreatureShop
related_publications: CreatureShop2022
_styles: |
  .project-authors {
    font-size: 1.1rem;
    margin-bottom: 1.5rem;
  }
  .project-links {
    margin-bottom: 2rem;
  }
  .project-section-title {
    font-size: 1.5rem;
    margin-top: 2rem;
    margin-bottom: 1rem;
    border-bottom: 1px solid #eee;
    padding-bottom: 0.5rem;
  }
---

<p class="text-center project-authors">
  <strong>Authors:</strong> 
  <a href="https://cong-yi.github.io/">Congyi Zhang</a>, 
  <a href="https://scholar.google.com.hk/citations?user=JAzFhXQAAAAJ">Lei Yang</a>, 
  <a href="https://scholar.google.com/citations?user=UhjTC7AAAAAJ">Nenglun Chen</a>, 
  <a href="https://www.cs.ubc.ca/~nvining/">Nicholas Vining</a>, 
  <a href="https://www.cs.ubc.ca/~sheffa/">Alla Sheffer</a>, 
  <a href="https://i.cs.hku.hk/~fcmlau/">Francis C.M. Lau</a>, 
  <a href="https://cs.pku.edu.cn/info/1178/1575.htm">Guoping Wang</a>, 
  <a href="https://engineering.tamu.edu/cse/profiles/Wang-Wenping.html">Wenping Wang</a>
</p>

<div class="text-center project-links">
  <a href="https://arxiv.org/abs/2208.05572" class="btn btn-outline-primary btn-sm">Paper (arXiv)</a>
  <a href="https://github.com/cong-yi/CreatureShop" class="btn btn-outline-dark btn-sm ml-2">Code (GitHub)</a>
</div>

<h4 class="project-section-title">Abstract</h4>
Creating 3D shapes from 2D drawings is an important problem with applications in content creation for computer animation and virtual reality. We introduce a new sketch-based system, *CreatureShop*, that enables amateurs to create high-quality textured 3D character models from 2D drawings with ease and efficiency. CreatureShop takes an input bitmap drawing of a character (such as an animal or other creature), depicted from an arbitrary descriptive pose and viewpoint, and creates a 3D shape with plausible geometric details and textures from a small number of user annotations on the 2D drawing. Our key contributions are a novel oblique view modeling method, a set of systematic approaches for producing plausible textures on the invisible or occluded parts of the 3D character (as viewed from the direction of the input drawing), and a user-friendly interactive system. We validate our system and methods by creating numerous 3D characters from various drawings, and compare our results with related works to show the advantages of our method. We perform a user study to evaluate the usability of our system, which demonstrates that our system is a practical and efficient approach to create fully-textured 3D character models for novice users.

<h4 class="project-section-title">Demo Video</h4>
<div class="text-center">
  <video width="100%" autoplay loop muted controls>
    <source src="/assets/creatureshop/assets/Creatureshop_Demo.m4v" type="video/mp4">
  </video>
</div>

<h4 class="project-section-title">BibTeX</h4>
```bibtex
@ARTICLE{zhang2022creatureshop,
	author={Zhang, Congyi and Yang, Lei and Chen, Nenglun and Vining, Nicholas and Sheffer, Alla and Lau, Francis C.M. and Wang, Guoping and Wang, Wenping},
	journal={IEEE Transactions on Visualization and Computer Graphics},
	title={CreatureShop: Interactive 3D Character Modeling and Texturing from a Single Color Drawing},
	year={2022},
	pages={1-18},
	doi={10.1109/TVCG.2022.3197560}
}
```

