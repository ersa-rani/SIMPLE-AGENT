# 🤖 Greeting Agent

This project demonstrates the use of the `AsyncOpenAI` provider with the `Gemini API` to create a simple greeting agent. The agent responds to user greetings based on predefined instructions.

## ✨ Features
- 🚀 Loads environment variables using `dotenv`.
- 🔌 Utilizes `AsyncOpenAI` for API communication.
- 🤖 Implements an `Agent` to handle user greetings.
- ⚡ Uses `Runner` to execute the agent synchronously.

## 📌 Requirements
Ensure you have the following installed:
- 🐍 Python 3.8+
- 📦 `dotenv` for loading environment variables
- 📜 Required dependencies from `agents` module

## 📥 Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/ersa-rani/SIMPLE-AGENT.git
   cd SIMPLE_AGENT
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Create a `.env` file and add your Gemini API key:
   ```sh
   GEMINI_API_KEY=your_api_key_here
   ```

## 🚀 Usage
Run the script by executing:
```sh
python main.py
```
Enter your message when prompted. The agent will respond based on predefined instructions:
- **"hi" →** "Salam from Ersa Rani" 🕌
- **"bye" →** "Allah Hafiz from Ersa Rani" 👋
- **Other queries →** "Ersa is here just for greeting, I can't answer anything else, sorry." ❌

## 🛠️ Code Explanation
1. **📝 Load Environment Variables**: Loads the Gemini API key from `.env`.
2. **🔧 Initialize OpenAI Provider**: Configures the `AsyncOpenAI` provider with Gemini API settings.
3. **🧠 Configure Language Model**: Uses `OpenAIChatCompletionsModel` for interactions.
4. **🤗 Create Greeting Agent**: Defines agent behavior and instructions.
5. **🎯 Execute Runner**: Runs the agent synchronously and prints the response.

## 📜 License
This project is licensed under the MIT License.

## 👤 Author
[ERSA RANI]

