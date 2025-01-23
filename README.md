# SmartDOC-chat-with-doc
# SmartDOC: Interactive Document Conversations with AI 📄💬
Transform your documents into intelligent, interactive Q&amp;A sessions with SmartDOC. Upload PDFs, Word, PPT, or Text files, and get instant, context-aware responses powered by LLAMA 3.3 70b-versatile model and FAISS. Simplify knowledge extraction, save time, and enhance productivity with this user-friendly AI tool!

## 📖 About SmartDOC

SmartDOC is designed to make interacting with documents effortless and insightful. Instead of reading through pages of content, you can simply ask questions and get precise answers instantly. Built with cutting-edge AI models, SmartDOC combines document parsing, vector-based search, and conversational AI to provide a seamless and intelligent experience.

### Key Benefits
- Simplifies knowledge extraction from complex documents.
- Boosts productivity by reducing time spent searching for information.
- Supports multiple document formats, making it versatile for various use cases.

---

## ❓ Why SmartDOC

### 🚀 Transform Document Handling:
- Tired of sifting through long PDFs or slides? SmartDOC makes navigating your documents easier than ever with natural language queries.

### 💡 Key Use Cases:
- **Students & Researchers**: Quickly locate specific information in textbooks or research papers.
- **Professionals**: Streamline data extraction from reports, presentations, and legal documents.
- **Teams**: Enable knowledge sharing by transforming shared documents into interactive assets.

### 🌟 Unique Features:
- Supports **multi-format documents** (PDF, Word, PowerPoint, Text).
- **Real-time processing** for instant insights.
- **State-of-the-art AI** (LLAMA 3.3 70b-versatile model and FAISS) for accurate, context-aware responses.
- **Easy-to-use interface** powered by Streamlit.

---

## 🛠️ Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Akanksha4554/smartdoc.git
   cd smartdoc
   ```

2. **Install Dependencies**:
   Use the provided `requirements.txt` to set up the environment:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Environment Variables**:
   Update the `.env` file with your `GOOGLE_API_KEY`:
   ```plaintext
   GOOGLE_API_KEY=Your_API_KEY
   ```

4. **Run the Application**:
   Launch the Streamlit app:
   ```bash
   streamlit run main.py
   ```

5. **Upload Documents and Interact**:
   Use the interface to upload files and ask questions about their content.

---

## 📁 File Overview

- **`main.py`**: Core application logic with support for document processing, vectorization, and conversational interaction.
- **`requirements.txt`**: Dependency list for setting up the Python environment.
- **`.env`**: Configuration file for storing sensitive keys (e.g., `GROQ_API_KEY`).

---

## 🛡️ Requirements

- Python 3.8+
- Compatible with macOS, Linux, and Windows

---

## 📚 Dependencies

This project relies on several Python libraries, including:
- **LangChain**: For building conversational AI chains.
- **FAISS**: For efficient vector-based document retrieval.
- **Streamlit**: For creating the interactive interface.
- **Hugging Face Transformers**: For embedding generation.

See the complete list in [`requirements.txt`](requirements.txt).

---

## ⚙️ Key Functions in `main.py`

- **Document Loaders**:
  Supports PDF, Word, PowerPoint, and Text formats.
- **Vector Store Setup**:
  Uses FAISS for indexing and retrieval with chunk-based optimization.
- **Conversational Chain**:
  Built with ChatGroq and memory for natural Q&A experiences.

---

## 🤝 Contributions

We welcome contributions! Feel free to fork the repository, create a new branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

```
