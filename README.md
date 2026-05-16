# 🤖 Generative AI - Learning Repository

## 📚 Project Overview

This repository is a comprehensive learning guide for **Generative AI and Natural Language Processing (NLP)**. It contains practical implementations, examples, and tutorials covering fundamental NLP concepts to advanced generative models.

### 🎯 Purpose
- Learn and implement NLP fundamentals from scratch
- Explore tokenization, stemming, lemmatization, and text preprocessing
- Understand generative AI concepts and models
- Build real-world NLP applications

---

## 🚀 Roadmap

### **Phase 1: NLP Fundamentals** ✅ (In Progress)
- [✅] Text Preprocessing Basics
- [✅] Tokenization
  - Word Tokenization
  - Sentence Tokenization
- [✅] Stemming (Porter Stemmer, Snowball Stemmer)
- [✅ ] Lemmatization
- [✅ ] Stop Words Removal
- [ ] Text Normalization

### **Phase 2: Text Representation** 📍 (Upcoming)
- [ ] Bag of Words (BoW)
- [ ] TF-IDF (Term Frequency-Inverse Document Frequency)
- [ ] Word Embeddings
  - Word2Vec
  - GloVe
  - FastText
- [ ] Contextual Embeddings (BERT, GPT)

### **Phase 3: Advanced NLP Tasks** (Planned)
- [ ] Named Entity Recognition (NER)
- [ ] Sentiment Analysis
- [ ] Text Classification
- [ ] Machine Translation
- [ ] Question Answering Systems
- [ ] Text Summarization

### **Phase 4: Generative Models** (Future)
- [ ] Introduction to Transformers
- [ ] GPT Architecture & Fine-tuning
- [ ] Language Model Basics
- [ ] Text Generation Techniques
- [ ] Prompt Engineering
- [ ] Building Chatbots

### **Phase 5: Advanced Generative AI** (Roadmap)
- [ ] LLM Fine-tuning on Custom Data
- [ ] Retrieval Augmented Generation (RAG)
- [ ] Building Production-Ready AI Applications
- [ ] Model Optimization & Deployment
- [ ] Multimodal Generative Models

---

## 📁 Repository Structure

```
Generative AI/
├── Tokenization.ipynb          # Tokenization techniques & examples
├── Stemming.ipynb              # Stemming algorithms & comparison
├── Lemmatization.ipynb         # Lemmatization examples (upcoming)
├── Text_Preprocessing.ipynb    # Complete preprocessing pipeline
├── Embeddings/                 # Word embeddings implementation
├── Classification/             # Text classification models
├── Generative_Models/          # Transformer & GPT implementations
└── README.md                   # This file
```

---

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|-----------|---------|
| **Python 3.13.13** | Programming Language |
| **Jupyter Notebook** | Interactive Development |
| **NLTK** | Natural Language Toolkit |
| **Scikit-learn** | Machine Learning |
| **PyTorch** | Deep Learning Framework |
| **Transformers** | Pre-trained Models |
| **Pandas & NumPy** | Data Processing |

---

## 🎓 Learning Path

### Beginner
1. Start with **Tokenization.ipynb** - Learn basic text splitting
2. Move to **Stemming.ipynb** - Understand word normalization
3. Explore **Text_Preprocessing.ipynb** - Complete pipeline

### Intermediate
1. Study Word Embeddings (Word2Vec, GloVe)
2. Learn Text Classification techniques
3. Implement Sentiment Analysis projects

### Advanced
1. Study Transformer Architecture
2. Fine-tune Pre-trained Models (BERT, GPT)
3. Build End-to-End NLP Applications

---

## 📊 Key Concepts Covered

### ✨ Text Preprocessing
- Tokenization (word, sentence, regex)
- Stemming (Porter, Snowball)
- Lemmatization
- Lowercasing & Normalization
- Stop words handling

### 🧠 NLP Models
- Bag of Words
- TF-IDF Vectorization
- Word2Vec Embeddings
- BERT & Transformers
- GPT Architecture

### 🎯 Applications
- Sentiment Analysis
- Text Classification
- Named Entity Recognition
- Machine Translation
- Text Generation

---

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.13+
pip (Python Package Manager)
Jupyter Notebook
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Umam-3289/Generative-AI.git
   cd Generative-AI
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open any notebook and start learning!**

---

## 📦 Required Dependencies

```
jupyter==4.0.0
nltk==3.8.1
numpy==1.24.0
pandas==2.0.0
scikit-learn==1.3.0
torch==2.0.0
transformers==4.30.0
matplotlib==3.7.0
seaborn==0.12.0
```

---

## 💡 Example Usage

### Tokenization Example
```python
from nltk.tokenize import word_tokenize, sent_tokenize

text = "Hello world! This is NLP."
words = word_tokenize(text)
sentences = sent_tokenize(text)
```

### Stemming Example
```python
from nltk.stem import PorterStemmer

stemmer = PorterStemmer()
words = ['running', 'runs', 'ran']
stemmed = [stemmer.stem(word) for word in words]
```

---

## 📈 Progress Tracker

| Phase | Status | Completion |
|-------|--------|-----------|
| Phase 1: NLP Fundamentals | 🟡 In Progress | 75% |
| Phase 2: Text Representation | ⚪ Upcoming | 0% |
| Phase 3: Advanced NLP Tasks | ⚪ Planned | 0% |
| Phase 4: Generative Models | ⚪ Future | 0% |
| Phase 5: Advanced Generative AI | ⚪ Roadmap | 0% |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new notebooks with implementations
- Improve existing code
- Report issues
- Suggest new topics

### Steps to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📝 Notes & Tips

- 📌 Each notebook is self-contained and can be run independently
- 💾 Datasets are included in relevant notebooks
- 🔍 Refer to code comments for detailed explanations
- 🎓 Check the official documentation for libraries used
- 🐛 If you encounter errors, check your NLTK data is downloaded

### Download NLTK Data
```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
```

---

## 📚 Resources & References

- [NLTK Documentation](https://www.nltk.org/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Stanford NLP Course](https://web.stanford.edu/class/cs224n/)
- [Fast.ai NLP](https://www.fast.ai/)
- [Papers with Code](https://paperswithcode.com/)

---

## 📧 Contact & Support

- **Author**: Md Umam Adnan Khan
- **Email**: Umamkhan9931@gmail.com
- **GitHub**: [@Umam-3289](https://github.com/Umam-3289)

Feel free to reach out for questions, suggestions, or collaborations!

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## ⭐ Acknowledgments

- Thanks to the NLTK community for excellent NLP tools
- Inspired by Stanford NLP and Fast.ai courses
- Special thanks to all contributors

---

<div align="center">

**Made with ❤️ for NLP Enthusiasts**

⭐ If you find this helpful, please consider giving it a star! 

[![Stars](https://img.shields.io/github/stars/yourusername/Generative-AI.svg)](https://github.com/yourusername/Generative-AI)
[![Forks](https://img.shields.io/github/forks/yourusername/Generative-AI.svg)](https://github.com/yourusername/Generative-AI)
[![Issues](https://img.shields.io/github/issues/yourusername/Generative-AI.svg)](https://github.com/yourusername/Generative-AI)

**Happy Learning! 🚀**
</div>