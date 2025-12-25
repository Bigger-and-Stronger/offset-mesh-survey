# A Survey on Work Related to Offset Mesh Generation

Here is a list of related work on offset mesh generation that I have collected and complied.
I will update this list on a regular basis.

The emoji :white_check_mark: after the `[code]` indicates that this code has been verified by me to be valid.

:clap: If you have any suggestions for improvements, please raise an issue.

> [!NOTE]
> Please note that this repo focuses exclusively on papers related to offset operations, while intentionally excluding the extraction of isosurfaces from (signed) distance fields.
> I consider these to be distinct approaches, differing primarily in whether the underlying surface is explicitly provided.

# :page_with_curl: Papers

<table> 
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Variational-Mesh-Offsetting-by-Smoothed-Winding-Number.png" width="300"><td>

**Variational Mesh Offsetting by Smoothed Winding Number**

Haoran Sun, Shuang Wu, Hujun Bao, [Jin Huang]

2025, TVCG

[[doi]](https://pubmed.ncbi.nlm.nih.gov/41308093/) [[pdf]](http://www.cad.zju.edu.cn/home/hj/25/wnoffset.pdf)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Topological-Offsets.png" width="300"><td>

**Topological Offsets**

[Daniel Zint], Zhouyuan Chen, Yifei Zhu, [Denis Zorin], Teseo Schneider, [Daniele Panozzo]

2025, TOG (SIGGRAPH)

[[doi]](https://arxiv.org/abs/2407.07725) [[pdf]](https://cims.nyu.edu/gcl/papers/2025-Topological-Offsets.pdf) [[code]](https://github.com/wildmeshing/topological-offsets):white_check_mark:
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/OffsetCrust-Variable-Radius-Offset-Approximation-with-Power-Diagrams.png" width="500"><td>

**OffsetCrust: Variable-Radius Offset Approximation with Power Diagrams**

[Zihan Zhao], [Pengfei Wang], [Shuangmin Chen], [Shiqing Xin], [Changhe Tu], [Wenping Wang]

15 July 2025, arXiv

[[doi]](https://arxiv.org/abs/2507.10924) [[code]](https://github.com/zih-an/offsetcrust)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Towards-Voronoi-Diagrams-of-Surface-Patches.png" width="300"><td>

**Towards Voronoi Diagrams of Surface Patches**

[Pengfei Wang], Jiantao Song, [Lei Wang], [Shiqing Xin], [Dongming Yan], [Shuangmin Chen], [Changhe Tu], [Wenping Wang]

17 Jan 2025, TVCG

[[doi]](https://ieeexplore.ieee.org/document/10845125) [[pdf]](https://pengfei.me/assets/papers/spaceVoronoi.pdf)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Robust-and-Feature-Preserving-Offset-Meshing.png" width="300"><td>

**Robust and Feature-Preserving Offset Meshing**

Hongyi Cao, Gang Xu, Renshu Gu, Jinlan Xu, Xiaoyu Zhang, Timon Rabczuk, Yuzhe Luo, [Xifeng Gao]

20 Dec 2024, arXiv

[[doi]](https://arxiv.org/abs/2412.15564)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/PCO-Precision-Controllable-Offset-Surfaces-with-Sharp-Features.png" width="300"><td>

**PCO: Precision-Controllable Offset Surfaces with Sharp Features**

[Lei Wang], Xudong Wang, [Pengfei Wang], [Shuangmin Chen], [Shiqing Xin], Jiong Guo, [Wenping Wang], [Changhe Tu]

19 Nov 2024, TOG (SIGGRAPH Asia)

[[doi]](https://dl.acm.org/doi/10.1145/3687920) [[project]](https://alan-leo-wong.github.io/SIGASIA24-PCO-ProjectPage/) [[code]](https://github.com/Alan-Leo-Wong/PCO):white_check_mark:
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Feature-preserving-shrink-wrapping-with-adaptive-alpha.png" width="300"><td>

**Feature-preserving shrink wrapping with adaptive alpha**

Jiayi Dai, Yiqun Wang, [Dongming Yan]

Jun 2024, CAGD (GMP 2024)

[[doi]](https://www.sciencedirect.com/science/article/pii/S0167839624000554)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Feature-Preserving-Offset-Mesh-Generation-from-Topology-Adapted-Octrees.png" width="300"><td>

**Feature-Preserving Offset Mesh Generation from Topology-Adapted Octrees**

[Daniel Zint], Nissim Maruani, M Rouxel-Labb, [Pierre Alliez]

10 Aug 2023, CGF (Eurographics Symposium on Geometry Processing 2023)

[[doi]](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14906) [[code]](https://github.com/daniel-zint/offsets-and-remeshing):white_check_mark:
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/A-Parallel-Feature-preserving-Mesh-Variable-Offsetting-Method-with-Dynamic-Programming.png" width="300"><td>

**A Parallel Feature-preserving Mesh Variable Offsetting Method with Dynamic Programming**

Hongyi Cao, Gang Xu, Renshu Gu, Jinlan Xu, Xiaoyu Zhang, Timon Rabczuk

13 Oct 2023, arXiv

[[doi]](https://arxiv.org/abs/2310.08997) [[code]](https://github.com/iGame-Lab/PFPOffset?tab=readme-ov-file)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Alpha-wrapping-with-an-offset.png" width="300"><td>

**Alpha wrapping with an offset**

Cédric Portaneri, Mael Rouxel-Labbé, Michael Hemmer, [David Cohen-Steiner], [Pierre Alliez]

22 Jul 2022, TOG

[[doi]](https://dl.acm.org/doi/abs/10.1145/3528223.3530152) [[code (available in CGAL)]](https://github.com/CGAL/cgal/):white_check_mark: [[doc]](https://doc.cgal.org/latest/Alpha_wrap_3/index.html#Chapter_3D_Alpha_wrapping)
</tr>
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Half-Space-Power-Diagrams-and-Discrete-Surface-Offsets.png" width="300"><td>

**Half-Space Power Diagrams and Discrete Surface Offsets**

Zhen Chen, [Daniele Panozzo], Jérémie Dumas

14 Oct 2019, TVCG

[[doi]](https://ieeexplore.ieee.org/abstract/document/8865648) [[project]](https://www.jdumas.org/publication/2019/voroffset/) [[code]](https://github.com/geometryprocessing/voroffset):white_check_mark: [[video]](https://www.youtube.com/watch?v=u8qtOkJqEO0)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Efficiently-computing-feature-aligned-and-high-quality-polygonal-offset-surfaces.png" width="300"><td>

**Efficiently computing feature-aligned and high-quality polygonal offset surfaces**

Wenlong Meng, [Shuangmin Chen], Zhenyu Shu, [Shiqing Xin], [Hongbo Fu], [Changhe Tu]

Feb 2018, Computers & Graphics (CAD/Graphics 2017)

[[doi]](https://www.sciencedirect.com/science/article/pii/S0097849317300961)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Point-morphology.png" width="300"><td>

**Point morphology**

Stéphane Calderon, Tamy Boubekeur

27 Jul 2014, TOG

[[doi]](https://dl.acm.org/doi/10.1145/2601097.2601130)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Thickening-freeform-surfaces-for-solid-fabrication.png" width="300"><td>

**Thickening freeform surfaces for solid fabrication**

[Charlie C.L. Wang], Yong Chen

30 Sep 2013, Rapid Prototyping Journal

[[doi]](https://www.emerald.com/insight/content/doi/10.1108/rpj-02-2012-0013/full/html) [[project]](https://mewangcl.github.io/Projects/MeshThickeningProj.htm) [[code]](https://mewangcl.github.io/Projects/MeshThickeningProj.htm):white_check_mark:
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/GPU-based-offset-surface-computation-using-point-samples.png" width="300"><td>

**GPU-based offset surface computation using point samples**

[Charlie C.L. Wang], Dinesh Manocha

Feb 2013, CAD (Solid and Physical Modeling 2012)

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448512002205) [[project]](https://mewangcl.github.io/Projects/GPUBasedLDNI_DLLProj.htm) [[code]](https://mewangcl.github.io/Projects/GPUBasedLDNI_DLLProj.htm):white_check_mark:
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Uniform-offsetting-of-polygonal-model-based-on-Layered-Depth-Normal-Images.png" width="300"><td>

**Uniform offsetting of polygonal model based on Layered Depth-Normal Images**

Yong Chen, [Charlie C.L. Wang]

Jan 2011, CAD

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448510001697)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Polygonal-Boundary-Evaluation-of-Minkowski-Sums-and-Swept-Volumes.png" width="300"><td>

**Polygonal Boundary Evaluation of Minkowski Sums and Swept Volumes**

Marcel Campen, Leif Kobbelt

21 Sep 2010, CGF

[[doi]](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2010.01770.x)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Fast-Intersection-Free-Offset-Surface-Generation-From-Freeform-Models-With-Triangular-Meshes.png" width="300"><td>

**Fast Intersection-Free Offset Surface Generation From Freeform Models With Triangular Meshes**

[Shengjun Liu], [Charlie C.L. Wang]

13 Sep 2010, IEEE Transactions on Automation Science and Engineering

[[doi]](https://ieeexplore.ieee.org/document/5570949)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Topology-Adaptive-Mesh-Deformation-for-Surface-Evolution,-Morphing,-and-Multiview-Reconstruction.png" width="300"><td>

**Topology-Adaptive Mesh Deformation for Surface Evolution, Morphing, and Multiview Reconstruction**

Andrei Zaharescu, Edmond Boyer, Radu Horaud

07 Jun 2010, Transactions on Pattern Analysis and Machine Intelligence

[[doi]](https://ieeexplore.ieee.org/abstract/document/5482586)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Offsetting-operations-on-non-manifold-topological-models.png" width="300"><td>

**Offsetting operations on non-manifold topological models**

Sang Hun Lee

Nov 2009, CAD

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448509001523)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/A-Simple-Method-for-Computing-Minkowski-Sum-Boundary-in-3D-Using-Collision-Detection.png" width="300"><td>

**A Simple Method for Computing Minkowski Sum Boundary in 3D Using Collision Detection**

[Jyh-Ming Lien]

2009, Algorithmic Foundation of Robotics VIII

[[pdf]](https://cs.gmu.edu/~jmlien/lib/exe/fetch.php?media=lien_wafr08.pdf) [[project (may not available now)]](http://masc.cs.gmu.edu/wiki/SimpleMsum) [[code (may not available now)]](http://masc.cs.gmu.edu/wiki/Software#m+3dmesh)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Covering-Minkowski-Sum-Boundary-Using-Points-with-Applications.png" width="300"><td>

**Covering Minkowski Sum Boundary Using Points with Applications**

[Jyh-Ming Lien]

Nov 2008, CAGD (Pacific Graphics 2007)

[[pdf]](https://cs.gmu.edu/~jmlien/lib/exe/fetch.php?media=lien-pointbasedminkowskisum.pdf) [[project (may not available now)]](http://masc.cs.gmu.edu/wiki/PointMsum) [[code (may not available now)]](http://masc.cs.gmu.edu/wiki/Software#m+3dpt):white_check_mark: (if you require this code, you can contact me)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Exact-Minkowski-sums-of-polyhedra-and-exact-and-efficient-decomposition-of-polyhedra-in-convex-pieces.png" width="300"><td>

**Exact Minkowski sums of polyhedra and exact and efficient decomposition of polyhedra in convex pieces**

Peter Hachenberger

15 Aug 2008, European Symposium on Algorithms, 2007

[[doi]](https://link.springer.com/chapter/10.1007/978-3-540-75520-3_59)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Filleting-and-rounding-using-a-point-based-method.png" width="300"><td>

**Filleting and rounding using a point-based method**

Yong Chen, Hongqing Wang, David W. Rosen, Jarek Rossignac

11 Jun 2008, Design Automation Conference

[[doi]](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2005/533/313972)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/High-Resolution-Volumetric-Computation-of-Offset-Surfaces-with-Feature-Preservation.png" width="300"><td>

**High-Resolution Volumetric Computation of Offset Surfaces with Feature Preservation**

Darko Pavić, Leif Kobbelt

24 Apr 2008, CGF

[[doi]](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2008.01113.x)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Point-Based-Minkowski-Sum-Boundary.png" width="300"><td>

**Point-Based Minkowski Sum Boundary**

[Jyh-Ming Lien]

04 Dec 2007, (PG 2007)

[[doi]](https://ieeexplore.ieee.org/abstract/document/4392736)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Trimming-local-and-global-self-intersections-in-offset-curves.png" width="300"><td>

**Trimming local and global self-intersections in offset curves/surfaces using distance maps**

Joon-Kyung Seong, Gershon Elber, Myung-Soo Kim

Mar 2006, CAD

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448505001491)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Triangular-mesh-offset-for-generalized-cutter.png" width="300"><td>

**Triangular mesh offset for generalized cutter**

Su-Jin Kim, Min-Yang Yang

1 Sep 2005

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448504002027)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/A-point-based-offsetting-method-of-polygonal-meshes.png" width="300"><td>

**A point-based offsetting method of polygonal meshes**

Yong Chen, Hongqing Wang, David W. Rosen, Jarek Rossignac

2005, ASME Journal of Computing and Information Science in Engineering

[[pdf]](https://d1wqtxts1xzle7.cloudfront.net/30743529/OffsetYong-libre.pdf?1392056140=&response-content-disposition=inline%3B+filename%3DA_point_based_offsetting_method_of_polyg.pdf&Expires=1740158862&Signature=YFe6MBnPfTKD9S1RKvAZ0xluWEqlvPeDnujJ-09Fkj0OnEZwnkU~5arEKrZMOukYdvZVnZs2fQ5N3A58MLSOfthSGYWMj0cckyPtSmTyZvLuDd7kKUymoa4B1g8wFRtDj48yauFvARnsH4V4-Kpu225yrUQO~rVcPsLcBRklLe7ODllcc9zICCqmdxa5fezJ27wDKd3nF1UAEm3OmACIHngm3842PmZWBd-Pal5Qj7zXXiXZMZuLMu5xypaFzSegsSfmVKKUxV-tcilELbV3u15XHHNcK0Z3s-BNOPVBzT-R14tEvsmsZnpHyF-3dK13extqNW5LXJNABoiQcudpiw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Accurate-Minkowski-sum-approximation-of-polyhedral-models.png" width="300"><td>

**Accurate Minkowski sum approximation of polyhedral models**

Varadhan, Gokul, Dinesh Manocha

01 Nov 2004, PG 2004

[[doi]](https://ieeexplore.ieee.org/abstract/document/1348370)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Offset-Triangular-Mesh-Using-the-Multiple-Normal-Vectors-of-a-Vertex.png" width="300"><td>

**Offset Triangular Mesh Using the Multiple Normal Vectors of a Vertex**

Su-Jin Kim, Dong-Yoon Lee, Min-Yang Yang

2004, CADA

[[doi]](https://www.tandfonline.com/doi/abs/10.1080/16864360.2004.10738269)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Self-intersection-Removal-in-Triangular-Mesh-Offsetting.png" width="300"><td>

**Self-intersection Removal in Triangular Mesh Offsetting**

Wonhyung Jung, Hayong Shin, Byoung K. Choi

2004, CADA

[[doi]](https://www.tandfonline.com/doi/abs/10.1080/16864360.2004.10738290)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/A-new-curve-based-approach-to-polyhedral-machining.png" width="300"><td>

**A new curve-based approach to polyhedral machining**

Cha-Soo Jun, Dong-Soo Kim, Sehyung Park

15 Apr 2002, CAD

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448501001105)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/A-computing-strategy-for-applications-involving-offsets,-sweeps,-and-Minkowski-operations.png" width="300"><td>

**A computing strategy for applications involving offsets, sweeps, and Minkowski operations**

E.E. Hartquist, J.P. Menon, K. Suresh, H.B. Voelcker, J. Zagajac

Mar 1999, CAD

[[doi]](https://www.sciencedirect.com/science/article/pii/S0010448599000147)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Generating-Shaded-Offset-Surfaces-with-Distance,-Closest-Point-and-Color-Volumes.png" width="300"><td>

**Generating Shaded Offset Surfaces with Distance, Closest-Point and Color Volumes**

Breen, David E., Sean Mauch

1999, Proceedings of the international workshop on volume graphics

[[doi]](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=0bf85b578dffca47888bfc1d0be03a48e6d9ce92)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Offsetting-operations-on-non-manifold-boundary-representation-models-with-simple-geometry.png" width="300"><td>

**Offsetting operations on non-manifold boundary representation models with simple geometry**

Sang Hun Lee

1999, Solid Modeling and Applications

[[doi]](https://dl.acm.org/doi/10.1145/304012.304017)
<!-- ---------------------------------------------------------------------- -->
<tr><td><img title="image" src=".pic/Intersection-of-offsets-of-parametric-surfaces.png" width="300"><td>

**Intersection of offsets of parametric surfaces**

Yu Wang

Jul 1996, CAGD

[[doi]](https://www.sciencedirect.com/science/article/pii/0167839695000399)
<!-- ---------------------------------------------------------------------- -->
</table> 

# :hammer: Projects
- **LDNI-based-Solid-Modeling**: [[project]](https://ldnibasedsolidmodeling.sourceforge.net/) [[code]](https://github.com/DebbieLeung/LDNI-based-Solid-Modeling):white_check_mark: [[video]](https://www.youtube.com/watch?v=G75mS1VGqx0&t=2s)

# :floppy_disk: Softwares
- [Rhino 8](https://www.rhino3d.com/cn/) [[offset operation doc]](https://docs.mcneel.com/rhino/8/help/en-us/commands/offsetmesh.htm)
  - The `OffsetMesh` operation in Rhino 8 is accomplished by directly moving the vertices, while the `OffsetSrf` operation on a B-rep input produces results that are more akin to the widely recognized offset results.
- [CATIA](https://www.3ds.com/zh-hans/products/catia)
- [NX](https://plm.sw.siemens.com/zh-CN/nx/?srsltid=AfmBOoqVvD7xm--0SrXLfoSCzDYG5D8kePOvU2nJxRQD64bCXcqZ5d3e)
  - It may be one of the better industrial software for performing offset mesh operations, but in many cases it is unable to complete the operation, possibly due to the generation of self-intersections.
- [Solidworks](https://www.solidworks.com/)
- [ZW3D](https://www.zwsoft.com/product/zw3d)
  - It seems to utilize a method involving the use of voxels for isosurface extraction.
- [CAXA](https://www.caxa.com/)

[Changhe Tu]: https://irc.cs.sdu.edu.cn/~chtu/index.html
[Charlie C.L. Wang]: https://mewangcl.github.io/
[Daniele Panozzo]: https://cims.nyu.edu/gcl/daniele.html
[Daniel Zint]: https://daniel-zint.github.io/
[David Cohen-Steiner]: https://www-sop.inria.fr/members/David.Cohen-Steiner/
[Denis Zorin]: https://cims.nyu.edu/gcl/denis.html
[Dongming Yan]: https://people.ucas.ac.cn/~dmyan
[Hongbo Fu]: https://facultyprofiles.hkust.edu.hk/profiles.php?profile=hongbo-fu-hongbofu
[Jin Huang]: http://www.cad.zju.edu.cn/home/hj/index.xml
[Jyh-Ming Lien]: https://cs.gmu.edu/~jmlien/doku.php
[Lei Wang]: https://alan-leo-wong.github.io/
[Pengfei Wang]: https://pengfei.me/
[Pierre Alliez]: https://team.inria.fr/titane/pierre-alliez/
[Shengjun Liu]: https://faculty.csu.edu.cn/liushengjun/en/lwcg/2772/list/index.htm
[Shuangmin Chen]: https://xk.qust.edu.cn/info/1041/4695.htm
[Shiqing Xin]: https://irc.cs.sdu.edu.cn/~shiqing/index.html
[Wenping Wang]: https://engineering.tamu.edu/cse/profiles/Wang-Wenping.html
[Xifeng Gao]: https://gaoxifeng.github.io/
[Zihan Zhao]: https://zih-an.github.io