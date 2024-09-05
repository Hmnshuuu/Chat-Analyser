# WhatsApp Chat Analyzer

![WhatsApp Chat Analyzer](https://img.shields.io/badge/Python-3.8+-green) ![Streamlit](https://img.shields.io/badge/Streamlit-App-red)

## Overview

The **WhatsApp Chat Analyzer** is a data analysis tool that provides insights into your WhatsApp chat history. By using this app, you can analyze the frequency of messages, identify popular words, URLs, and emojis used, and generate visual insights from any chat file.

This project is built using `Streamlit` and `Python` and leverages various libraries such as `regex`, `urlextract`, and `stopwords` to parse and analyze the chat data.

## Features

- **Message Frequency:** Analyze the frequency of messages sent by each participant.
- **Popular Words:** Identify the most commonly used words in the chat.
- **URL Analysis:** Extract and count the number of URLs shared in the chat.
- **Emoji Count:** Analyze the usage of emojis.
- **Visualizations:** Generate plots and graphs to visualize the data.

## Demo

![Chat Analyzer Demo](path/to/demo.gif)  <!-- You can add a GIF showcasing your app here -->

## Technologies Used

- **Python:** Main programming language.
- **Streamlit:** For building the interactive web app.
- **Regex:** For parsing chat text.
- **urlextract:** For extracting URLs.
- **Stopwords:** For filtering out common words from analysis.
- **Matplotlib/Seaborn:** For visualizations.

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Hmnshuuu/Chat-Analyser.git
    cd Chat-Analyser
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use `env\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

## Usage

1. Export your WhatsApp chat in `.txt` format from WhatsApp.
2. Upload the chat file into the app using the "Choose a WhatsApp chat text file" button.
3. Explore the various analyses such as message frequency, popular words, and more through the interactive interface.

## Future Improvements

- Add support for more languages beyond English.
- Implement sentiment analysis to gauge the mood of the chat.
- Include advanced analytics for media shared in the chat (images, videos, etc.).

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Author:** Himanshu Jangid  
*Feel free to check out my other projects on [GitHub](https://github.com/Hmnshuuu) or connect with me on [LinkedIn](https://www.linkedin.com/in/himanshuuu/)!*
