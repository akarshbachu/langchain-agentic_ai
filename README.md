# LangChain - Agentic AI

Course: https://www.youtube.com/watch?v=rV3HJ4LEZ7k&t=28393s

## Steup
1. Install UV package manager (In Powershell execute this command): `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
2. uv init
    - This will create the gitignore, python version info, pyproject.toml
3. uv venv
    - This will create the virtual environment for the project at `.venv\Scripts\activate`
4. Activate vEnv
    - `.venv\Scripts\activate`
5. uv add -r requirements.txt

## API Keys
1. Google API Key: https://aistudio.google.com/app/api-keys?project=gen-lang-client-0348637965
    - Create API Key and place it in .env file "GOOGLE_API_KEY"
2. Groq API Key: https://console.groq.com/keys
    - Create API Key and place it in .env file "GROQ_API_KEY"
3. OpenAI API Key: https://platform.openai.com/api-keys
    - Create API Key and place it in .env file "OPENAI_API_KEY"