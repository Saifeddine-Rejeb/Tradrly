---
title: Human Like Agent
emoji: 🤖
colorFrom: pink
colorTo: yellow
sdk: gradio
sdk_version: 5.15.0
app_file: app.py
pinned: false
tags:
  - smolagents
  - agent
  - smolagent
  - tool
---

# Human Like Agent

## Challenge: Construire un modèle capable de reformuler la sortie d'un LLM pour la rendre plus "humaine" - Tardly

Human Like Agent is a project designed to simulate human-like interactions using advanced tools and frameworks. It leverages Gradio for its user interface and integrates various tools to enhance its functionality.

## Features

- 🤖 Human-like interaction capabilities.
- 🛠️ Integration with multiple tools for extended functionality.
- 🎨 Customizable UI with Gradio.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the application using the following command:

```bash
python app.py
```

Access the Gradio interface in your browser to interact with the agent.

## Project Structure

- `app.py`: Main application file.
- `Gradio_UI.py`: Contains the Gradio user interface logic.
- `prompts.yaml`: Configuration for prompts used by the agent.
- `tools/`: Directory containing additional tools for the agent.
- `requirements.txt`: List of dependencies required for the project.

## How It Works

Human Like Agent is designed to simulate human-like interactions by leveraging advanced tools and frameworks. Here's an overview of its functionality:

1. **Gradio Interface**: The project uses Gradio to create an interactive user interface. This allows users to interact with the agent in a seamless and user-friendly manner.

2. **Tool Integration**: The `tools` directory contains Python scripts that extend the agent's capabilities:

   - `final_answer.py`: Handles the generation of final responses.
   - `visit_webpage.py`: Enables the agent to visit and fetch content from web pages.
   - `web_search.py`: Allows the agent to perform web searches for additional information.

3. **Prompt Configuration**: The `prompts.yaml` file contains configurations for the prompts used by the agent. This ensures that the agent's responses are contextually relevant and aligned with its purpose.

4. **Backend Logic**: The main application logic is implemented in `app.py`, while the Gradio-specific UI logic is handled in `Gradio_UI.py`.

5. **Dependencies**: All required dependencies are listed in `requirements.txt`, making it easy to set up the project environment.

## References

Check out the [configuration reference](https://huggingface.co/docs/hub/spaces-config-reference) for more details on setting up your Gradio application.
