<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SamvidhaanAI: A Legal Companion Chatbot</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; }
        h1, h2, h3 { color: #2c3e50; }
        ul { margin-top: 0; }
        code { background-color: #f4f4f4; padding: 2px 4px; border-radius: 3px; }
        .section { margin-bottom: 40px; }
    </style>
</head>
<body>
    <h1>SamvidhaanAI: A Legal Companion Chatbot using Retrieval-Augmented Generation (RAG) and Gemini AI</h1>

    <p><strong>Artificial Intelligence (BCSE306L)</strong><br>
    <strong>Faculty Name:</strong> Dr. Vijayalakshmi A<br>
    <strong>Team Members:</strong><br>
    Gokul Ram K – 23BAI1462<br>
    Kishore A G – 23BAI1577<br>
    Shyam Karthinathan P K – 23BAI1394</p>

    <div class="section">
        <h2>1. Abstract</h2>
        <p>SamvidhaanAI is a legal chatbot designed to improve accessibility to the Indian Constitution using a Retrieval-Augmented Generation (RAG) pipeline powered by Google's Gemini AI. The system semantically embeds constitutional content using Google’s embedding model and retrieves relevant sections through a vector database (ChromaDB). On top of this, Gemini AI interprets and generates accurate, structured legal responses. This project combines Python, LangChain, and Streamlit to offer an intelligent interface that transforms how users interact with complex legal documents.</p>
    </div>

    <div class="section">
        <h2>2. Introduction</h2>
        <p>The Indian Constitution poses challenges for interpretation due to its intricate legal language and massive structure. Citizens often struggle to grasp its provisions. SamvidhaanAI addresses this by using AI with a conversational interface to offer grounded, contextually coherent legal responses.</p>
    </div>

    <div class="section">
        <h2>3. Problem Statement</h2>
        <ul>
            <li>Complex Legal Language</li>
            <li>Massive Volume</li>
            <li>Limited Intelligent Tools</li>
        </ul>
    </div>

    <div class="section">
        <h2>4. Our Solution</h2>
        <ul>
            <li>RAG-based context-aware answers</li>
            <li>Semantic Embeddings</li>
            <li>Contextual Memory</li>
            <li>Interactive Frontend using Streamlit</li>
        </ul>
    </div>

    <div class="section">
        <h2>5. Technical Architecture and Concepts</h2>
        <h3>a. RAG</h3>
        <p>Uses a retriever and Gemini generator to provide grounded answers from the Constitution.</p>
        <h3>b. Embeddings</h3>
        <p>Google’s <code>embedding-001</code> to convert constitutional chunks to vectors.</p>
        <h3>c. Vector Store - ChromaDB</h3>
        <ul>
            <li>Efficient similarity search</li>
            <li>Persistence</li>
            <li>LangChain integration</li>
            <li>Local hosting</li>
        </ul>
        <h3>d. Similarity Search</h3>
        <p>Cosine similarity with top-k = 10 for document retrieval.</p>
        <h3>e. Language Model</h3>
        <ul>
            <li>Gemini 1.5 Pro</li>
            <li>Structured Output</li>
            <li>Multimodal potential</li>
            <li>Low hallucination rate</li>
        </ul>
    </div>

    <div class="section">
        <h2>6. Implementation</h2>
        <ol>
            <li>Parsed and chunked Constitution</li>
            <li>Embedded chunks into ChromaDB</li>
            <li>Top 10 chunks retrieved using similarity search</li>
            <li>Gemini generated response using context</li>
            <li>Displayed via Streamlit with session memory</li>
        </ol>

        <h3>Component | Tool/Technology</h3>
        <ul>
            <li>Backend: Python</li>
            <li>AI Framework: LangChain</li>
            <li>Embeddings: Google Gen AI (<code>embedding-001</code>)</li>
            <li>Vector Store: ChromaDB</li>
            <li>PDF Parsing: PyPDFLoader</li>
            <li>LLM: Gemini 1.5 Pro</li>
            <li>Interface: Streamlit</li>
            <li>Memory: Session-based history</li>
        </ul>
    </div>

    <div class="section">
        <h2>7. Output</h2>
        <p>Note: Some answers were cut to fit the Word document due to length.</p>
    </div>

    <div class="section">
        <h2>8. Conclusion</h2>
        <p>SamvidhaanAI shows how RAG can democratize access to complex legal knowledge like the Indian Constitution. It grounds responses in source documents and uses conversational memory to guide users intelligently and accurately.</p>
    </div>

    <div class="section">
        <h2>9. Future Enhancements</h2>
        <ul>
            <li>Expand knowledge base to include case laws</li>
            <li>Add multilingual support</li>
            <li>Enable scalable cloud deployment</li>
            <li>Integrate user feedback for learning</li>
        </ul>
        <p><strong>SamvidhaanAI</strong> represents a step toward digital democracy and AI-driven public empowerment.</p>
    </div>
</body>
</html>
