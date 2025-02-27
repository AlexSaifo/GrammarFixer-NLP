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
pip install -r requirements.txt  
```

## **Usage**  
### **Training the Model**  
```bash
python train.py --model t5 --epochs 3  
```
or  
```bash
python train.py --model lstm --epochs 10  
```

### **Running Inference**  
```bash
python infer.py --sentence "She don't knows how to do it."  
```
**Output:** `"She doesn't know how to do it."`

## **Dataset**  
- **Source:** GEC_LANG8  
- Includes **incorrect sentences** and **corrected versions**  
- Preprocessed with normalization, tokenization, and filtering  

## **Evaluation**  
| Model | GLEU | ROUGE-1 | ROUGE-2 | ROUGE-L | Training Time |
|--------|------|---------|---------|---------|--------------|
| T5 | 0.5751 | 0.8043 | 0.6333 | 0.7918 | ~1h (GPU) |
| LSTM-Enc-Dec | 0.2776 | 0.6112 | 0.6112 | - | ~44h (CPU) |

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
- **Ali Sefo**  

## **License**  
MIT License  
