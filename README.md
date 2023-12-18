# Prompt Learning for Light Field Semantic Segmentation in the Consumer-centric Internet of Intelligent Computing Things
# Method #
![image](https://github.com/jiachen0620/Prompt-Learning-for-Light-Field-Semantic-Segmentation/assets/23238674/991e20d3-a036-4c7d-b2f9-f3d3b090f4bf)
Authors: Chen Jia, Fan Shi, Member, IEEE, Xiufeng Liu, Xu Cheng, Member, IEEE, Zixuan Zhang, Meng Zhao, Member, IEEE, and Shengyong Chen, Senior Member, IEEE
# Abstract #
Light field semantic segmentation accurately identifies the semantic information of the scene, offering solutions for various intelligent computing tasks in consumer electronics and CIoT, such as portrait segmentation, image editing and environmental perception. However, the high dimensionality, redundancy and computational cost in light field 4D data limit its application. To address this issue, we choose to decode the highly interleaved data into multi-scale macro-pixel images and propose a prompt-based light field semantic segmentation network that incorporates an efficient transformer architecture to capture and learn the global and long-range dependencies. Unlike the previous implicit embedding method, we introduce a visual prompt component called Explicit Angle Prompting (EAP) in the model. Our key insight is to adaptively generate crucial angle-based visual prompts explicitly during the training stage. This enhances the understanding of geometric information, such as object shape and structure. Furthermore, the self-attention design in the encoder and the multi-scale feature fusion mechanism ensure that the network comprehends the global and contextual information of the image from the perspective of the light field spatial dimensions. Extensive experiments demonstrate the potential of light field prompt learning for semantic segmentation, and the proposed model achieves state-of-the-art (SOTA) performance. The code will be released.
# Installation
python3.7
CUDA 10.1
pytorch 1.7.1
pip install opencv-python 4.5.1.48
# the code will be relased
This manuscript is under review.
# Contact #
Any questions, please contact the email at jiachen@email.tjut.edu.cn
