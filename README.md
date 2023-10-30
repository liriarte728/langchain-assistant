# langchain-assistant: Analyze and Answer Questions on YouTube Videos 🎥🤖

## Overview

**langchain-assistant** is an advanced tool that answers questions about any YouTube video by delving deep into its transcript. Relying on OpenAI's `text-davinci-003` model and Streamlit, it effortlessly fetches, processes, and produces in-depth responses to user queries.

## Core Components

- 🔄 **YoutubeLoader**: Retrieves video transcripts using the provided YouTube URL.
- 📜 **RecursiveCharacterTextSplitter**: Divides the transcript into digestible segments for efficient processing.
- 🧠 **OpenAIEmbeddings & FAISS**: Generates embeddings of the transcript portions and commits them to a FAISS vector database.
- 🔗 **LLMChain**: Crafts a prompt and utilizes OpenAI's model to produce detailed answers.
- 🖥️ **Streamlit UI**: An intuitive interface where users can input YouTube video URLs and pose questions.

## Usage

Simply input the YouTube video URL and your question within the Streamlit interface. The system will delve into the video's transcript and present a comprehensive answer derived from its content.
