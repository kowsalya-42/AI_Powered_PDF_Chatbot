# PDFs-Meet-A

---

# 💬 Chat With PDFs Using Zephyr 7B Alpha

Welcome to the Chat With PDFs App! This Google Colab-based application allows you to easily upload PDF files and have a conversation with their content using the advanced Zephyr 7B Alpha language model. Perfect for extracting specific insights or exploring documents interactively.

## ✨ Features

- **PDF Upload:** Seamlessly upload your PDF documents for analysis.
- **Conversational AI:** Interact with your PDF content using natural language queries and receive precise responses.
- **AI-Powered Insight:** Utilizes the Zephyr 7B Alpha model for deep comprehension and response generation.
- **Interactive Interface:** Gradio provides a clean and user-friendly web interface for easy document interactions.
- **Runs on Google Colab:** Leverages Colab’s free cloud resources, so no local setup is needed.

## 🛠️ Technology Stack

- **Zephyr 7B Alpha:** A cutting-edge language model for conversational AI.
- **LangChain:** For document processing and conversation management.
- **ChromaDB:** Efficiently stores and retrieves document embeddings.
- **Gradio:** Creates an intuitive web interface for user interaction.
- **Google Colab:** Provides the environment for running the application in the cloud.

## 📋 Requirements

To get started with this app, you’ll need the following Python packages installed in your Colab environment:
```
langchain
chromadb
gradio
```

## 🚀 How to Run

**1. Clone the Repository**


**2. Open the Colab Notebook**
- Navigate to the `.ipynb` file and open it in Google Colab.

**3. Install Dependencies**
- Run the provided installation cells in the notebook to install all necessary libraries:
    ```python
    !pip install langchain chromadb gradio
    ```

**4. Set Up Zephyr 7B Alpha Model**
- Follow the instructions in the notebook to initialize and load the Zephyr 7B Alpha model.

**5. Upload and Chat with Your PDF**
- Upload a PDF through the Gradio interface and start asking questions!

## 📝 Code Explanation

- **file_preprocessing(file):** Processes the uploaded PDF, extracting text and converting it into manageable chunks for analysis.
- **llm_pipeline(filepath):** Uses the Zephyr 7B Alpha model to handle user queries and provide relevant responses based on the document’s content.
- **displayPDF(file):** Displays the uploaded PDF within the Gradio interface.
- **main():** Sets up the Gradio interface, manages user interactions, and triggers the appropriate responses based on user input.

## 📸 Screenshots

### 🌟 Intuitive Chat Interface
![Screenshot 2024-09-18 213440](https://github.com/user-attachments/assets/b497b3ed-401b-475b-a2b5-54d66f95b146)



### 💬 Conversational PDF Responses
![Screenshot 2024-09-18 214341](https://github.com/user-attachments/assets/58b5d652-cef2-41e7-b244-6cf8d1d14393)


## 🔗 Links

- Documentation: [LangChain Documentation](https://docs.langchain.com/)


## 🤝 Contributing

Feel free to fork the repository and contribute by submitting pull requests. For major changes, please open an issue to discuss proposed modifications.

## 📜 License

This project is licensed under the MIT License.
