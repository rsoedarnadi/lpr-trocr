Here’s a `README.md` for your GitHub repository:  

---

# License Plate Recognition using Transformer OCR  
🏆 **14th Place in National Data Science Competition | 96.75% Character Accuracy | Transfer Learning Approach**

## Project Overview  
This project was developed as part of a license plate recognition competition. The objective was to build an Optical Character Recognition (OCR) model capable of accurately recognizing license plate characters from images.  

Our approach leveraged **transfer learning** on a **Transformer-based OCR architecture**, resulting in a **96.75% character accuracy rate**, placing **14th in the competition** based on the F1 score.

## Key Features  
- **Transfer Learning**: Utilized a pre-trained Transformer OCR model for efficient learning and improved performance.  
- **High Accuracy**: Achieved a **96.75% character accuracy rate**, demonstrating strong generalization across various license plate styles and conditions.  
- **Robust Performance**: Ranked **14th place** in the competition in terms of F1 score.

## Methodology  
1. **Data Preprocessing**:  
   - Cleaned and augmented license plate images to enhance model robustness.  
   - Standardized image resolution for consistent input.  
   
2. **Model Architecture**:  
   - Implemented a Transformer-based OCR model with transfer learning through the HuggingFace API to reduce training time and improve accuracy.  
   
3. **Training**:  
   - Fine-tuned the pre-trained model using the competition dataset.  
   - Applied early stopping and learning rate scheduling for optimal performance.

## Results  
- **Character Accuracy Rate**: 96.75%  
- **Competition Ranking**: 14th place based on F1 score.

## Repository Structure  
```
├── data/                 # Dataset files
├── src/                  # Source code for preprocessing, training, and evaluation
├── submission/           # Prediction results and submission file  
└── README.md             # Project description  
```
