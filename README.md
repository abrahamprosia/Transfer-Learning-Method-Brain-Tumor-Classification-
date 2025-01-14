# Transfer-Learning-Method-Brain-Tumor-Classification

## Overview
In this project, I used the Transfer Learning method to build a CNN architecture that classifies MRI images of the brain into four classes: Meningioma, Pituitary, Glioma, and No Tumor.

## Methods
- Various transfer learning methods were utilized, fine-tuned to achieve the most optimal results, and their performances were evaluated.
- Preprocessing techniques such as data augmentation (to introduce variability) and normalization were employed to improve model performance.

## Results
### Test Accuracy and Test Loss of the Transfer Learning Methods
- **Inception V3**  
  - Accuracy: 94.36%  
  - Loss: 47.75%  

- **DenseNet 121**  
  - Accuracy: 97.25%  
  - Loss: 29.80%  

- **VGG-16**  
  - Accuracy: 80.40%  
  - Loss: 68.18%  

- **ResNet-50**  
  - Accuracy: 49.96%  
  - Loss: 187.88%  

- **EfficientNetB0**  
  - Accuracy: 80.24%  
  - Loss: 85.22%  

### Conclusion
Based on the test accuracy, DenseNet 121 is the most efficient model among the five methods evaluated.

#### Classification Report for DenseNet 121 (Validation Data):
| Class       | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| Glioma      | 0.96      | 0.95   | 0.96     | 260     |
| Meningioma  | 0.95      | 0.93   | 0.94     | 267     |
| No Tumor    | 0.99      | 0.99   | 0.99     | 307     |
| Pituitary   | 0.96      | 0.99   | 0.97     | 308     |

- **Overall Accuracy**: 97%  
- **Macro Average**:  
  - Precision: 0.97  
  - Recall: 0.96  
  - F1-Score: 0.97  
- **Weighted Average**:  
  - Precision: 0.97  
  - Recall: 0.97  
  - F1-Score: 0.97  

## Additional Information
For more detailed results of all the methods, please refer to the "codes" folder accompanying this file.
