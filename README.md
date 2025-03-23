# GRASS GIS Sample Chatbot
# GRASS GIS Chatbot

## Project Overview
The **GRASS GIS Chatbot** is a chatbot designed to interact with users and help them with their geospatial analysis tasks using **GRASS GIS** commands. The chatbot utilizes a machine learning model trained on GRASS GIS documentation to understand user queries and provide relevant GRASS GIS commands.

This repository contains code for training the chatbot, using it with a web interface, and fine-tuning the model for better performance.

## Features
- **Natural Language Understanding**: The chatbot understands and processes user queries related to GRASS GIS.
- **Command Suggestion**: Based on the user's input, the chatbot provides the most relevant GRASS GIS commands and examples.
- **Lightweight Model**: The chatbot uses a small language model that can be deployed on edge devices for real-time responses.
- **Gradio Interface**: The project uses **Gradio** for building a simple web interface for easy interaction with the chatbot.

## Project Structure

- `chatbot.py`: Contains the main code for running the chatbot and integrating it with the Gradio interface.
- `train.py`: Code for training the model using the provided dataset.
- `dataset.py`: Contains the dataset used for training the model, including input-output pairs of GIS queries and corresponding GRASS GIS commands.
- `evaluate.py`: Used for evaluating the chatbot's performance.
- `requirements.txt`: A list of dependencies needed to run the project.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/grass-gis-chatbot.git
    cd grass-gis-chatbot
    ```

2. Set up a virtual environment (optional but recommended):

    ```bash
    python -m venv grass_gis_chatbot_env
    source grass_gis_chatbot_env/bin/activate  # On Windows use `grass_gis_chatbot_env\Scripts\activate`
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```


## Usage

1. **Run the chatbot**:
    To start the chatbot and test it with a web interface using Gradio, run:

    ```bash
    python chatbot.py
    ```

2. **Train the model**:
    To train the model using the dataset, run:

    ```bash
    python train.py
    ```

3. **Evaluate the model**:
    After training, you can evaluate the model's performance using:

    ```bash
    python evaluate.py
    ```

4. **Interact with the chatbot**:
    Open your browser and visit the Gradio interface (by default it runs on `http://localhost:7860`).

## Contributing

Feel free to fork this repository and submit pull requests. If you have any suggestions, bugs, or issues, please open an issue in the repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **GRASS GIS** for providing powerful geospatial tools.
- **Gradio** for building the user-friendly interface.
- **NLTK** for providing tools for natural language processing.

---

If you have any questions or need help with the project, feel free to reach out to me through [LinkedIn](https://www.linkedin.com/in/yourname).
