<div align="center">
<h1>Emojeez 💎</h1>
AI-powered semantic search engine for emojis in 50+ languages

<img src="./header_img.png" alt="An app for emojis" width="500"/>

[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/release/python-311/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![HF Dataset](https://img.shields.io/badge/%F0%9F%A4%97-datasets-yellow)](https://huggingface.co/datasets/badrex/llm-emoji-dataset)
[![Language](https://img.shields.io/badge/Language-Multilingual-red)](LANGUAGES)
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://emojeez.streamlit.app)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/badrex/emojeez/blob/main/notebooks/emoji_search_notebook.ipynb)


[![Share](https://img.shields.io/badge/share-000000?logo=x&logoColor=white)](https://x.com/intent/tweet?text=Check%20out%20this%20project%20on%20GitHub:%20https://github.com/badrex/emojeez%20%23OpenIDConnect%20%23Security%20%23Authentication)
[![Share](https://img.shields.io/badge/share-1877F2?logo=facebook&logoColor=white)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/badrex/emojeez)
[![Share](https://img.shields.io/badge/share-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/badrex/emojeez)
[![Share](https://img.shields.io/badge/share-FF4500?logo=reddit&logoColor=white)](https://www.reddit.com/submit?title=Check%20out%20this%20project%20on%20GitHub:%20https://github.com/badrex/emojeez)
[![Share](https://img.shields.io/badge/share-0088CC?logo=telegram&logoColor=white)](https://t.me/share/url?url=https://github.com/badrex/emojeez&text=Check%20out%20this%20project%20on%20GitHub)

Share Emojeez 💎 and star us on GitHub if you like it ⭐

[ <a href="https://medium.com/@badr.alabsi/semantic-search-for-emojis-in-50-languages-using-ai-f85a36a86f21">How does it work?  </a>  🚀 ]
</div>


## 📑 Description

Emojeez 💎 is an AI-powered semantic search engine, which is designed to help users discover and explore emojis. It was developed using advanced natural language processing (NLP) technologies to understand users' text queries and respond with relevant emojis. Emojeez 💎 features a multilingual support for more than 50 languages, enabling exploratory emoji search for users with diverse linguistic backgrounds. 

Try out Emojeez 💎 [here](https://emojeez.streamlit.app/).




## 🪄 Core Features

 - **Advanced Semantic Emoji Search** 🔎 Utilize our embedding-based search algorithm to find emojis that best match the intended meaning of short text queries. This utility is powered by the integration of [Qdrant](https://qdrant.tech/)'s vector database and the powerful Hugging Face 🤗 [Transformers](https://huggingface.co/docs/transformers/en/index) to build an efficient semantic search engine.

 - **LLM-Generated Emoji Descriptions** 🦜 Go beyond string matching search and experience the power of Large Language Models (LLMs) for better semantic search. Emojeez 💎 relies on enriched semantic descriptions generated by Meta AI's Llama-3-8B model. These descriptions not only define each emoji and its symbolism but also provide better contextualization of its usage in today's text-based communication. For more information, see this Hugging Face 🤗 [Dataset](https://huggingface.co/datasets/badrabdullah/llm-emoji-dataset). 

- **Efficient Indexing for Thousands of Emojis** ✨ Explore more than 5000 emojis based on the most recent Unicode standards. While each emoji is searchable by its standard Unicode name, you can also discover emojis by their meaning and how they are used by social media users today. For example, the text query *great ambition* returns 🚀, while *idea* returns 💡.

- **Comprehensive Multilingual Support** 🌐 Discover emojis using your native language! This feature is facilitated by a Transformer-based multilingual encoder that supports over 50 languages.

- **Intuitive User Interface** 🖥️ Interact with Emojeez 💎 via an intuitive user-friendly interface built with [Streamlit](https://streamlit.io/).


## 🌱 Getting Started

 To get a copy of the project up and running on your local machine for development and testing purposes, follow these instructions.

### Prerequisites

What you need to install the software:

- Python 3.11+
- Qdrant
- Sentence Transformers
- Streamlit


### Local Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/badrex/emojeez.git

2. Navigate to the project directory:

    ```bash
    cd emojeez

3. Install the required packages:

    ```bash
    pip install -r requirements.txt

4. Running the Application

    ```bash
    streamlit run search_emojis_app.py

## ℹ️ How to Use Emojeez 💎

After launching the app, you will see a text input where you can type your query. Enter a phrase or a keyword or a keyphrase, and the app will display emojis based on semantic similarity with your text input. The app use is optimized when the search query is a phrase or a full sentence.


### Examples 

Here, I provide a few exampels of text queries and the output of the search algorithm


<font size="4">

| Query | Top 10 Emojis |
|----------|----------|
| great ambition  | 🚀 ⚒ 💯 💸 🎯 🧗 🧗‍♂ 🧗🏽‍♂ 🏃‍♀️ 🧗🏾‍♂️  |
| innovative idea  | 💡 🥚 🧰 🧑‍💻 🚀 🧩 🛞 🌱 💭 🪤  |
| extinct species | 🦣 🦖 🦕 🦤 🦥 🏚️ 🇦🇶 🦛 🐧 🦏 |
| animal that builds dams | 🦫 🐃 🐏 🐐 🦬 🦦 🐂 🦛 🐺 🦙 |
| protect from evil eye | 🧿 👓 🥽 👁 🦹🏻 👀 🦹🏿 🛡️ 🦹🏼 🦹🏻‍♂ |
| popular sport in the USA | ⚾ 🏐 🏀 🏈 🥍 🏓 🏑 🤾‍♂ 🤾‍♂️ 🎾 |
| extraterrestrial | 👽 🛸 👾 👩🏼‍🚀 👩‍🚀 🧑‍🚀 👨‍🚀 👩🏽‍🚀 🧑🏻‍🚀 👩🏾‍🚀 |
| heart gesture with hand | 🫶🏽 🫶🏿 🫶🏾 🫶🏻 🫶🏼 💁🏼‍♂ 🙌🏽 🤟 🫶 🙌 |

</font>


## 🫶🏼 Contributions

If you would like to contribute to Emojeez 💎, I warmly welcome your contribution 😊 Start by forking the repository and then propose your changes through a pull request. Contributions of all kinds are welcome, from new features and bug fixes to development of test cases. Your input will be highly valued  🤝

## 🤙🏼 Get in Touch! 

Try out Emojeez 💎 in your language and let me know how you like it 😊

Developed with 💚 by [Badr Alabsi](https://badrex.github.io/) 👨🏻‍💻