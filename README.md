# Documate-AI
Documate AI provides an offline chat with the private PDF
Overview

DocuMate AI is an offline, AI-powered document assistant designed to help users interact with and extract insights from their documents securely and efficiently. Built using an open-source stack, DocuMate AI leverages state-of-the-art technologies, including Llama 3.2, HuggingFace BGE embeddings, and Qdrant, to process and answer queries about documents without requiring internet access. This ensures complete data privacy and security.

Key Features

Offline Functionality: Runs entirely on local infrastructure, safeguarding sensitive data.

PDF Upload and Preview: Users can upload PDF documents and preview them within the application.

Embeddings Creation: Generates vector embeddings of the document content for efficient query retrieval.

Interactive Chatbot: Enables users to query their documents interactively and receive detailed, well-explained responses.

Seamless Integration: Integrates tools like Streamlit, Docker, and LangChain for an intuitive and robust user experience.

Technologies Used

LangChain: Modular framework for building custom language model applications.

LangChain Community and Core Libraries: Extended capabilities for handling embeddings and retrieval.

Qdrant: High-performance vector database for managing document embeddings and fast retrieval.

Llama 3.2: Advanced local language model for generating accurate and context-aware responses.

HuggingFace BGE: Pre-trained embedding model for creating high-quality vector representations.

Docker: Containerization platform to ensure portability and consistency across different environments.

Streamlit: Framework for building an interactive and user-friendly web interface.

Installation

Follow these steps to set up DocuMate AI on your local machine:

Clone the Repository:

git clone https://github.com/IpshitaKarmakar/DocuMateAI.git
cd DocuMateAI

Install Dependencies:
Use pip to install the required Python packages:

pip install -r requirements.txt

Run Qdrant in Docker:
Ensure Docker is installed and running. Start a Qdrant instance using:

docker run -d -p 6333:6333 qdrant/qdrant

Launch the Application:
Start the Streamlit app:

streamlit run app.py

Access the Application:
Open your browser and navigate to http://localhost:8501.

How to Use

Upload a PDF: Navigate to the "Chatbot" section and upload your document.

Generate Embeddings: Click on the "Create Embeddings" checkbox to process your document for queries.

Interact with the Chatbot: Type your queries, and the chatbot will respond with insights derived from the document.

Review Responses: All conversations are displayed in the chat interface for easy reference.

Use Cases

Research and Analysis: Extract key information and insights from research papers, reports, and manuals.

Legal Document Review: Quickly understand contracts and legal documents.

Educational Purposes: Summarize and query academic papers, textbooks, or lecture notes.

Business Documentation: Retrieve important data from business proposals, invoices, or policy documents.

Project Structure

DocuMateAI/
├── app.py                # Main application file
├── chatbot.py            # Chatbot manager implementation
├── vectors.py            # Embeddings manager implementation
├── requirements.txt      # Python dependencies
├── logo1.png.webp        # Logo for the app sidebar
├── README.md             # Project documentation
└── ...                   # Additional files and resources


Acknowledgments

Special thanks to the IOCL Kolkata Team for their support and guidance in the development of this project. Additionally, gratitude to the creators of LangChain, Qdrant, and HuggingFace for their amazing open-source tools.

Contact

Developer: Ipshita Karmakar

Email: ipshita.cse.22@nitap.ac.in

GitHub: IpshitaKarmakar

Thank you for exploring DocuMate AI! 🚀
