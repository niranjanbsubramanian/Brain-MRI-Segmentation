# Brain-MRI-Segmentation
## Problem Description
A brain tumor is an abnormal mass of tissue in which cells grow and multiply abruptly, which remains unchecked by the mechanisms that control normal cells. Brain tumors are classified into benign tumors or low grade (grade I or II ) and malignant or high grade (grade III and IV). Benign tumors are non-cancerous and are considered to be non-progressive, their growth is relatively slow and limited. However, malignant tumors are cancerous and grow rapidly with undefined boundaries. So, early detection of brain tumors is very crucial for proper treatment and saving of human life.

Magnetic Resonance Imaging (MRI) of the brain is one of the best diagnostic imaging techniques used by neurologists for the detection of brain tumors. MRI images provide a lot of information about brain structure and abnormalities within brain tissues due to high-resolution images. In the past few decades, researchers have used different automated techniques for the detection of brain tumors using MRI images, as it is possible to scan and load these images in the computer for visual inspection. But recently, deep learning techniques have shown tremendous results and become the state of the art in the field of bioinformatics, medical informatics, and medical image analysis. In this post, I will discuss the detection of brain tumors from MRI scan images using a deep learning technique and compare the performance of different transfer learning approaches for the same.

## Dataset Description
The dataset is downloaded from [Kaggle.](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation)
This dataset was used in Mateusz Buda, AshirbaniSaha, Maciej A. Mazurowski "Association of genomic subtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm." Computers in Biology and Medicine, 2019.

This dataset contains brain MR images together with manual FLAIR abnormality segmentation masks.

The images were obtained from The Cancer Imaging Archive (TCIA). They correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.

Tumor genomic clusters and patient data is provided in data.csv file. The images are in .tif format
