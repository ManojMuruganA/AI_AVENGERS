# Automated Website Content Summarizer and Translator

## 🚀 Summarize and Translate Website Content with Ease!

This project is a Python-based tool that **extracts text from web pages, summarizes the content, and translates it into a target language**. It utilizes **BeautifulSoup** for web scraping, **NLTK & Sumy** for summarization, and **Google Translate API & Deep Translator** for translation.

---

## 📌 Features

✅ **Web Scraping** – Extracts text from web pages using `BeautifulSoup`.  
✅ **Text Summarization** – Summarizes the extracted content using `NLTK` and `Sumy`.  
✅ **Language Translation** – Translates the summarized content into any specified language.  
✅ **Easy to Use** – Enter a URL, choose a summary method, and select the target language.  

---

## 🛠 Installation

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-username/automated-summarizer-translator.git
cd automated-summarizer-translator
```

### **2️⃣ Install Dependencies**  
Ensure you have **Python 3.8+** installed. Then, install the required packages:  
```sh
pip install -r requirements.txt
```

### **3️⃣ Download NLTK Resources**  
Run this command to download required datasets for summarization:  
```python
import nltk
nltk.download('punkt')
```

---

## ⚡ Usage

### **Run the Application**  
```sh
python main.py
```

### **Example Usage in Python Code**  
```python
from summarizer import summarize_content
from translator import translate_text

url = "https://example.com"
summary = summarize_content(url, method="sumy", num_sentences=3)
translated_summary = translate_text(summary, target_language="fr")

print("Summarized Text:", summary)
print("Translated Text:", translated_summary)
```

---

## 🧩 Project Structure

```
📂 automated-summarizer-translator
│── 📄 main.py                 # Main script to run summarization and translation
│── 📄 summarizer.py           # Module for text summarization
│── 📄 translator.py           # Module for translation
│── 📄 requirements.txt        # List of dependencies
│── 📄 README.md               # Project documentation
│── 📂 datasets/               # (Optional) Sample text datasets
│── 📂 tests/                  # Unit tests for summarization & translation
```

---

## 🔧 Customization

- Change the **summarization method** (`"nltk"` or `"sumy"`) in `summarizer.py`.  
- Modify the **translation language** by changing the `target_language` parameter in `translator.py`.  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request.

---

## ✨ Author

Developed by **[Your Name]**  
GitHub: [your-username](https://github.com/your-username)
