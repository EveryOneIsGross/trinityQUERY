# trinityQUERY

## Overview

trinityQUERY is a chatbot framework that aims to incorporate the principles of causality into chatbot interactions. By considering cause-effect relationships in user inputs and chatbot responses, TrinityQUERY strives to generate more relevant and contextually appropriate responses. With its unique 'v', 'confounder', and 'chain' structures, the system aims to facilitate richer responses. In essence, the term "trinity" encapsulates the triadic nature of the system's design and its three-pronged approach to chatbot interaction.

![DreamShaper_v6_trinity_from_the_matrix_as_a_pencil_sketch_show_0](https://github.com/EveryOneIsGross/trinityQUERY/assets/23621140/9b3e44d8-62d6-4641-8da7-dc0220625407)


## Features

- **Multiple Structures**: The system allows for the implementation of chatbots in different structures - 'v', 'confounder', and 'chain'. This feature enables the evaluation and comparison of chatbot performance in various scenarios and configurations.

- **Keyword Extraction**: The system employs the Rake algorithm to extract keywords from user queries and chatbot responses. This feature aids in assessing the chatbot's understanding and responsiveness to key concepts in a conversation.

- **Sentiment Analysis**: SentimentIntensityAnalyzer from NLTK is used to calculate sentiment scores of chatbot responses. This feature provides insight into the emotional tone of the chatbot's responses, which can be useful in evaluating the chatbot's ability to respond appropriately to the emotional context of a conversation.

- **Data Persistence**: All chat data is saved in a JSON file, providing a historical record of each chatbot's performance. This data can be used for trend analysis and performance evaluation over time.

- **Versatility**: While the system is designed to work with OpenAI's GPT-3 model, it can be adapted to work with other chatbot models, making it a versatile tool for evaluating a wide range of chatbots.

- **Scalability**: The system is capable of handling multiple chatbots simultaneously, making it a scalable solution for evaluating multiple chatbots in parallel.

- **Customizability**: The roles of the chatbots can be customized, allowing for a wide range of evaluation scenarios. This feature can assist in assessing how well a chatbot performs in different roles or contexts.

![KkmGiPAS](https://github.com/EveryOneIsGross/trinityQUERY/assets/23621140/869b11ad-24d0-4be4-8070-8871747ea421)


## Installation

1. Clone this repository.
2. Install the required Python packages using pip: `pip install -r requirements.txt`
3. Set up your OpenAI API key in a `.env` file.

## Usage

1. Run the script: `python trinity_query.py`
2. Enter your query when prompted.
3. Choose the roles for Chatbot A, B, and C.
4. Choose the chatbot structure ('v', 'confounder', or 'chain').

## Contributing

Contributions are welcome. Feel free to submit pull requests or open issues to discuss potential features or improvements.

## Disclaimer

This project is for educational purposes only. It does not claim to provide accurate predictions or outcomes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
