# Damage_Detection_in_Composites_Using_Transfer_Learning
This is the code Repository for paper titled - "Matrix cracking and delamination detection in GFRP laminates using pre-trained CNN models", which is published in the Journal of the Brazilian Society of Mechanical Sciences and Engineering, Springer

Link to the paper can be found here - [Link](https://link.springer.com/article/10.1007/s40430-023-04060-w), in addition to the pdf uploaded in this repository.

All code files are present in the "Code" folder. 

# Abstract
The demand for fiber-reinforced polymer composites is increasing steadily because of their superior mechanical properties, high specific strength and stiffness, and high corrosion resistance. Matrix cracking and delamination are one of the most significant kind of damage in laminated composite structures. In this research work, our main objective is to differentiate whether the randomly oriented chopped glass fiber composite laminate is undamaged or damaged (matrix cracking and delamination) using five distinct convolutional neural network (CNN) models with transfer learning techniques. A microscopic examination is conducted on a composite laminate in the thickness direction just before and after the three-point bending test at 100 μm. Thereafter, data augmentation techniques such as mirroring, rotation, affine transformation, and noise addition are used to augment the dataset. The augmented dataset is given as input to five different deep CNN models, including VGG-16, ResNet-101, NasNetMobile, MobileNet-V2, and DenseNet-201. Using augmented image datasets, the pre-trained CNN models with transfer learning are trained, validated, and tested in the proportion of 70:15:15. Thereafter, comparative studies are carried out to analyze the total trainable and non-trainable parameters, computation time, training, validation, testing accuracy, and F1 score of different CNN models. VGG-16 has 138 million trainable parameters and thus requires maximum computation time. However, MobileNet-V2 has 3 million trainable parameters that needs minimum computation time. DenseNet-201, VGG-16, MobileNet-V2, and NasNetMobile converge very fast and produce minimum validation loss and maximum accuracy whereas ResNet-101 seems not to be converged easily which leads to maximum validation loss and minimum accuracy. The highest training, validation, testing, and F1 score were observed for VGG-16, NasNetMobile, MobileNet-V2, and DenseNet-201 and the lowest for the ResNet-101 CNN model. Finally, it can be concluded that the MobileNet-V2 model performed better than the other four CNN models in terms of accuracy with respect to total parameters and computation time over the other models.

# Gallery

![GFRP](https://github.com/rohit-ash/Damage_Detection_in_Composites_Using_Transfer_Learning/assets/51155103/1bdc98fd-be69-4faf-b40e-c7c1a1d620da)

# Citation
Please cite our paper if you find this work useful for your research:

```
@article{chaupal2023matrix,
  title={Matrix cracking and delamination detection in GFRP laminates using pre-trained CNN models},
  author={Chaupal, Pankaj and Rohit, S and Rajendran, Prakash},
  journal={Journal of the Brazilian Society of Mechanical Sciences and Engineering},
  volume={45},
  number={3},
  pages={136},
  year={2023},
  publisher={Springer}
}
```
