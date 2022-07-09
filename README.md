# awesome-tactile-sensing
>Collection of vision-based tactile sensing papers and blogposts

---------------------------------------

# 1 Survey papers

Overview of sensors in this table from the paper [A soft thumb-sized vision-based sensor with accurate all-round force perception](https://www.nature.com/articles/s42256-021-00439-3/tables/1):  
![Overview](assets/overview.png "Title")

# 2 Sensor design papers and related github repositories
## 2.1 Gelsight and its variants
**[0]** Yuan, W.; Dong, S.; Adelson, E.H. [GelSight: High-Resolution Robot Tactile Sensors for Estimating Geometry and Force](https://www.mdpi.com/1424-8220/17/12/2762#cite) :star::star::star::star::star:  

**[1]** Elliott Donlon, Siyuan Dong, Melody Liu, Jianhua Li, Edward Adelson, Alberto Rodriguez [GelSlim: A High-Resolution, Compact, Robust, and Calibrated Tactile-sensing Finger](https://arxiv.org/abs/1803.00628) :star::star::star::star::star:  
[GelSlim Webpage](http://www.mit.edu/~daolinma/research/tactile_sensing.html#:~:text=GelSlim%20is%20a%20tactile%20finger,elastoma%20is%20the%20sensing%20element.).   

**[2]** Daolin Ma, Elliott Donlon, Siyuan Dong, Alberto Rodriguez [Dense Tactile Force Distribution Estimation using GelSlim and inverse FEM](https://arxiv.org/abs/1810.04621) :star::star::star::star::star:  

**[3]** Ian Taylor, Siyuan Dong, Alberto Rodriguez [GelSlim3.0: High-Resolution Measurement of Shape, Force and Slip in a Compact Tactile-Sensing Finger](https://arxiv.org/abs/2103.12269) :star::star::star::star::star:  

**[4]** Shaoxiong Wang, Yu She, Branden Romero, Edward Adelson [GelSight Wedge: Measuring High-Resolution 3D Contact Geometry with a Compact Robot Finger](https://arxiv.org/abs/2106.08851) :star::star::star::star::star:
### Related Github repos```
- [Gelsight Marker Tracking](https://github.com/GelSight/tracking)
- [GelSlim Fabrication and Software](https://github.com/mcubelab/gelslim)
- [GelSlim heightmap reconstruction](https://github.com/siyuandong16/Heightmap_reconstruction_with_GelSlim)
- [Gelsight heightmap reconstruction](https://github.com/siyuandong16/gelsight_heightmap_reconstruction)
#### Unofficial:
- [Calibration of Osaka-produced GelSight](https://github.com/wrslab/gelsight)
- [Implementation of Gelsight Wedge](https://github.com/leo9344/Implementation-of-GelSight)
## 2.2 DIGIT
**[0]** Mike Lambeta, Po-Wei Chou, Stephen Tian, Brian Yang, Benjamin Maloon, Victoria Rose Most, Dave Stroud, Raymond Santos, Ahmad Byagowi, Gregg Kammerer, Dinesh Jayaraman, Roberto Calandra  
[DIGIT: A Novel Design for a Low-Cost Compact High-Resolution Tactile Sensor with Application to In-Hand Manipulation](https://arxiv.org/abs/2005.14679) :star::star::star::star::star:
### Related Github repos
-[digit-interface](https://github.com/facebookresearch/digit-interface)
-[PyTouch: a machine learning library for tactile touch sensing](https://github.com/facebookresearch/PyTouch)
#### Unofficial:
-[PatchGraph:In-hand tactile tracking with learned surface normals](https://github.com/psodhi/tactile-in-hand)
-[Touch Detection with Deep CNNs](https://github.com/Jcastanyo/Grip-detection)
-[gazebo-yarp-digit-plugin](https://github.com/hsp-iit/gazebo-yarp-digit-plugin)

## 2.3 FingerVision
**[0]** Akihiko Yamaguchi [FingerVision for Tactile Behaviors, Manipulation,and Haptic Feedback Teleoperation](http://akihikoy.net/info/wdocs/Yamaguchi,2018-FingerVision%20for%20Tactile%20Behaviors,%20Manipulation,%20and%20Haptic%20Feedback%20Teleoperation-SAMCON.pdf) :star::star::star::star::star:    

**[1]** Akihiko Yamaguchi, Christopher G. Atkeson [Tactile Behaviors with the Vision-Based Tactile Sensor FingerVision](https://par.nsf.gov/servlets/purl/10156255)  
[FingerVision webpage](http://akihikoy.net/notes/?project%2FFingerVision%2FConcept)

### Related Github repos

## 2.4 ETH Zurich tactile sensor
**[0]** Carmelo Sferrazza, Raffaello D'Andrea [Transfer learning for vision-based tactile sensing](https://arxiv.org/abs/1812.03163) :star::star::star::star::star:
### Related Github repos

## 2.5 GelTip
**[0]** Daniel Fernandes Gomes, Zhonglin Lin, Shan Luo [GelTip: A Finger-shaped Optical Tactile Sensor for Robotic Manipulation](https://arxiv.org/abs/2008.05404) :star::star::star::star::star:
### Related Github repos

## 2.6 DelTact
**[0]** Guanlan Zhang, Yipai Du, Hongyu Yu, Michael Yu Wang.  [DelTact: A Vision-based Tactile Sensor Using Dense Color Pattern](https://arxiv.org/abs/2202.02179) :star::star::star::star::star:
### Related Github repos

## 2.7 OmniTact
**[0]** Akhil Padmanabha, Frederik Ebert, Stephen Tian, Roberto Calandra, Chelsea Finn, Sergey Levine [OmniTact: A Multi-Directional High Resolution Touch Sensor](https://arxiv.org/abs/2003.06965) :star::star::star::star::star:
### Related Github repos
## 2.8 TacTip
**[0]** Nathan F. Lepora [Soft Biomimetic Optical Tactile Sensing with the TacTip: A Review](https://arxiv.org/abs/2105.14455)
### Related Github repos

## 2.9 Insight
**[0]** Huanbo Sun, Katherine J. Kuchenbecker, Georg Martius [A soft thumb-sized vision-based sensor with accurate all-round force perception](https://arxiv.org/abs/2111.05934) :star::star::star::star::star:

# 3 Tactile sensing tasks
## 3.1 Touch Detection
**[0]** Julio Castano-Amoros,Pablo Gil, Santiago Puente [Touch Detection with Low-cost Visual-based Sensor](https://rua.ua.es/dspace/bitstream/10045/119083/4/Castano-Amoros_etal_ROBOVIS-2021.pdf) :star::star::star::star::star:
## 3.2 Force Estimation
## 3.3 Pose Estimation
## 3.4 3D reconstruction
## 3.5 Slip detection
**[0]** Yazhan Zhang, Zicheng Kan,Yu Alexander Tse,Yang Yang, Michael Yu Wang   
[FingerVision Tactile Sensor Design and Slip Detection Using
Convolutional LSTM Network](https://arxiv.org/abs/1810.02653) :star::star::star::star::star:  

**[1]** Mike Lambeta, Huazhe Xu, Jingwei Xu, Po-Wei Chou, Shaoxiong Wang, Trevor Darrell, Roberto Calandra [PyTouch: A Machine Learning Library for Touch Processing](https://arxiv.org/abs/2105.12791). Check page 5 of the paper for more details. :star::star::star::star::star:
## 3.6 Localization and Mapping
**[0]** Rui Li, Robert Platt Jr., Wenzhen Yuan*, Andreas ten Pas*, Nathan Roscup*, Mandayam A. Srinivasan,
Edward Adelson [Localization and Manipulation of Small Parts Using GelSight Tactile
Sensing](http://persci.mit.edu/_media/pub_pdfs/rui-iros2014.pdf)
