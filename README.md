# LangChain AI Elective homework

Welcome to the LangChain AI Elective homework repository! This repo contains all the code examples you'll need to follow along with the LangChain walk thru for Beginners. By the end of this walk thru, you'll know how to use LangChain to create your own AI agents, build RAG chatbots, and automate tasks with AI.

## Work Outline

1. **Setup Environment**
2. **Chat Models**
3. **Prompt Templates**
4. **Chains**
5. **RAG (Retrieval-Augmented Generation)**
6. **Agents & Tools**

## Getting Started

### Prerequisites

- Python 3.12
- Poetry (At the command prompt follow this [Poetry installation ]((Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python –) to install Poetry on your system)

### Installation

1. Clone the repository:

   ```bash
   <!-- TODO: UPDATE TO MY  -->
   git clone https://github.com/Devilfish281/ai_elective
   cd ai_electi
   ```

2. Install dependencies using Poetry:

   ```bash
   poetry install --no-root
   ```

3. Set up your environment variables:

   - Rename the `.env.example` file to `.env` and update the variables inside with your own values. Example:

   ```bash
   mv .env.example .env
   ```

4. Activate the Poetry shell to run the examples:

   ```bash
   poetry shell
   ```

5. Run the code examples:

   ```bash
    python 1_chat_models/44_chat_model_conversation_with_user.py
    python 1(TAB)
    python 1_chat_models 44(TAB)
    python 1_chat_models/44_chat_model_conversation_with_user.py
   ```

## Repository Structure

Here's a breakdown of the folders and what you'll find in each:

### 1. Chat Models


- `44_chat_model_conversation_with_user.py`


Learn how to interact with models like ChatGPT, Claude, and Gemini.


## How to Use This Repository

1. **Run the Code Examples:** Follow along with the code examples provided in this repository. 

2. **Join the Community:** 

## Comprehensive Documentation

Each script in this repository contains detailed comments explaining the purpose and functionality of the code. This will help you understand the flow and logic behind each example.

## FAQ

**Q: What is LangChain?**  
A: LangChain is a framework designed to simplify the process of building applications that utilize language models.

**Q: How do I set up my environment?**  
A: Follow the instructions in the "Getting Started" section above. Ensure you have Python  3.12 installed, install Poetry, clone the repository, install dependencies, rename the `.env.example` file to `.env`, and activate the Poetry shell.

**Q: I am getting an error when running the examples. What should I do?**  
A: Ensure all dependencies are installed correctly and your environment variables are set up properly. If the issue persists, open an issue on GitHub.

**Q: Can I contribute to this repository?**  
A: Yes! Contributions are welcome. Please open an issue or submit a pull request with your changes.

**Q: Where can I find more information about LangChain?**  
A: Check out the official LangChain documentation .

## Support

If you encounter any issues or have questions, feel free to open an issue on GitHub or ask for help in school.

## License

This project is licensed under the MIT License.
