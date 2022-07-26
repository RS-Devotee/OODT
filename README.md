# OODT：Oriented Object Detection and Tracking in SVD
This is the official website of the **OODT** dataset.

## Data download link
Baidu netdisk：https://pan.baidu.com/s/1IsBQlVc4PD4DTFqe3L0hLg (Extraction Code:OODT)  
Google drive：https://drive.google.com/file/d/1TK7-D-LhZcL2jgowuSqe_Q0TaxsNh7mk/view?usp=sharing

## 1.Data Introduction
OODT is the first dataset of oriented objects for object detection and tracking in satellite vedio datasets (SVDs), in which  each object is **labeled as a rectangular box with rotating orientation**. It consists of the single-object and multi-object tracking datasets.
<br />The single-object tracking (SOT) dataset consists of 74 sequences, including 30 cars, 17 planes, 17 ships and 10 trains with 22610 frames in total. 
<div align=center>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/sheet1.png">
</div>

The multi-object tracking (MOT) datasets is tentatively labeled with 8628 vehicles in 41 frames of five SVDs .
<div align=center>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/sheet2.png">
</div>

## 2.Data Visualization
### (1)SOT
<div align=center>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/single1.gif" style="height:170px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/single2.gif" style="height:170px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/single3.gif" style="height:170px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/single4.gif" style="height:170px"/>
</div>

### (2)MOT
<div align=center>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi1.png" style="height:160px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi2.png" style="height:160px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi3.png" style="height:160px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi4.png" style="height:160px"/>
</div>
<div align=center>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi5.png" style="height:155px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi6.png" style="height:155px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi7.png" style="height:155px"/>
<img src="https://github.com/RS-Devotee/OODT/blob/main/Figure/multi8.png" style="height:155px"/>
</div>

## 3.Data source
### (1)SOT
The raw satellite video data is collected from various sources, such as the JiLin-1 satellite constellation [<sup>[1]</sup>](#R1), SkySat satellite constellation[<sup>[2]</sup>](#R2), object tracking contests [<sup>[3]</sup>](#R3)[<sup>[4]</sup>](#R4)[<sup>[5]</sup>](#R5), and some other publicly available videos [<sup>[6]</sup>](#R6)[<sup>[7]</sup>](#R7).
### (2)MOT
SVD1 and SVD2 are collected from JiLin-1 satellite constellation [<sup>[8]</sup>](#R8). SVD3 is collected from IRIS camera on the International Space Station[<sup>[3]</sup>](#R3) .SVD4 and SVD5 are collected from SkySat satellite constellation[<sup>[9]<sup>](#R9)[<sup>[10]<sup>](#R10).
### (3)Source
<div><a name="R1"></a>  
[1] https://mall.charmingglobe.com/Sampledata.
</div>
<div><a name="R2"></a>  
[2] https://www.satimagingcorp.com/satellite-sensors/skysat-1/.
</div>
<div><a name="R3"></a>  
[3] https://www.grss-ieee.org/resources/tutorials/data-fusion-tutorial-in-spanish/ .
</div>
<div><a name="R4"></a>  
[4] https://satvideodt.github.io.
</div>
<div><a name="R5"></a>  
[5] http://gaofen-challenge.com/.
</div>
<div><a name="R6"></a>  
[6] Yin, Q.; Liu, T.; Lin, Z.P.; An, W.; Guo, Y.L. Moving Object Detection in Satellite Videos via Spatial-Temporal Tensor Model and Weighted Schatten p-Norm Minimization. IEEE Geosci. Remote Sens. Lett. 2022, 19, doi: Artn 802240510.1109/Lgrs.2021.3117054.
</div>
<div><a name="R7"></a>  
[7] Zhao, M.Q.; Li, S.Y.; Xuan, S.Y.; Kou, L.X.; Gong, S.; Zhou, Z. SatSOT: A Benchmark Dataset for Satellite Video Single Object Tracking. IEEE Trans. Geosci. Remote Sens. 2022, 60, doi:10.1109/tgrs.2022.3140809.
</div>
<div><a name="R8"></a>  
[8]http://www.grss-ieee.org/community/technical-committees/data-fusion/2016-ieee-grss-data-fusion-contest-results/
</div>
<div><a name="R9"></a>  
[9]https://www.youtube.com/watch?v=aW1-ZWencvA
</div>
<div><a name="R10"></a>  
[10]https://www.youtube.com/watch?v=lKNAY5ELUZY
</div>
  
### Contact
If you have any questions, please contact oodt_server@163.com.
