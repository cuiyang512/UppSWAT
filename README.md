<div align="center">
  <img src="./logo.png" alt="UppSWAT Logo" width="250">
</div>

## UppSWAT: An Interactive Deep-Learning Software for Surface-Wave Processing and Tomography
<div align="center">
  <a href="https://github.com/cuiyang512" target="_blank">Yang Cui<sup>1</sup></a> &emsp; 
  <a href="https://www.jsg.utexas.edu/researcher/yangkang_chen/" target="_blank">Yangkang Chen<sup>2</sup></a> &emsp;
  <a href="https://www.uu.se/en/contact-and-organisation/staff?query=N19-37" target="_blank">Christian Schiffer<sup>1</sup></a> &emsp;
  <a href="https://www.uu.se/en/contact-and-organisation/staff?query=N18-827" target="_blank">Ayse Kaslilar<sup>1</sup></a> &emsp;
  <a href="https://www.uu.se/en/contact-and-organisation/staff?query=N21-2074" target="_blank">Myrto Papadopoulou<sup>1</sup></a>
</div>
<div align="center">
  <sup>1</sup>Department of Earth Sciences, Uppsala University<br>
  <sup>2</sup>Bureau of Economic Geology, The University of Texas at Austin<br>
</div>

<div align="center">
  <img src="https://img.shields.io/github/stars/cuiyang512/SW-Mode-Sep" alt="GitHub Stars" />
  <img src="https://img.shields.io/github/forks/cuiyang512/SW-Mode-Sep" alt="GitHub Forks" />
  <img src="https://img.shields.io/github/last-commit/cuiyang512/SW-Mode-Sep" alt="Last Commit" />
  <img src="https://img.shields.io/badge/language-Jupyter%20Notebook-%233572A5" alt="Language" />
</div>



## Overview
UppSWAT is an interactive, deep-learning-based software framework for surface-wave mode separation, processing, and inversion. The mode-separation module is built on an unsupervised deep-learning framework and can process an individual shot gather within a few minutes on a CPU. After separating different surface-wave modes in the space–time domain, UppSWAT further integrates multimodal surface-wave inversion to provide an end-to-end workflow from data processing to subsurface imaging. Our results demonstrate that the separated modal components can improve the quality and reliability of subsurface imaging.

Numerous deep-learning methods have been developed for a wide range of seismic processing and interpretation tasks. However, their practical adoption in both academia and industry remains limited, primarily because of insufficient generalizability and the lack of user-friendly tools. To address these challenges, we propose UppSWAT, an interactive and user-friendly software framework for surface-wave processing and inversion. UppSWAT improves generalizability by incorporating user-provided dispersion information into the deep-learning workflow through interactive guidance, allowing the model to adapt to different datasets without requiring predefined labels. Computational efficiency is further improved through a lightweight U-Net architecture, which provides a robust and computationally efficient backbone for the proposed unsupervised learning framework. Together, these features make UppSWAT a practical bridge between deep-learning research and real-world surface-wave processing applications.



## ModeSep Results

<div align="center">
  <img src="./fig/example1.png" alt="ModeSep Alum Shale" width="800">
</div>

<div align="center">
  <img src="./fig/example2.png" alt="ModeSep P1" width="800">
</div>
