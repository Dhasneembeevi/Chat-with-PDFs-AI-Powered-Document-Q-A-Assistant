# 📚 Chat with Multiple PDFs – AI-Powered Document Q&A Assistant  

This project is a **Streamlit-based AI chatbot** that allows users to upload multiple PDFs and interact with them through **natural language queries**. It leverages **Hugging Face embeddings and FAISS vector storage** to efficiently retrieve relevant document content and generate responses using a **LLM (Large Language Model)**.

## 🚀 Features  
✅ Upload multiple PDFs for processing  
✅ Extract and split text from PDFs  
✅ Store and retrieve document content using **FAISS**  
✅ AI-powered conversational search using **Google FLAN-T5-XXL**  
✅ Memory-enabled chat for context-aware conversations  
✅ Interactive **Streamlit** UI for a seamless user experience  

## 🛠️ Technologies Used  
- **Python**  
- **Streamlit** – for building the web interface  
- **PyPDF2** – for extracting text from PDFs  
- **LangChain** – for text processing, retrieval, and conversation handling  
- **FAISS** – for efficient vector storage and similarity search  
- **Hugging Face Models** – for embeddings and language model  

## 📌 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/chat-with-pdfs.git
cd chat-with-pdfs
```

### 2️⃣ Create a Virtual Environment (Optional)  
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables  
Create a `.env` file in the project root and add any required API keys (if needed).

### 5️⃣ Run the Application  
```bash
streamlit run app.py
```

## 🎯 How It Works  
1️⃣ **Upload PDFs**: Add one or more PDF files through the sidebar.  
2️⃣ **Process Documents**: The app extracts and chunks text, then converts it into vector embeddings using **Hugging Face Instructor-XL**.  
3️⃣ **Ask Questions**: Type any question related to the documents, and the AI chatbot will provide responses based on document content.  
4️⃣ **Conversational Memory**: The chatbot remembers context, allowing for natural multi-turn conversations.  
