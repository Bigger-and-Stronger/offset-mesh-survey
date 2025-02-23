# A Survey on Work Related to Offset Mesh Generation

Here is a list of related work on offset mesh generation that I have collected and complied.
I will update this list on a regular basis.

I add emoji :star: after each project item **based on my own assessment** of their importance.
The more :star: a project item has, the more important it is **from my perspective**.

The emoji :white_check_mark: after the `[code]` indicates that this code has been verified by me to be valid.

:clap: If you have any suggestions for improvements, please raise an issue or contact me.

# 2024
- [Daniel Zint](https://daniel-zint.github.io/), Zhouyuan Chen, Yifei Zhu, Denis Zorin, Teseo Schneider, Daniele Panozzo. "Topological Offsets". (arXiv 2024) [[Paper]](https://arxiv.org/abs/2407.07725) [[Test Data]](https://github.com/daniel-zint/topological-offsets-data):star::star:
  - <font color=gray> A type of offset operation that differs from traditional offset, where the offset results are expected to maintain the same topology as *"infinitesimal offset"*. </font>
- Hongyi Cao, Gang Xu, Renshu Gu, Jinlan Xu, Xiaoyu Zhang, Timon Rabczuk, Yuzhe Luo, Xifeng Gao. "Robust and Feature-Preserving Offset Meshing". (arXiv 2024) [[Paper]](https://arxiv.org/abs/2412.15564):star::star:
  - <font color=gray> This paper appears to be an updated version of the previous work, "A Parallel Feature-preserving Mesh Variable Offsetting Method with Dynamic Programming" (see below), and the offset operation being performed is a variant of the conventional offset, referred to as *"mitered offset"*. </font>
- **PCO**: [Lei Wang](https://alan-leo-wong.github.io/), Xudong Wang, Pengfei Wang, Shuangmin Chen, Shiqing Xin, Jiong Guo, Wenping Wang, Changhe Tu. "PCO: Precision-Controllable Offset Surfaces with Sharp Features". (SIGGRAPH Asia 2024, TOG 2024) [[Paper]](https://dl.acm.org/doi/10.1145/3687920) [[Project Page]](https://alan-leo-wong.github.io/SIGASIA24-PCO-ProjectPage/) <font color=orange>[Code (coming soon...)]</font>:star::star::star:
- [Pengfei Wang](https://pengfei.me/), Jiantao Song, Lei Wang, Shiqing Xin, Dongming Yan, Shuangmin Chen, Changhe Tu, Wenping Wang. "Towards Voronoi Diagrams of Surface Patches". (TVCG 2024) [[Paper]](https://pengfei.me/assets/papers/spaceVoronoi.pdf):star::star::star:
- Jiayi Dai, Yiqun Wang, Dong-Ming Yan. "Feature-preserving shrink wrapping with adaptive alpha" (CAGD 2024) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0167839624000554)

# 2023
- **FPO**: [Daniel Zint](https://daniel-zint.github.io/), Nissim Maruani, M Rouxel-Labb, Pierre Alliez. "Feature-Preserving Offset Mesh Generation from Topology-Adapted Octrees". (ESGP 2023, CGF 2023) [[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14906) [[Code]](https://github.com/daniel-zint/offsets-and-remeshing):white_check_mark::star::star:
- Hongyi Cao, Gang Xu, Renshu Gu, Jinlan Xu, Xiaoyu Zhang, Timon Rabczuk. "A Parallel Feature-preserving Mesh Variable Offsetting Method with Dynamic Programming" (arXiv 2023) [[Paper]](https://arxiv.org/abs/2310.08997) [[Code]](https://github.com/iGame-Lab/PFPOffset?tab=readme-ov-file):star:
  - <font color=gray> This paper appears to have uploaded an updated version "Robust and Feature-Preserving Offset Meshing" (see above), and the offset operation being performed is variant of the conventional offset, refered to as *"variable offset"* (allows for each facet to have a different offset distance). </font>

# 2022
- **AlphaWrap**: Cédric Portaneri, Mael Rouxel-Labbé, Michael Hemmer, David Cohen-Steiner, Pierre Alliez. "Alpha wrapping with an offset". (TOG 2022) [[Paper]](https://dl.acm.org/doi/abs/10.1145/3528223.3530152) [[Code (available in CGAL)]](https://github.com/CGAL/cgal/):white_check_mark: [[Documentation]](https://doc.cgal.org/latest/Alpha_wrap_3/index.html#Chapter_3D_Alpha_wrapping):star:

# 2019
- **HSP**: Zhen Chen, Daniele Panozzo, Jérémie Dumas. "Half-Space Power Diagrams and Discrete Surface Offsets". (TVCG 2019) [[Paper]](https://ieeexplore.ieee.org/abstract/document/8865648) [[Project Page]](https://www.jdumas.org/publication/2019/voroffset/) [[Code]](https://github.com/geometryprocessing/voroffset):white_check_mark: [[Video]](https://www.youtube.com/watch?v=u8qtOkJqEO0):star:

# 2018
- Wenlong Meng, Shuangmin Chen, Zhenyu Shu, Shi-Qing Xin, Hongbo Fu, Changhe Tu. "Efficiently computing feature-aligned and high-quality polygonal offset surfaces". (C&G 2018) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0097849317300961)

# 2014
- Stéphane Calderon, Tamy Boubekeur. "Point morphology". (TOG 2014) [[Paper]](https://dl.acm.org/doi/10.1145/2601097.2601130):star:

# 2013
- **Thickening**: [Charlie C.L. Wang](https://mewangcl.github.io/), Yong Chen. "Thickening freeform surfaces for solid fabrication". (Rapid Prototyping Journal 2013) [[Paper]](https://www.emerald.com/insight/content/doi/10.1108/rpj-02-2012-0013/full/html) [[Project Page]](https://mewangcl.github.io/Projects/MeshThickeningProj.htm) [[Code]](https://mewangcl.github.io/Projects/MeshThickeningProj.htm):white_check_mark::star:
  - <font color=gray> The offset results for open surfaces differ from conventional offset, generating thickened shell-like models </font>

# 2012
- **LDNI**: [Charlie C.L. Wang](https://mewangcl.github.io/), Dinesh Manocha. "GPU-based offset surface computation using point samples". (CAD 2013) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448512002205) [[Project Page]](https://mewangcl.github.io/Projects/GPUBasedLDNI_DLLProj.htm) [[Code]](https://mewangcl.github.io/Projects/GPUBasedLDNI_DLLProj.htm):white_check_mark::star:

# 2011
- Shengjun Liu, Charlie C.L. Wang. "Fast Intersection-Free Offset Surface Generation From Freeform Models With Triangular Meshes". (Transactions on Automation Science and Engineering 2011) [[Paper]](https://ieeexplore.ieee.org/document/5570949)
- Yong Chen, Charlie C.L. Wang. "Uniform offsetting of polygonal model based on Layered Depth-Normal Images". (CAD 2011) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448510001697)

# 2010
- [Jyh-Ming Lien](https://cs.gmu.edu/~jmlien/doku.php). "A Simple Method for Computing Minkowski Sum Boundary in 3D Using Collision Detection". (Algorithmic Foundation of Robotics VIII) [[Paper]](https://cs.gmu.edu/~jmlien/lib/exe/fetch.php?media=lien_wafr08.pdf) [<font color=red>[Project Page (may not available now)]</font>](http://masc.cs.gmu.edu/wiki/SimpleMsum) [<font color=red>[Code (may not available now)]</font>](http://masc.cs.gmu.edu/wiki/Software#m+3dmesh)
- Andrei Zaharescu, Edmond Boyer, Radu Horaud. "Topology-Adaptive Mesh Deformation for Surface Evolution, Morphing, and Multiview Reconstruction". (Transactions on Pattern Analysis and Machine Intelligence 2010) [[Paper]](https://ieeexplore.ieee.org/abstract/document/5482586)
- Marcel Campen, Leif Kobbelt. "Polygonal Boundary Evaluation of Minkowski Sums and Swept Volumes". (CGF 2010) [[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2010.01770.x)

# 2009
- Sang Hun Lee. "Offsetting operations on non-manifold topological models". (CAD 2009) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448509001523)

# 2008
- [Jyh-Ming Lien](https://cs.gmu.edu/~jmlien/doku.php). "Covering Minkowski Sum Boundary Using Points with Applications". (CAGD 2008) [[Paper]](https://cs.gmu.edu/~jmlien/lib/exe/fetch.php?media=lien-pointbasedminkowskisum.pdf) [<font color=red>[Project Page (may not available now)]</font>](http://masc.cs.gmu.edu/wiki/PointMsum) [<font color=red>[Code (may not available now)]</font>](http://masc.cs.gmu.edu/wiki/Software#m+3dpt):white_check_mark:
    - <font color=gray> Fortunately, I have retained this original code and have made some modifications to make it usable. If you require this code, please feel free to contact me. </font>
- Darko Pavić, Leif Kobbelt. "High-Resolution Volumetric Computation of Offset Surfaces with Feature Preservation". (CGF 2008) [[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2008.01113.x)

# 2007
- [Jyh-Ming Lien](https://cs.gmu.edu/~jmlien/doku.php). "Point-Based Minkowski Sum Boundary". (PG 2007) [[Paper]](https://ieeexplore.ieee.org/abstract/document/4392736)
- Peter Hachenberger. "Exact Minkowski sums of polyhedra and exact and efficient decomposition of polyhedra in convex pieces". (European Symposium on Algorithms 2007) [[Paper]](https://link.springer.com/chapter/10.1007/978-3-540-75520-3_59)

# 2006
- Joon-Kyung Seong, Gershon Elber, Myung-Soo Kim. "Trimming local and global self-intersections in offset curves/surfaces using distance maps". (CAD 2006) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448505001491)

# 2005
- Yong Chen, Hongqing Wang, David W. Rosen, Jarek Rossignac. "A point-based offsetting method of polygonal meshes". (ASME Journal of Computing and Information Science in Engineering 2005) [[Paper]](https://d1wqtxts1xzle7.cloudfront.net/30743529/OffsetYong-libre.pdf?1392056140=&response-content-disposition=inline%3B+filename%3DA_point_based_offsetting_method_of_polyg.pdf&Expires=1740158862&Signature=YFe6MBnPfTKD9S1RKvAZ0xluWEqlvPeDnujJ-09Fkj0OnEZwnkU~5arEKrZMOukYdvZVnZs2fQ5N3A58MLSOfthSGYWMj0cckyPtSmTyZvLuDd7kKUymoa4B1g8wFRtDj48yauFvARnsH4V4-Kpu225yrUQO~rVcPsLcBRklLe7ODllcc9zICCqmdxa5fezJ27wDKd3nF1UAEm3OmACIHngm3842PmZWBd-Pal5Qj7zXXiXZMZuLMu5xypaFzSegsSfmVKKUxV-tcilELbV3u15XHHNcK0Z3s-BNOPVBzT-R14tEvsmsZnpHyF-3dK13extqNW5LXJNABoiQcudpiw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
- Yong Chen, Hongqing Wang, David W. Rosen, Jarek Rossignac. "Filleting and rounding using a point-based method". (Design Automation Conference 2005) [[Paper]](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2005/533/313972)
- Su-Jin Kim, Min-Yang Yang. "Triangular mesh offset for generalized cutter". (CAD 2005) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448504002027)

# 2004
- Varadhan, Gokul, Dinesh Manocha. "Accurate Minkowski sum approximation of polyhedral models". (PG 2004) [[Paper]](https://ieeexplore.ieee.org/abstract/document/1348370)
- Su-Jin Kim, Dong-Yoon Lee, Min-Yang Yang. "Offset Triangular Mesh Using the Multiple Normal Vectors of a Vertex". (CADA 2004) [[Paper]](https://www.tandfonline.com/doi/abs/10.1080/16864360.2004.10738269)
- Wonhyung Jung, Hayong Shin, Byoung K. Choi. "Self-intersection Removal in Triangular Mesh Offsetting". (CAD 2004) [[Paper]](https://www.tandfonline.com/doi/abs/10.1080/16864360.2004.10738290)

# 2002
- Cha-Soo Jun, Dong-Soo Kim, Sehyung Park. "A new curve-based approach to polyhedral machining". (CAD 2002) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448501001105)

# 1999
- Sang Hun Lee. "Offsetting operations on non-manifold boundary representation models with simple geometry". (Solid Modeling and Applications 1999) [[Paper]](https://dl.acm.org/doi/10.1145/304012.304017)
- Breen, David E., Sean Mauch. "Generating Shaded Offset Surfaces with Distance, Closest-Point and Color Volumes". (Proceedings of the international workshop on volume graphics 1999) [[Paper]](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=0bf85b578dffca47888bfc1d0be03a48e6d9ce92)
- E.E. Hartquist, J.P. Menon, K. Suresh, H.B. Voelcker, J. Zagajac. "A computing strategy for applications involving offsets, sweeps, and Minkowski operations". (CAD 1999) [[Paper]](https://www.sciencedirect.com/science/article/pii/S0010448599000147)

# 1996
- Yu Wang. "Intersection of offsets of parametric surfaces". (CAGD 1996) [[Paper]](https://www.sciencedirect.com/science/article/pii/0167839695000399)

# Other Project
- **LDNI-based-Solid-Modeling**: [[Project Page]](https://ldnibasedsolidmodeling.sourceforge.net/) [[Code]](https://github.com/DebbieLeung/LDNI-based-Solid-Modeling):white_check_mark: [[Video]](https://www.youtube.com/watch?v=G75mS1VGqx0&t=2s)

# Software
- Rhino 8 [[Documentation]](https://docs.mcneel.com/rhino/8/help/en-us/commands/offsetmesh.htm)
  - <font color=gray> The `OffsetMesh` operation in Rhino 8 is accomplished by directly moving the vertices, while the `OffsetSrf` operation on a B-rep input produces results that are more akin to the widely recognized offset results. </font>
- CATIA
- NX
  - <font color=gray> It may be one of the better industrial software for performing offset mesh operations, but in many cases it is unable to complete the operation, possibly due to the generation of self-intersections. </font>
- Solidworks
- ZW3D
  - <font color=gray> It seems to utilize a method involving the use of voxels for isosurface extraction. </font>
- CAXA