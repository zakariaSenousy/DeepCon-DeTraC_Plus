# DeepCon-DeTraC_Plus
DeepCon: Unleashing the Power of Divide and Conquer Deep Learning for Colorectal Cancer Classification

In this work, we present a novel deep learning approach, termed **DeepCon**, for the classification of CRC histopathology images. DeepCon is an advancement of the previously developed Decompose, Transfer, and Compose [DeTraC Model](https://ieeexplore.ieee.org/abstract/document/9075155) that aims to investigate the impact of trained composition on the learning process. DeTraC relies on class decomposition by partitioning image classes into subsets based on specific guidelines and assigns new labels to these subsets. It then proceeds to composition, assigning each instance classified to a subclass to its original/parent class. In contrast, **DeepCon** retains class decomposition but takes a transformative step in the composition process. It introduces a learnable composition step that dynamically assembles subclass results using a pre-trained CNN, fine-tuning weights for precise data-driven composition.

## Dataset Overview
In this work, we used the dataset **CRC-VAL-HE-7K** from the Institute of Pathology (University Medical Center Mannheim, Heidelberg University, Mannheim, Germany). The dataset contains 5,000 images, equally distributed in 8 classes of 625 images each. The classes include TUMOR, STROMA, COMPLEX, LYMPHO, DEBRIS, MUCOSA, ADIPOSE, and EMPTY/BACKGROUND. All images are 224×224 pixels at 0.5 microns per pixel with TIF format.



### Dataset's paper link: [Multi-class texture analysis in colorectal cancer histology](https://www.nature.com/articles/srep27988)


## Citation
If you use our **DeepCon** model in your research, please cite our paper:

*Suhaib Chughtai, Zakaria Senousy, Ahmed Mahany, Nouh Sabri Elmitwally, Khalid N. Ismail, Mohamed Medhat Gaber, and Mohammed M. Abdelsamea,* **"DeepCon: Unleashing the Power of Divide and Conquer Deep Learning for Colorectal Cancer Classification."**

