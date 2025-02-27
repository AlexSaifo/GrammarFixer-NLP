# **GrammarFixer-NLP**  
A deep learning-based Grammar Error Correction (GEC) system for English text using **T5 Transformer** and **LSTM Encoder-Decoder with Attention**.  

## **Features**  
✅ Corrects English grammar errors using NLP models  
✅ Supports **T5** and **LSTM Encoder-Decoder with Attention**  
✅ Evaluated with **GLEU** and **ROUGE** metrics  
✅ Preprocessed dataset with tokenization and cleaning  

## **Installation**  
```bash
git clone https://github.com/yourusername/GrammarFixer-NLP.git  
cd GrammarFixer-NLP  
```


## **Dataset**  
- **Source:** GEC_LANG8  
- Includes **incorrect sentences** and **corrected versions**  
- Preprocessed with normalization, tokenization, and filtering  

## **Evaluation**  
| Model | GLEU | ROUGE-1 | ROUGE-2 | ROUGE-L | Training Time |
|--------|------|---------|---------|---------|--------------|
| T5 | 0.5751 | 0.8043 | 0.6333 | 0.7918 | ~1h (GPU) |


## **Technologies Used**  
- Python  
- TensorFlow / PyTorch  
- Hugging Face Transformers  
- NLP Data Preprocessing  

## **Contributors**  
- **Bilal Younes**  
- **Ghassan Jarbooa**  
- **Amer Kanhoosh**  
- **Qusai Al-Sheikh Ali**  
- **Ali Saifo**  

## **License**  
MIT License  
