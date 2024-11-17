# Brain Tumor Segmentation using U-Net
This project focuses on the segmentation of brain tumors from medical imaging using a deep learning-based approach. The U-Net architecture, a popular model for biomedical image segmentation, is implemented to achieve accurate tumor delineation.

# **Summary**
This repository provides a solution for the semantic segmentation of brain tumors using the U-Net model. The project leverages TensorFlow and Keras for implementing the model and utilizes a dataset of medical images to train and validate the segmentation model.

Key features:

i) Uses U-Net architecture for semantic segmentation.
 
ii) Handles preprocessing and augmentation of brain tumor image data.
 
iii) Evaluates performance using metrics like Dice coefficient.

# **Methodology**

The project employs a comprehensive approach to brain tumor segmentation using the U-Net model. The dataset is organized into training, validation, and test sets, with all images preprocessed for normalization and resizing to ensure consistency. To improve the model's generalization capability, data augmentation techniques are applied, increasing the diversity of the dataset. The U-Net architecture, known for its encoder-decoder structure with skip connections, is implemented using TensorFlow and Keras. The encoder extracts features through convolutional layers, while the decoder reconstructs the segmentation masks using upsampling layers. The model is trained with a combination of binary cross-entropy loss and the Dice coefficient, with early stopping and learning rate reduction mechanisms in place to optimize training efficiency. Performance is evaluated on a validation dataset to ensure robust segmentation of brain tumor regions, making the methodology both rigorous and effective.

# **Results**
The model demonstrates high accuracy in segmenting brain tumors, as evidenced by performance metrics such as the Dice coefficient and Intersection over Union (IoU). Visualizations of the predicted masks further validate the effectiveness of the U-Net architecture in accurately identifying and delineating tumor regions, showcasing its robustness and precision in handling medical imaging tasks.




