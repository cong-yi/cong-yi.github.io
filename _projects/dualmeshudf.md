---
layout: page
title: DualMeshUDF
description: Surface Extraction from Neural Unsigned Distance Fields
img: assets/img/publication_preview/dualmeshudf.png
importance: 1
category: Neural Implicit Representation
project_intro: true
github: https://github.com/cong-yi/DualMesh-UDF
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
  <a href="https://cong-yi.github.io/">Congyi Zhang</a>*, 
  <a href="https://carrie-lin.github.io/">Guying Lin</a>*, 
  <a href="https://scholar.google.com.hk/citations?user=JAzFhXQAAAAJ">Lei Yang</a>, 
  <a href="https://people.tamu.edu/~xinli/">Xin Li</a>, 
  <a href="https://i.cs.hku.hk/~taku/">Taku Komura</a>, 
  <a href="https://people.engr.tamu.edu/schaefer/index.html">Scott Schaefer</a>, 
  <a href="https://people.engr.tamu.edu/keyser/index.html">John Keyser</a>, 
  <a href="https://engineering.tamu.edu/cse/profiles/Wang-Wenping.html">Wenping Wang</a>
</p>
<p class="text-center" style="font-size: 0.9rem; margin-top: -1rem; margin-bottom: 1.5rem;">* joint first authors</p>

<div class="text-center project-links">
  <a href="https://arxiv.org/abs/2309.08878" class="btn btn-outline-primary btn-sm">Paper (arXiv)</a>
  <a href="https://github.com/cong-yi/DualMesh-UDF" class="btn btn-outline-dark btn-sm ml-2">Code (GitHub)</a>
</div>

<h4 class="project-section-title">Abstract</h4>
We propose a method, named DualMesh-UDF, to extract a surface from unsigned distance functions (UDFs), encoded by neural networks, or neural UDFs. Neural UDFs are becoming increasingly popular for surface representation because of their versatility in presenting surfaces with arbitrary topologies, as opposed to the signed distance function that is limited to representing a closed surface. However, the applications of neural UDFs are hindered by the notorious difficulty in extracting the target surfaces they represent. Recent methods for surface extraction from a neural UDF suffer from significant geometric errors or topological artifacts due to two main difficulties: (1) A UDF does not exhibit sign changes; and (2) A neural UDF typically has substantial approximation errors. DualMesh-UDF addresses these two difficulties. Specifically, given a neural UDF encoding a target surface S to be recovered, we first estimate the tangent planes of S at a set of sample points close to S. Next, we organize these sample points into local clusters, and for each local cluster, solve a linear least squares problem to determine a final surface point. These surface points are then connected to create the output mesh surface, which approximates the target surface. The robust estimation of the tangent planes of the target surface and the subsequent minimization problem constitute our core strategy, which contributes to the favorable performance of DualMesh-UDF over other competing methods. To efficiently implement this strategy, we employ an adaptive Octree. Within this framework, we estimate the location of a surface point in each of the octree cells identified as containing part of the target surface. Extensive experiments show that our method outperforms existing methods in terms of surface reconstruction quality while maintaining comparable computational efficiency.

<h4 class="project-section-title">BibTeX</h4>
```bibtex
@InProceedings{zhang2023dualmeshudf,
    author    = {Zhang, Congyi and
                 Lin, Guying and
                 Yang, Lei and
                 Li, Xin and
                 Komura, Taku and
                 Schaefer, Scott and
                 Keyser, John and
                 Wang, Wenping},
    title     = {Surface Extraction from Neural Unsigned Distance Fields},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2023},
    pages     = {0000-0000}
}
```

