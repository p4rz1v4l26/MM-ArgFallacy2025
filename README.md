# MM-ArgFallacy2025




This project implements a multimodal system to detect and classify argumentative fallacies in political debates using both text and audio inputs.

## 🔍 Fallacy Types
- Ad Hominem  
- Appeal to Emotion  
- Appeal to Authority  
- False Cause  
- Slippery Slope  
- Slogan  

## 💡 Key Features
- Multimodal fusion (Text + Audio)
- Models: RoBERTa, Wav2Vec2.0, BiLSTM
- Dataset: MM-USED-fallacy
- Audio features: MFCCs, pitch, prosody
- Text features: BERT-based embeddings, argument structure
- Attention-based fusion mechanism

## 📊 Results
- Text-only models perform best overall
- Multimodal models enhance detection of delivery-based fallacies
- Audio-only models underperform due to noise/speaker variability

## ⚙️ Tech Stack
- PyTorch, Hugging Face Transformers, MAMkit
- Librosa, Scikit-learn, Torchaudio
- Streamlit (for demo)


## 📌 Contributors
- [Avinash Warale](https://github.com/p4rz1v4l26)    
- [Siddharth Pagaria](https://github.com/sidpagaria) 
- [Chaitra V](https://github.com/chaitra1323)        
- [Spoorthi HG](https://github.com/spoorthihg25)     


