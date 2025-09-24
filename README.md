# AutoGen Multi-Agent Blog Project

This project demonstrates how to build a **virtual team of AI agents** using [AutoGen](https://microsoft.github.io/autogen/).  
The agents collaborate to research and generate a blog post about **Nvidia’s stock performance over the past month**.

---

## 📌 Project Overview
We implemented a group chat that coordinates five agents:

- **Admin (User Proxy):** Provides tasks and feedback  
- **Planner:** Determines the data and steps required  
- **Engineer:** Writes Python code based on Planner’s plan  
- **Executor:** Runs the code and reports results  
- **Writer:** Produces and refines a markdown blog post  

This workflow showcases **multi-agent collaboration** and structured task execution.

---

## 📂 Project Structure

```
autogen-multi-agent-blog/
│
├── notebooks/
│   └── Virtual_Lab_1.ipynb      # Jupyter Notebook with the multi-agent workflow
│
├── src/
│   └── autogen_blog.py          # (Optional) Python script version of the notebook
│
├── docs/
│   └── demo_screenshot.png      # Example output screenshot
│
├── .env.example                 # Template for environment variables
├── requirements.txt             # Dependencies list
├── README.md                    # Project documentation
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/autogen-multi-agent-blog.git
   cd autogen-multi-agent-blog
   ```

2. **Create and activate a Python 3.10 virtual environment**
   ```bash
   python3.10 -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**
   Install from the provided requirements file:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**  
   Create a `.env` file in the root directory with the following content:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

---

## 📹 Demo
 
- **Video Walkthrough:** https://iit.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=e73474af-2384-4974-9c36-b3590149e55d  

---

## 👤 Author

Sahilsingh Khalsa 
