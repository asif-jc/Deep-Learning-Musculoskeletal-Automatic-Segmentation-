# Deep-Learning-Musculoskeletal-Automatic-Segmentation-
Honours Project: Automatic Segmentation for Lower Limb Bones &amp; Muscles using Deep Learning

The musculoskeletal structure of children remains a significantly underexplored domain in research, plagued by
challenges in the analysis of medical imaging data. Within medical imaging workflows, segmentation plays a
pivotal role by identifying and localizing anatomical structures, enabling the study of their morphological
changes over time. Manual segmentation, especially in paediatric populations, is a laborious and time-intensive
task that demands meticulous annotation by expert researchers. In this study, we propose a robust deep learning
based segmentation pipeline that performs automatic segmentation on Magnetic Resonance Imaging (MRI) on
populations of children. The segmentation model used within the study is the Resnet34 U-Net deep learning
architecture because of its strong segmentation accuracy and adaptability to transfer learning. The deep learning
segmentation pipeline consists of a medical data processing layer, the Resnet34 U-Net deep learning
segmentation model, and a denoising algorithm to post-process segmentation results. This is all integrated in a
user-friendly GUI for ease of use. Experimental results were compared to state-of-the-art deep learning based
segmentation methods within the biomedical domain, such as the nnU-Net framework, and the H-DenseUNet.
The experiment accuracy of the ResNet34 U-Net is 89% (DSC), and outperforms the nnU-Net framework’s 2D
U-Net and 3D U-Net models on the segmentation of the tibia, femur, fibula and pelvis musculoskeletal
structures. As well as the H-DenseUNet on the segmentation of the tibia structure.
