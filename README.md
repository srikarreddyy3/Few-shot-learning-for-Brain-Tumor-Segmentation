



## Project Overview: Exploring Few-Shot Learning for Brain Tumor Segmentation

This project focuses on developing an advanced machine learning model for brain tumor segmentation using the Brain Tumor Segmentation (BraTS) dataset. The primary goal was to design a model capable of accurately segmenting brain tumor subregions in MRI scans, which is critical for applications in neurosurgery and oncology. Given the limited availability of labeled medical data, few-shot learning techniques were explored to enhance model performance.

The solution involved modifying the traditional U-Net architecture by incorporating Residual Extended Skip (RES) blocks, resulting in the RU-Net model. This model addresses challenges such as informational degradation and dataset imbalance, leading to improved segmentation accuracy. By implementing a teacher-student learning approach, pseudo-labels were generated for additional data, further refining the model's capabilities.

The RU-Net model demonstrated significant improvements in segmenting different tumor subregions, achieving a Dice score of 0.7234 for whole tumors and up to 0.8557 for peritumoral edema. Future directions include leveraging pre-trained weights from autoencoders to further optimize the model and exploring ensemble methods for enhanced performance.

This study highlights the potential of machine learning techniques in advancing medical diagnosis and treatment, particularly in automating complex tasks like brain tumor segmentation.

