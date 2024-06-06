# Agri-Mitra

Agri-Mitra is a Q&A chatbot designed to assist with agricultural queries using the Google Gemini API. The application provides an interactive platform for users to input their questions and receive AI-generated responses.

## Features

- **Interactive UI**: Powered by Streamlit for real-time user interaction.
- **AI Responses**: Utilizes Google Gemini API to generate answers to user queries.

## Setup and Installation

### Prerequisites

- Python 3.7+
- Vercel CLI (for deployment)

### Installation

1. **Clone the repository**:

    ```sh
    git clone https://github.com/Suyash33/agri-mitra.git
    cd agri-mitra
    ```

2. **Create a virtual environment**:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**:

    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:

    Create a `.env` file in the root directory and add your Google API key:

    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

### Running the App Locally

To run the app locally, use the following command:

```sh
streamlit run app.py
