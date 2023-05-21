Tips: You can get a better experience of this site in [Google chrome](https://www.google.com/chrome) browser.

# Overview
## Welcome to our Project: GuLiM motion transfer
<p align='center'>
<img src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/images/teleop-dualarm.gif" width="400" height="240" alt="demo of dualarm teleop"/>
<img src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/images/teleop-grasp.gif" width="400" height="240" alt="demo of dualarm grasp"/>
</p>

#### Citation:
This work has been published in [IEEE Transactions on Medical Robotics and Bionics](https://ieeexplore.ieee.org/document/9693932).
```
@ARTICLE{9693932,  
        author={Lv, Honghao and Kong, Depeng and Pang, Gaoyang and Wang, Baicun and Yu, Zhangwei and Pang, Zhibo and Yang, Geng},  
        journal={IEEE Transactions on Medical Robotics and Bionics},   
        title={GuLiM: A Hybrid Motion Mapping Technique for Teleoperation of Medical Assistive Robot in Combating the COVID-19 Pandemic},   
        year={2022},  
        volume={4},  
        number={1},  
        pages={106-117},  
        doi={10.1109/TMRB.2022.3146621}
}
```

#### Abstract:
We present an intuitive teleoperation approach for human-robot motion transfer. Hybrid mapping of hand gesture and limb motion method (GuLiM) with incremental pose mapping strategy is introduced to flexibly map the workspace between human and robot. This GuLiM method cost-effectively enables a non-expert to transfer a rough manipulation skill to an assistive robot for challenging tasks.

<p align='center'>
<img src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/images/process.jpg" width="1000" height="600" alt="GuLiM process"/>
</p>

#### Contact: 
[Honghao Lv](http://fsie-zju.com/team/) (lvhonghao [at] zju.edu.cn)

# Setup
<p align='center'>
<img src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/images/setup.png" width="800" height="600" alt="setup of the grasp task"/>
</p>

# Task1:
### Grab a block and place it in the specific region.

## From region A to region B.

<table align='center'>
<tr>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/ABP1T1_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/AB-R-P1 (2)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> DMM </td>
<td align='center'> GuLiM </td>
</tr>
</table>

## From region A to region C.

<table align='center'>
<tr>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/AC-P1 (2)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/AC-R-P1 (1)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> DMM </td>
<td align='center'> GuLiM </td>
</tr>
</table>

## From region A to region D.

<table>
<tr>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/ADP1T2_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/ADRP1T4_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> DMM </td>
<td align='center'> GuLiM </td>
</tr>
</table>

# Task2:
### Grab a block and place it at the specific angle.

## Place at 30 degrees.

<table>
<tr>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/degree30-P1 (2)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/degree30-R-P1 (2)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> DMM </td>
<td align='center'> GuLiM </td>
</tr>
</table>

## Place at 60 degrees.

<table>
<tr>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/degree60-P1 (2)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/degree60-R-P1 (3)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> DMM </td>
<td align='center'> GuLiM </td>
</tr>
</table>

## Place at 90 degrees.

<table>
<tr>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/degree90-P1 (5)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/GuLiM-motion-transfer/assets/media/zip/degree90-R-P1-batch (3)_batch.mp4" type="video/mp4" controls="controls" width="500" height="282"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> DMM </td>
<td align='center'> GuLiM </td>
</tr>
</table>


<!-- ### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/). -->
