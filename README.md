# BERT-Based-Chatbot-with-Streamlit


This project implements a chatbot application powered by the **BERT model** (Bidirectional Encoder Representations from Transformers) for natural language understanding. The chatbot is designed to provide intelligent responses to user queries based on a predefined set of question-and-answer pairs.

---

## Key Features

### 1. **Interactive Frontend**
- Built using **Streamlit**, a Python framework for creating web-based data applications.
- Users can type questions into a text input field and receive responses from the chatbot.

### 2. **Natural Language Processing**
- Uses the **BERT tokenizer and model** to extract contextual embeddings from text inputs.
- Calculates **cosine similarity** between user input and predefined questions to identify the best matching response.

### 3. **Background Customization**
- The application includes functionality to set a custom image as the background using CSS.

### 4. **Predefined Q&A Pairs**
- A set of common questions and their corresponding responses are stored and used for quick matching with user queries.

### 5. **Embeddings for Query Matching**
- The chatbot computes **BERT embeddings** for user inputs and predefined questions to identify the most contextually similar query using cosine similarity.

### 6. **Threshold-based Response**
- Responses are provided only if the similarity score exceeds a certain threshold, ensuring relevance.

---

## Use Cases

This chatbot can be used as a foundation for:
- AI-based customer service applications.
- Educational or informational assistants.
- Demonstrations of NLP capabilities in small-scale projects.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Required libraries:
  - `transformers`
  - `torch`
  - `scikit-learn`
  - `base64`
  - `streamlit`


---

## Usage

1. Launch the Streamlit application.
2. Type a question into the input field.
3. The chatbot will analyze your input and return the most relevant predefined response.

---

## Project Files

- `app.py`: Main application code.
- `requirements.txt`: List of required Python packages.
- `background.jpg`: Custom background image for the application (replace with your own image if needed).

---

## Example Q&A Pairs

- **Q:** What is your name?
  - **A:** I am a chatbot powered by BERT!
- **Q:** What is BERT?
  - **A:** BERT stands for Bidirectional Encoder Representations from Transformers. It’s a powerful NLP model.
- **Q:** Tell me a joke.
  - **A:** Why don't programmers like nature? It has too many bugs.

---

## Future Enhancements

- Add dynamic question-answer generation using fine-tuned BERT.
- Integrate with a larger knowledge base for more comprehensive responses.
- Enable multi-turn conversation capabilities.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [PyTorch](https://pytorch.org/)
