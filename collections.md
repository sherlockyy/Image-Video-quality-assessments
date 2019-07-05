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
	- [LIVE Image Quality Assessment Database](#liveimage), [CID2013](#cid2013)
- [Video database](#viddatabase)
	- [LIVE Video Quality Database](#livevideo), [LIVE Mobile Video Quality Database](#livemobilev), [LIVE-Qualcomm Mobile In-Capture Video Quality Database](#livequalcomm), [CVD2014](#cvd2014), [KoNViD-1k](#konvid), [YouTube UGC Dataset](#youtubeugc)

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
### Blind prediction of natural video quality (BLIINDS)
M. Saad and A.C. Bovik, *[“ Blind prediction of natural video quality ”](https://ieeexplore.ieee.org/abstract/document/6705673)* 
IEEE Transactions on Image Processing, December 2013.  
[*[code](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)*]

<a name="imagedatabase"></a>
## Image database

<a name="liveimage"></a>
### LIVE Image Quality Assessment Database (LIVE)
H.R. Sheikh, Z.Wang, L. Cormack and A.C. Bovik, "LIVE Image Quality Assessment Database Release 2", http://live.ece.utexas.edu/research/quality.  
H.R. Sheikh, M.F. Sabir and A.C. Bovik, *["A statistical evaluation of recent full reference image quality assessment algorithms"](https://ieeexplore.ieee.org/abstract/document/1709988)*, IEEE Transactions on Image Processing, vol. 15, no. 11, pp. 3440-3451, Nov. 2006.  
Z. Wang, A.C. Bovik, H.R. Sheikh and E.P. Simoncelli, *["Image quality assessment: from error visibility to structural similarity,"](https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf)* IEEE Transactions on Image Processing , vol.13, no.4, pp. 600- 612, April 2004.  
[*[project](http://live.ece.utexas.edu/research/Quality/subjective.htm)*]

<a name="cid2013"></a>
### CID2013
Virtanen, Toni, et al. *["CID2013: A database for evaluating no-reference image quality assessment algorithms."](https://ieeexplore.ieee.org/abstract/document/6975172)* IEEE Transactions on Image Processing 24.1 (2014): 390-402.
[*[project](http://www.helsinki.fi/psychology/groups/visualcognition/)*]

<a name="videodatabase"></a>
## Video database

<a name="livevideo"></a>
### LIVE Video Quality Database (LIVE)
K. Seshadrinathan, R. Soundararajan, A. C. Bovik and L. K. Cormack, *["Study of Subjective and Objective Quality Assessment of Video",](https://ieeexplore.ieee.org/abstract/document/5404314)* IEEE Transactions on Image Processing , vol.19, no.6, pp.1427-1441, June 2010.  
K. Seshadrinathan, R. Soundararajan, A. C. Bovik and L. K. Cormack, *["A Subjective Study to Evaluate Video Quality Assessment Algorithms",](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/7527/75270H/A-subjective-study-to-evaluate-video-quality-assessment-algorithms/10.1117/12.845382.short)* SPIE Proceedings Human Vision and Electronic Imaging , Jan. 2010.  
[*[project](http://live.ece.utexas.edu/research/Quality/live_video.html)*]

<a name="livemobilev"></a>
### LIVE Video Quality Database (LIVE-Mobile)
A. K. Moorthy, L. K. Choi, A. C. Bovik and G. deVeciana, *[“Video Quality Assessment on Mobile Devices: Subjective, Behavioral and Objective Studies”,](https://ieeexplore.ieee.org/abstract/document/6263265)* IEEE Journal of Selected Topics in Signal Processing, to appear in October 2012.  
A. K. Moorthy, L. K. Choi, G. deVeciana, and A. C. Bovik, “Mobile Video Quality Assessment Database,” IEEE ICC Workshop on Realizing Advanced Video Optimized Wireless Networks, Ottawa, Canada, June 10-15, 2012.  
A. K. Moorthy, L. K. Choi, G. deVeciana, and A. C. Bovik, *[“Subjective Analysis of Video Quality on Mobile Devices,”](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.298.9721&rep=rep1&type=pdf)* Sixth International Workshop on Video Processing and Quality Metrics for Consumer Electronics (VPQM) (invited article), Scottsdale, Arizona, January 15-16, 2012.  
[*[project](http://live.ece.utexas.edu/research/Quality/live_mobile_video.html)*]

<a name="livequalcomm"></a>
### LIVE-Qualcomm Mobile In-Capture Video Quality Database (LIVE-Qualcomm)
D. Ghadiyaram, J. Pan, A. C. Bovik, A. K. Moorthy, P. Panda, and K. C. Yang, *["In-capture Mobile Video Distortions: A Study of Subjective Behavior and Objective Algorithms,"](https://ieeexplore.ieee.org/abstract/document/7932975)* IEEE Trans. Circ. and Syst. for Video Tech.  
D. Ghadiyaram, J. Pan, A. C. Bovik, A. K. Moorthy, P. Panda, and K. C. Yang, "LIVE-Qualcomm Mobile In-Capture Video Quality Database," Online: http://live.ece.utexas.edu/research/incaptureDatabase/index.html, 2017.  
[*[project](http://live.ece.utexas.edu/research/incaptureDatabase/index.html)*]

<a name="cvd2014"></a>
### CVD2014
Nuutinen, Mikko, et al. *["CVD2014—A database for evaluating no-reference video quality assessment algorithms."](https://ieeexplore.ieee.org/abstract/document/7464299)* IEEE Transactions on Image Processing 25.7 (2016): 3073-3086.  
[*[project](http://www.helsinki.fi/psychology/groups/visualcognition/)*]

<a name="konvid"></a>
### KoNViD-1k
Hosu, Vlad, et al. *["The Konstanz natural video database (KoNViD-1k)."](https://ieeexplore.ieee.org/abstract/document/7965673)* 2017 Ninth international conference on quality of multimedia experience (QoMEX). IEEE, 2017.  
[*[project](http://database.mmsp-kn.de/konvid-1k-database.html)*]

<a name="youtubeugc"></a>
### YouTube UGC Dataset
Wang, Yilin, Sasi Inguva, and Balu Adsumilli. *["YouTube UGC Dataset for Video Compression Research."](https://arxiv.org/pdf/1904.06457.pdf)* arXiv preprint arXiv:1904.06457 (2019).  
[*[project](https://media.withyoutube.com/)*]
