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
