# Databases and algorithms for image/video quality assessment

## Table of Contents:
- [Image reference-based algorithm](#image-reference)
	- [SSIM](#ssim), [MS-SSIM](#ms-ssim), [VIF](#vif)
- [Image no-reference algorithm](#image-noreference)
	- [NIQE](#niqe), [BRISQUE](#brisque)
- [Video reference-based algorithm](#video-reference)
	- [SpEED-QA](#speedqa), [ViS3](#vis3), [MoViE](#movie), [VMAF](#vmaf)
- [Video no-reference algorithm](#video-noreference)
	- [VIIDEO](#viideo), [V-BLINDS](#vblinds)
- [Image database](#imgdatabase)
- [Video database](#viddatabase)
	- [LIVE Video Quality Database](#livevideo), [LIVE Mobile Video Quality Database](#livemobilev), [LIVE-Qualcomm Mobile In-Capture Video Quality Database 
](#livequalcomm), [CVD2014](#cvd2014), [KoNViD-1k](#konvid), [YouTube UGC Dataset](#youtubeugc)

___
<br>

<a name="image-reference"></a>
## Image reference-based algorithm

<a name="ssim"></a>
### Structural Similarity Index (SSIM)
Z. Wang, A.C. Bovik, H.R. Sheikh and E.P. Simoncelli, *["Image quality assessment: from error visibility to structural similarity,"](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf)* 
IEEE Transactions on Image Processing , vol.13, no.4pp. 600- 612, April 2004.  
[*[code](https://ece.uwaterloo.ca/~z70wang/research/ssim/index.html)*]

<a name="ms-ssim"></a>
### Multi-Scale Structural Similarity Index (MS-SSIM)
Z. Wang, E. P. Simoncelli and A. C. Bovik, *["Multi-scale structural similarity for image quality assessment,"](https://ieeexplore.ieee.org/abstract/document/1292216)* 
IEEE Asilomar Conference Signals, Systems and Computers , Nov. 2003.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="vif"></a>
### Visual Information Fidelity (VIF)
H.R. Sheikh.and A.C. Bovik, *["Image information and visual quality,"](https://ieeexplore.ieee.org/abstract/document/1326643)* 
IEEE Transactions on Image Processing , vol.15, no.2,pp. 430- 444, Feb. 2006.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="image-noreference"></a>
## Image no-reference algorithm

<a name="niqe"></a>
### Naturalness Image Quality Evaluator (NIQE)
A. Mittal, R. Soundararajan and A. C. Bovik, *[“Making a Completely Blind Image Quality Analyzer, ”](https://ieeexplore.ieee.org/document/6353522)* 
IEEE Signal Processing Letters , pp. 209-212, vol. 22, no. 3, March 2013.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="brisque"></a>
### Blind/Referenceless Image Spatial QUality Evaluator (BRISQUE) 
A. Mittal, A. K. Moorthy and A. C. Bovik, *[“No-Reference Image Quality Assessment in the Spatial Domain,”](https://ieeexplore.ieee.org/abstract/document/6272356)* 
IEEE Transactions on Image Processing , 2012 (to appear).  
A. Mittal, A. K. Moorthy and A. C. Bovik, “Referenceless Image Spatial Quality Evaluation Engine,” 
45th Asilomar Conference on Signals, Systems and Computers , November 2011.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="video-reference"></a>
## Video reference-based algorithm

<a name="speedqa"></a>
### SpEED-QA: Spatial Efficient Entropic Differencing for Image and Video Quality
C. G. Bampis, P. Gupta, R. Soundararajan and A. C. Bovik, *["SpEED-QA: Spatial Efficient Entropic Differencing for Image and Video Quality,"](https://ieeexplore.ieee.org/abstract/document/7979533) 
in IEEE Signal Processing Letters, vol. 24, no. 9, pp. 1333-1337, Sept. 2017.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]
[*[project](https://github.com/christosbampis/SpEED-QA_release)]

<a name="vis3"></a>
### ViS3: An Algorithm for Video Quality Assessment via Analysis of Spatial and Spatiotemporal Slices
Vu, Phong V., and Damon M. Chandler. *["ViS3: an algorithm for video quality assessment via analysis of spatial and spatiotemporal slices."](https://www.spiedigitallibrary.org/journals/Journal-of-Electronic-Imaging/volume-23/issue-1/013016/ViS3--an-algorithm-for-video-quality-assessment-via-analysis/10.1117/1.JEI.23.1.013016.short)* 
Journal of Electronic Imaging 23.1 (2014): 013016.
[*[project](http://vision.eng.shizuoka.ac.jp/vis3/)*]

<a name="movie"></a>
### MOtion-based Video Integrity Evaluation (MOVIE) index for video quality assessment
Kalpana Seshadrinathan and A.C. Bovik, *["Motion Tuned Spatio-temporal Quality Assessment of Natural Videos,"](https://ieeexplore.ieee.org/abstract/document/5290142)* vol. 19, no. 2, pp. 335-350, 
IEEE Transactions on Image Processing , Feb. 2010.
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="vmaf"></a>
### Perceptual video quality assessment based on multi-method fusion (VMAF)
[*[project](https://github.com/Netflix/vmaf)*]

<a name="video-noreference"></a>
## Video no-reference algorithm

<a name="viideo"></a>
### A Completely Blind Video Integrity Oracle (VIIDEO)
A. Mittal, M. A. Saad, and A. C. Bovik, *["A Completely Blind Video Integrity Oracle,"](https://ieeexplore.ieee.org/abstract/document/7332944/)* 
IEEE Transactions on Image Processing , vol. 25, no. 1, pp. 289-300, January, 2016.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="vblinds"></a>
### Blind prediction of natural video quality (BLINDS)
M. Saad and A.C. Bovik, *[“ Blind prediction of natural video quality ”](https://ieeexplore.ieee.org/abstract/document/6705673)* 
IEEE Transactions on Image Processing, December 2013  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="imagedatabase"></a>
## Image database

<a name="videodatabase"></a>
## Video database
