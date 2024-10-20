
# ResearchFlowAgent

A Python-based agentic workflow leveraging DSPy, Pydantic, OpenAI, and connected-papers-py to retrieve current research papers and their citation networks.

## Requirements

- **Conda** installed for managing environments
- **Python 3.9** or above

## Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/danilotpnta/ResearchFlowAgent.git
cd ResearchFlowAgent
```

### Step 2: Create and Activate the Conda Environment

To set up the environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
```

Once the environment is created, activate it with:

```bash
conda activate researchflow
```

### Step 3: Create a `.env` file

Create a `.env` file in the root directory for API keys and other environment variables:

```bash
OPENAI_API_KEY=your_openai_key_here
```

### Step 4: Run the App

To start the Streamlit app:

```bash
streamlit run app.py
```

This will start a local server for the app, and you can access it by visiting the URL printed in the terminal (usually http://localhost:8501/).


## License

This project is licensed under the MIT License. See the LICENSE file for more details.
