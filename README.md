# RGB-D Human Matting Project
## HDM-2K Dataset
### Introduction
<p align="justify">In order to promote the RGB-D human matting research, the first RGB-D human matting dataset, HDM-2K, is established in our paper (RGB-D Human Matting). The HDM-2K dataset is comprised of <strong>2,270 real-world human images</strong> from various scenes, <strong>helpful depth maps</strong>, and manually annotated alpha mattes. The RGB-D images in HDM-2K are grouped into 27 scene subsets according to salient background objects and colors,including green plant, poster, bookcase, brown wall, etc. Meanwhile, the images are captured under different lighting conditions, which include strong light, normal light, and low light. Some examples are shown as below, more can be viewed in the dataset link.
 
<div align=center><img width="780" height="800" src="[https://img-blog.csdn.net/20161028230559575](https://github.com/rgbd-zml/RGB-D-human-matting/blob/main/demo/dataset/fig2.jpg)"/></div>

 ### Benchmark Tracks
 <p align="justify">Based on HDM-2K, two benchmark tracks, HDM-2K-CTrack and HDM-2K-FTrack, are set up and equipped with two dataset partitions. Fig. 4 shows the scene and lighting conditions in the HDM-2K-CTrack and HDM-2K-FTrack, respectively. Similar to the most common matting datasets, the dataset partition for <strong>HDM-2K-CTrack</strong> is set without overlap between both the foreground human and background scene in the training and the test sets. As a result, the training set contains 1,897 RGB-D images and the test set contains the remaining 373 RGB-D images for HDM-2K-CTrack. As shown in the figure below, there are 20 scenes in the training set and 7 scenes in the test set. Meanwhile, the lighting conditions of strong light, normal light and low light are covered in both the training set and test set. 
  
  ![](https://github.com/rgbd-zml/RGB-D-human-matting/blob/main/demo/dataset/HDM2KCTrack.jpg)
  
<p align="justify">Additionally, considering that the matting applications with fixed scenes (e.g., video conference rooms, surveillance rooms, etc) have gradually increased in recent years, HDM-2K-FTrack is set up to research fixed-scenes matting. For <strong>HDM-2K-FTrack</strong>, background-shared training and test sets are provided with 1,947 RGB-D images and 323 RGB-D images, respectively. In the HDM-2K-FTrack，the training set contains all 27 scenes and the test set contains 12 scenes that overlap with the training set. Similarly, both the training set and test set cover three lighting conditions. By providing two benchmark tracks and dataset partition of RGB-D human matting based on HDM-2K, it is hoped that the constructed HDM-2K can desirably promote the development of matting algorithms in academic research and practical applications.
 
![](https://github.com/rgbd-zml/RGB-D-human-matting/blob/main/demo/dataset/HDM2KFTrack.jpg)
  
###  Download
The datasets <a href="#am-2k"><strong>HDM-2K</strong></a> can now be openly accessed from the links below (both at Google Drive and at Baidu Wangpan) ! Please follow the dataset release agreements to access. 
> | Dataset | <p>Dataset Link<br>(Google Drive)</p> | <p>Dataset Link<br>(Baidu Wangpan 百度网盘)</p> | Dataset Release Agreement|
> | :----:| :----: | :----: | :----: | 
> |<strong>HDM-2k</strong>|[Link](https://drive.google.com/drive/folders/1SReB9Zma0TDfDhow7P5kiZNMwY9j9xMA?usp=sharing)|[Link](https://pan.baidu.com/s/1M1uF227-ZrYe3MBafqyTdw) (pw:29r1)|[Agreement (MIT License)](https://jizhizili.github.io/files/gfm_datasets_agreements/AM-2k_Dataset_Release_Agreement.pdf)| 
> 


