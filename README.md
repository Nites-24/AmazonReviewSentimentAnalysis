# **Amazon Review Sentiment Analysis**

## **Overview**
This project demonstrates the implementation of a **sentiment analysis model** to classify Amazon customer reviews as either positive or negative. It leverages cutting-edge **NLP techniques** using **BERT** (Bidirectional Encoder Representations from Transformers). The project introduces key concepts in natural language processing and deep learning, including:
- Text preprocessing and tokenization.
- Transformer-based architecture.
- Efficient handling of large datasets.

---

## **Project Details**
- **Framework**: PyTorch and Hugging Face Transformers.
- **Dataset**: Amazon Reviews (customer feedback on products)
  - **Training Data**: 3.6 million reviews.
  - **Testing Data**: 400,000 reviews.
  - Each review contains a:
    - **Title**: A brief summary of the review.
    - **Content**: The full review text.
    - **Label**: Sentiment (0 = Negative, 1 = Positive).
- **Model Architecture**:
  - **Preprocessing**: BERT tokenizer for text encoding.
  - **Base Model**: Pre-trained BERT (fine-tuned for sentiment classification).
  - **Output Layer**: Fully connected layer for binary classification.

---

## **Code and Notebook**
You can also open the notebook in Google Colab for interactive execution:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1niVpg2PIlgeBsbspHgmSyqEuW7dvBXmr#scrollTo=sWBHIJJ4jajY)

---

## **Results**
### **Accuracy Achieved**:
- **Training Set**: 96% accuracy.
- **Testing Set**: 94% accuracy.

### **Visualizations**
The project includes various visualizations to better understand the data and model performance:
- **Training Data Distribution**  
  ![Train Data Distribution](images/train_data_distribution.png)
- **Testing Data Distribution**  
  ![Test Data Distribution](images/test_data_distribution.png)
- **Predicted Sentiments**  
  ![Predicted Sentiments](images/predicted_sentiments.png)

### **Learning Outcomes**
- Learned the basics of neural networks and their components.
- Gained hands-on experience with transformer-based NLP models like BERT.
- Processed and analyzed millions of customer reviews.
- Learned the importance of data preprocessing for model performance.
- Visualized sentiment distributions and model predictions. 
  

---

### **Future Improvements** 
- Experiment with larger transformer models for better accuracy.
- Optimize preprocessing and inference for faster execution.
- Apply transfer learning to other domains, such as movie or hotel reviews.


### **Contributors**
Teja Gopal Reddy Vaka - Aspiring to become a top 1% AI professional.





