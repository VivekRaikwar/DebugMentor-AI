  # 🤖 DebugMentor AI  
Welcome to **DebugMentor AI** — an intelligent community chatbot that answers user queries and recommends expert trainers based on your needs! Built with **Streamlit**, **Sentence Transformers**, **Supabase**, and powered by the **Groq Llama-3.1-70b** model, this project connects users to domain experts while delivering AI-driven conversational responses.  

## 🌟 Key Features  
-  **Conversational AI Assistant**: Answers your questions using Groq's powerful LLM.  
-  **Trainer Recommendations**: Suggests relevant trainers based on user queries via semantic similarity search.  
-  **Supabase Integration**: Fetches and manages trainer data from a secure Supabase database.  
-  **Fast Embedding Search**: Uses SentenceTransformer (`all-MiniLM-L6-v2`) for efficient similarity matching.  
-  **Streamlit Frontend**: Clean and interactive UI built for easy usage.  

## 🚀 Getting Started  

### Prerequisites  
- Python 3.8+  
- Supabase account and API keys  
- Groq API key  
- Installed Python packages (listed in `requirements.txt`)  

### Installation  
```bash  
git clone https://github.com/your-username/debugmentor-ai.git  
cd debugmentor-ai  
pip install -r requirements.txt  
```  

### Environment Variables  
Create a `.env` file in the root directory with the following variables:  
```bash  
SUPABASE_URL=your_supabase_url  
SUPABASE_KEY=your_supabase_service_key  
GROQ_API_KEY=your_groq_api_key  
```  

## 🏗️ Project Structure  
```bash  
├── app.py              # Main Streamlit application  
├── requirements.txt    # Python dependencies  
├── .env                # Environment variables (not included in repo)  
├── README.md           # Project documentation  
```  

## 🛠️ Tech Stack  
- **Python** (Backend logic)  
- **Streamlit** (Frontend UI)  
- **Sentence-Transformers** (`all-MiniLM-L6-v2` for embeddings)  
- **Supabase** (Database and backend service)  
- **Groq API** (LLM-powered responses)  
- **Logging** (Debugging and error tracking)  

## ✍️ Usage Instructions  
To launch the app, run:  
```bash  
streamlit run app.py  
```  
1. Enter your query in the input box.  
2. View AI-generated answers.  
3. Get a list of related trainers with clickable chat links!  
  

## 📜 License  
Distributed under the **MIT License**. See the `LICENSE` file for more information.  

## 📬 Contact  
Maintained by **VIVEK RAIKWAR**. For any queries or collaborations, feel free to connect!

---

Now, you can simply copy-paste this text into your `README.md` file. Let me know if you'd like further changes! 😊
