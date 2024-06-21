# Brain-Tumor-Classification

## Overview
This project aims to develop a deep learning model for the detection and classification of brain tumors using Magnetic Resonance Imaging (MRI). The model leverages Convolutional Neural Networks (CNNs) to provide an accurate and efficient diagnosis, which is critical for early detection and treatment.

## Dataset Description
### What is a Brain Tumor?
A brain tumor is a collection, or mass, of abnormal cells in the brain. The rigid skull restricts growth, so any expansion in this confined space can lead to increased intracranial pressure, causing brain damage and potentially life-threatening situations. Brain tumors can be classified as either cancerous (malignant) or noncancerous (benign). Early detection and classification are crucial for effective treatment and patient survival.

### Importance of the Subject
Early detection and classification of brain tumors are essential in medical imaging research. Accurate diagnosis helps in selecting the most appropriate treatment method, potentially saving patients' lives.

### Methods
Deep learning approaches have shown significant promise in improving health diagnoses. According to the World Health Organization (WHO), proper brain tumor diagnosis involves:

### Detection of the tumor
Identification of the tumor's location
Classification based on malignancy, grade, and type
This project uses MRI scans to detect and classify brain tumors, leveraging a CNN-based multi-task classification model. This approach handles different classification tasks using a single model, enhancing efficiency and accuracy. The model also segments the tumor to identify its location.

## About the Dataset
The dataset combines three sources:
- Figshare
- SARTAJ Dataset
- Br35H

It contains a total of 7023 MRI images of human brains, categorized into four classes:
- Glioma
- Meningioma
- No Tumor
- Pituitary

The "No Tumor" class images are sourced from the Br35H dataset. The SARTAJ dataset had issues with misclassified glioma images, which were replaced with images from the Figshare site.

## Note
The image sizes in the dataset vary. It is recommended to resize images to a consistent size during pre-processing and remove any extra margins to improve model accuracy.

Ensure to resize the images and remove unnecessary margins before feeding them into the model. Pre-processing code can significantly enhance the model's performance.


## License
This project is licensed under the MIT License.

If you find this dataset helpful, please upvote it on [Kaggle!](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) Your support and feedback are greatly appreciated. Thank you! 😊

## Contact:
For any questions or suggestions, please reach out to pinildissanayaka@gmail.com.

## Acknowledgements:
We thank the contributors of the [Figshare](https://figshare.com/articles/dataset/brain_tumor_dataset/1512427), [SARTAJ](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri), and [Br35H](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection?select=no) datasets for making this research possible.
