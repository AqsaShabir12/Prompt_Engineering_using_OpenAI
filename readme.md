# Prompt Engineering Projects with OpenAI API

This repository contains hands-on notebooks for exploring prompt engineering techniques using the OpenAI GPT models, culminating in the creation of a functional chatbot interface called **OrderBot**.

---

## Folder Structure

### PROMPT ENG

A series of structured lessons for mastering prompt engineering:

- `L1_Your_First_AI_Agent.ipynb` – Introduction to using LLMs with simple prompts  
- `l2-guidelines.ipynb` – Prompt formatting and best practices  
- `l3-iterative-prompt-development.ipynb` – Improving prompt performance through refinement  
- `l6-transforming.ipynb` – Prompt-based data transformation  
- `l7-expanding.ipynb` – Content generation using prompts  
- `l8-chatbot.ipynb` – Creating a conversational assistant and GUI chatbot (OrderBot)

---

## Project Highlight: `l8-chatbot.ipynb`

This notebook demonstrates how to:

- Use the **Chat Completion API** with system/user/assistant roles  
- Create dynamic multi-turn conversations  
- Implement temperature control for creative or deterministic outputs  
- Build a functional chatbot interface using `panel` (GUI toolkit)  
- Develop **OrderBot**, a chatbot that can take pizza orders in a friendly conversational style

---

## 🛠 Technologies Used

- **Python 3**  
- **OpenAI API (gpt-3.5-turbo)**  
- **Dotenv** for securely loading API keys  
- **Panel** for building a minimal chat GUI  
- **Jupyter Notebook** for interactive development  

---

##  How to Run

1. Install dependencies:
   ```bash
   pip install openai python-dotenv panel
    ```
2. Create a .env file in the root directory with your API key:
   ```bash
    OPENAI_API_KEY=your_openai_key_here
    ```
3. Launch the notebook:
   ```bash
   jupyter notebook l8-chatbot.ipynb
    ```

##  Concepts Practiced
- Prompt formatting with roles (system, user, assistant)
- Context accumulation for multi-turn memory simulation
- Temperature tuning for output control
- Panel-based user input/output interfaces
- Developing a chatbot persona using system prompts