# A Survey on Work Related to Offset Mesh Generation

Here is a list of related work on offset mesh generation that I have collected and complied.
I will update this list on a regular basis.

I add :star: emojis after each project item **based on my own assessment** of their importance.
The more :star: a project item has, the more important it is **from my perspective**.

:clap: If you have any suggestions for improvements, please raise an issue or contact me.

# 2024
- Hongyi Cao, Gang Xu, Renshu Gu, Jinlan Xu, Xiaoyu Zhang, Timon Rabczuk, Yuzhe Luo, Xifeng Gao. *"Robust and Feature-Preserving Offset Meshing"*. (arXiv 2024) [[Paper](https://arxiv.org/abs/2412.15564)] :star:
  - This paper appears to be an updated version of the previous work, *"A Parallel Feature-preserving Mesh Variable Offsetting Method with Dynamic Programming"* (see below), and the offset operation being performed is a variant of the conventional offset, referred to as *mitered offset*.
- **PCO**: [Lei Wang](https://alan-leo-wong.github.io/), Xudong Wang, Pengfei Wang, Shuangmin Chen, Shiqing Xin, Jiong Guo, Wenping Wang, Changhe Tu. *"PCO: Precision-Controllable Offset Surfaces with Sharp Features"*. (SIGGRAPH Asia 2024, TOG 2024) [[Paper](https://dl.acm.org/doi/10.1145/3687920)] [[Project Page]](https://alan-leo-wong.github.io/SIGASIA24-PCO-ProjectPage/) [Code (coming soon)] :star::star::star:

# 2023
- **FPO**: Daniel Zint, Nissim Maruani, M Rouxel-Labb, Pierre Alliez. *"Feature-Preserving Offset Mesh Generation from Topology-Adapted Octrees"*. (ESGP 2023, CGF 2023) [[Paper](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14906)] [[Code](https://github.com/daniel-zint/offsets-and-remeshing)] :star::star:
- Hongyi Cao, Gang Xu, Renshu Gu, Jinlan Xu, Xiaoyu Zhang, Timon Rabczuk. *"A Parallel Feature-preserving Mesh Variable Offsetting Method with Dynamic Programming"* (arXiv 2023) [[Paper](https://arxiv.org/abs/2310.08997)] [[Code](https://github.com/iGame-Lab/PFPOffset?tab=readme-ov-file)] :star:
  - This paper appears to have uploaded an updated version *"Robust and Feature-Preserving Offset Meshing"* (see above), and the offset operation being performed is variant of the conventional offset, refered to as *variable offset* (allows for each facet to have a different offset distance).

# 2022
- **AlphaWrap**: Cédric Portaneri, Mael Rouxel-Labbé, Michael Hemmer, David Cohen-Steiner, Pierre Alliez. *"Alpha wrapping with an offset"*. (TOG 2022) [[Paper](https://dl.acm.org/doi/abs/10.1145/3528223.3530152)] [[Code (available in CGAL)](https://github.com/CGAL/cgal/)] [[Documentation](https://doc.cgal.org/latest/Alpha_wrap_3/index.html#Chapter_3D_Alpha_wrapping)] :star:

# 2018