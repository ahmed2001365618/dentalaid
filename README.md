# DentalAId Chatbot - GitHub Repository

## Overview

This repository contains the implementation of **DentalAId**, a specialized chatbot developed to assist dental professionals in the clinical management of dental trauma in permanent teeth. The chatbot provides evidence-based recommendations, designed to enhance decision-making processes regarding diagnosis and prognosis.

### Key Features:
- **Language**: Python (developed using PyCharm 2023.2.3)
- **Integration**: Utilizes the OpenAI API (ChatGPT-4) for natural language processing.
- **Scope**: Provides clinical recommendations based on the 2020 guidelines from the International Association of Dental Traumatology (IADT).
- **Multilingual Support**: Supports over 50 languages, adapting to the user's input language.

## How it Works

### Chatbot Logic:
- **Dental Trauma Management**: The chatbot is designed to guide users through a series of targeted questions to identify the specific type of dental trauma and provide appropriate clinical recommendations.
- **Content**: All recommendations are derived from the IADT guidelines (2020), ensuring the chatbot provides accurate, up-to-date clinical advice.

### Interaction Management:
- The chatbot preserves conversation history using the `session_state` function in Python, allowing seamless interaction throughout the session.
- The `render_chat` function handles the flow of conversation, ensuring that user inputs are properly categorized and chatbot responses are contextually appropriate.

## References

- **International Association of Dental Traumatology Guidelines (2020)**: These guidelines serve as the foundation for the chatbot's clinical recommendations.
  - Reference articles include guidelines for dental trauma management in permanent teeth.
  
## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
