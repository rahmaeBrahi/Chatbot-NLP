# AI Question-Answering Chatbot

An intelligent chatbot system powered by BERT NLP model with text interaction capabilities.

## ✨ Key Features
- **BERT-based Q&A**: Utilizes `deepset/bert-base-cased-squad2` model  
- **Dual Interface**: Web-based text chat interaction  
- **Admin Dashboard**: For content management and customization  
- **High Accuracy**: Achieved 80.11% F1 score on validation data  
- **Easy Integration**: Flask-based backend with responsive Bootstrap frontend  

## 🛠 Technical Specifications

### Model Performance
| Metric    | Score   |
|-----------|---------|
| F1 Score  | 80.11%  |
| Precision | 77.50%  |
| Recall    | 88.57%  |

### Technology Stack

**Backend**:
-  Transformers (BERT Q&A)
-  PyTorch
-  Flask

**Frontend**:
-  Bootstrap 5
-  JavaScript

#  Installation & Setup

1. **Clone the repository**
   
   git clone https://github.com/rahmaeBrahi/Chatbot-NLP.git
   cd Chatbot-NLP
2. **Install dependencies**
   pip install -r requirements.txt

3. **Initialize the model**
python main.py --init-model

4. **Run the backend**
   python backend.py
5. **Configuration**
   Edit config.json to customize settings

6. **Advanced Options**
   Model Switching: Replace model name in main.py:
   MODEL_NAME = "deepset/bert-base-cased-squad2" 
Change to roberta-base or other HuggingFace models if needed.

Database Integration: Pre-configured for PostgreSQL/MongoDB

7.👩‍💻 **Development Team**
Rahma Ebrahim

Poussy Ayman

jehad mahmoud 


   
