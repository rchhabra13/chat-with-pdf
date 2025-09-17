# 📄 Chat with PDF

A powerful RAG (Retrieval-Augmented Generation) application that allows you to have interactive conversations with PDF documents. Upload any PDF and ask questions about its content to get accurate, context-aware answers powered by advanced language models.

## 🌟 Features

### Core Functionality
- **PDF Upload & Processing**: Upload PDF documents of any size
- **Intelligent Question Answering**: Ask questions about PDF content
- **RAG-Powered Responses**: Accurate answers based on document content
- **Multiple LLM Support**: Works with various language models
- **Real-time Processing**: Instant responses to your queries
- **Context-Aware Answers**: Maintains conversation context

### Advanced Capabilities
- **Document Chunking**: Intelligent text splitting for optimal retrieval
- **Vector Embeddings**: Semantic search through document content
- **Source Attribution**: References specific parts of the document
- **Multi-Page Support**: Handles documents with multiple pages
- **Format Preservation**: Maintains document structure and formatting
- **Search Highlighting**: Highlights relevant text in responses

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- OpenAI API key (or other LLM provider)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rchhabra13/portfolio-projects.git
   cd portfolio-projects/chat_with_pdf
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up API keys**
   ```bash
   export OPENAI_API_KEY="your-openai-api-key-here"
   ```

4. **Run the application**
   ```bash
   streamlit run chat_pdf.py
   ```

5. **Access the application**
   - Open your browser to `http://localhost:8501`
   - Upload a PDF document
   - Start asking questions about its content

## 💡 Usage Examples

### Document Analysis
```
"What are the main findings in this research paper?"
"Summarize the key points from the executive summary."
"What methodology was used in this study?"
```

### Information Extraction
```
"What are the contact details mentioned in this document?"
"List all the dates mentioned in the PDF."
"What are the main recommendations?"
```

### Content Search
```
"Find information about machine learning algorithms in this document."
"Where is the budget information discussed?"
"What are the technical specifications mentioned?"
```

## 🛠️ Technical Architecture

### Core Technologies
- **Framework**: LangChain for RAG implementation
- **Language Model**: OpenAI GPT models
- **Vector Store**: ChromaDB for document embeddings
- **Text Processing**: PyPDF2 for PDF parsing
- **UI**: Streamlit for user interface
- **Embeddings**: OpenAI text-embedding-ada-002

### RAG Pipeline
1. **Document Upload**: PDF files are uploaded and processed
2. **Text Extraction**: PyPDF2 extracts text from PDF pages
3. **Text Chunking**: Documents are split into manageable chunks
4. **Embedding Generation**: Text chunks are converted to vector embeddings
5. **Vector Storage**: Embeddings are stored in ChromaDB
6. **Query Processing**: User questions are embedded and matched
7. **Context Retrieval**: Relevant chunks are retrieved based on similarity
8. **Answer Generation**: LLM generates answers using retrieved context

## 📊 Supported Document Types

### Academic Papers
- Research papers and studies
- Conference proceedings
- Journal articles
- Theses and dissertations

### Business Documents
- Reports and whitepapers
- Financial statements
- Legal documents
- Policy documents

### Technical Documentation
- User manuals
- API documentation
- Technical specifications
- Code documentation

### General Documents
- Books and ebooks
- News articles
- Blog posts
- Any text-based PDF

## 🔧 Configuration

### Environment Variables
```bash
OPENAI_API_KEY=your-openai-api-key
```

### Customization Options
- **Chunk Size**: Adjust text chunk size for better retrieval
- **Chunk Overlap**: Set overlap between chunks
- **Top K Results**: Number of relevant chunks to retrieve
- **Temperature**: Control response creativity
- **Max Tokens**: Limit response length

## 📈 Performance Features

- **Fast Processing**: Optimized for quick document processing
- **Memory Efficient**: Handles large documents efficiently
- **Scalable**: Works with documents of various sizes
- **Caching**: Intelligent caching for better performance
- **Error Handling**: Robust error handling and recovery

## 🔒 Security & Privacy

- **Local Processing**: Documents are processed locally
- **No Data Storage**: Documents are not permanently stored
- **API Security**: Secure API key management
- **Privacy Compliance**: Follows data privacy best practices

## 🤝 Contributing

We welcome contributions from developers and AI enthusiasts:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

### Areas for Contribution
- Support for more document formats
- Improved text extraction
- Better chunking strategies
- Enhanced UI/UX
- Performance optimizations

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- Create an issue in the GitHub repository
- Check the documentation
- Review the FAQ section

## 🔮 Roadmap

- [ ] Support for more document formats (DOCX, TXT, etc.)
- [ ] Multi-language support
- [ ] Advanced search capabilities
- [ ] Document comparison features
- [ ] Batch processing
- [ ] API endpoint for integration
- [ ] Mobile app support
- [ ] Advanced analytics

## 📊 Use Cases

### Research & Academia
- Literature review assistance
- Research paper analysis
- Academic document summarization
- Citation and reference extraction

### Business & Legal
- Contract analysis
- Legal document review
- Business report analysis
- Compliance checking

### Education
- Textbook question answering
- Study material analysis
- Assignment help
- Knowledge extraction

### Personal Use
- Document organization
- Information retrieval
- Content summarization
- Research assistance

## 🙏 Acknowledgments

- OpenAI for the language models
- LangChain for the RAG framework
- Streamlit for the user interface
- PyPDF2 for PDF processing
- ChromaDB for vector storage
- The open-source community

---

**Note**: This application is designed for educational and research purposes. Always ensure you have the right to process and analyze the documents you upload.


<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->
