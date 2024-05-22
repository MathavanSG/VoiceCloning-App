# VoiceCloning-App

Welcome to the VoiceCloning-App repository! This project enables you to clone voices using state-of-the-art machine learning models.



### Prerequisites

- Python 3.9  or strictly below 3.11
- [Git](https://git-scm.com/)
- [Virtualenv](https://virtualenv.pypa.io/)

### Steps

1. **Clone the Repository**

    ```bash
    git clone https://github.com/MathavanSG/VoiceCloning-App.git
    cd VoiceCloning-App
    ```

2. **Set Up a Virtual Environment**

    ```bash
    python -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

3. **Install the Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Download Embeddings**

    Due to a known bug, you must download the embeddings directly from Hugging Face. Please follow these instructions strictly to avoid errors:

    - Go to the [Hugging Face Embeddings](https://huggingface.co/) page.
    - Download the necessary embedding files.
    - Place the downloaded embedding files in the `bark` directory.

5. **Clone the Bark Repository**

    Ensure you maintain the folder hierarchy strictly:

    ```bash
    git clone https://github.com/suno-ai/bark.git
    ```

    Place the cloned `bark` directory within the `VoiceCloning-App` directory.

## Usage

1. **Activate the Virtual Environment**

    ```bash
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

2. **Run the Application**

    ```bash
    streamlit run app.py
    ```

    Follow the instructions in the Streamlit app to input the text you want to convert to speech.

## Folder Structure

To avoid errors, please maintain the following folder structure:
Bark_voices/speaker or in app.py--> Temp/Speaker
