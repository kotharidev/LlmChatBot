# Java Chatbot Using TinyLlama Model

This project is a **Java-based chatbot** utilizing the **TinyLlama-1.1B-Chat-v0.6** model in **GGUF** format for natural language processing. The chatbot is built using **Spring Boot** and leverages the `llama.cpp` library to run the model.

## 💻 How to Run

1. **Download the TinyLlama model**:
   - Download the **TinyLlama-1.1B-Chat-v0.6.Q4_K.gguf** model from [Hugging Face](https://huggingface.co/player1537/TinyLlama-1.1B-Chat-v0.6-GGUF).

2. **Setup Java**:
   - Ensure you have **Java 17+** installed on your machine.
   - Use `mvn clean package` to build the JAR file.

3. **Run the application**:
   - Execute the following command in the terminal:

   ```bash
   java -Dllamacpp.model=/path/to/your/TinyLlama-1.1B-Chat-v0.6.Q4_K.gguf -jar target/LLMCpp-Chat-SpringBoot.jar
Replace /path/to/your/ with the actual path to your downloaded .gguf model file.

🤖 Features
TinyLlama-1.1B-Chat-v0.6 model integration.

Lightweight and efficient for use cases requiring fast inference.

Java-based implementation using Spring Boot for easy extensibility.

📦 Dependencies
Java 17 or higher

Spring Boot

llama.cpp

Hugging Face models

🌐 Credits
TinyLlama: Hugging Face - player1537

llama.cpp: llama.cpp GitHub

Spring Boot: Spring Boot Official

📷 Screenshots
![Screenshot](p/home/devarshikothari/Pictures/Screenshots/Screenshot from 2025-04-19 00-23-33.png)

⚙️ Future Enhancements
Adding support for multiple models.

Docker support for easier deployment.

API integrations for real-time use cases.

