# 📊 DataQuery — Conversational Data Analysis with LLMs

DataQuery is an intuitive, Streamlit-based web application that lets you upload or connect datasets and ask questions using natural language. Powered by state-of-the-art large language models (LLMs) like **Google Gemini** and **Groq (LLaMA)**, it provides AI-driven insights on your data in real-time.

---

## ✅ Prerequisites

Before setting up the application, ensure you have the following installed on your system:

- **Python** (version 3.10 / 3.11 / 3.12)
- **Visual Studio Code (VS Code)** as your IDE
- **Python Extension** installed within VS Code

---

## 🚀 Getting Started

Follow these steps to set up and run the application locally:

### 1. Clone the Repository

Clone this repository to your desired directory using:

```bash
git clone <your-repository-url>
```

Then navigate into the cloned folder:

```bash
cd <your-project-folder>
```

---

### 2. Set Up a Python Virtual Environment

Create a virtual environment in the same project directory. This helps isolate dependencies for this app.

📽️ [How to Create a Virtual Environment (YouTube Guide)](https://youtu.be/RUGm1Lwc55s?si=dkhBxk3N6-yUOgju)

Once you've created the virtual environment, activate it:

- **Windows**:
  ```bash
  .\venv\Scripts\activate
  ```

- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

---

### 3. Install Dependencies

Use the provided `requirements.txt` file to install all necessary Python libraries:

```bash
pip install -r requirements.txt
```

---

### 4. Add Your API Keys

You’ll need API keys to connect to the LLM providers:

- 🔑 [Google Gemini API Key](https://ai.google.dev/gemini-api/docs)
- 🔑 [Groq API Key](https://console.groq.com/keys)

Once you’ve obtained your keys, create a `.env` file in the root of the project and add:

```env
GOOGLE_API_KEY=your_gemini_api_key
GROQ_API_KEY=your_groq_api_key
```

---

## 📁 Project Structure

After setup, your project directory should look like this:

```
project-folder/
│
├── venv/
├── .env
├── chat.py
├── requirements.txt
```

---

## 🧠 How to Run the Application

Once everything is set up, launch the app by running the following command in your terminal:

```bash
streamlit run chat.py
```

Make sure your terminal is pointed to the project’s root directory when executing this command.

---

## 🎉 You're All Set!

The application will open in your default browser. Start uploading datasets or connect your MySQL database and begin querying with natural language!

---

## 📬 Feedback & Contributions

Feel free to open issues or pull requests. Contributions are welcome!
