# OpenAI-Customized-Chatbot
This project focuses on developing a customized chatbot using OpenAI's pre-trained GPT models. The chatbot is designed to handle FAQs and provide relevant responses based on the input data. Originally designed for a B2B consulting company to provide expert responses based on the company's in-house domain knowledge, this project has been transformed for demonstration purposes to handle e-commerce customer service FAQ data.

## Project Overview
The goal of this project is to create a chatbot that can efficiently answer frequently asked questions (FAQs) by leveraging the capabilities of the GPT model. The project involves:
1. **Data Preprocessing:** Collecting data from various sources and transforming it into a unified structure that enhances training performance.
2. **Embedding Model:** Generating embeddings for the given data using OpenAI's API to enable question and answer functionality based on embedding search.
3. **Trained Chatbot with Customized Instruction:** Utilizing OpenAI's Chat Completion API with specified chatbot instructions.
4. **Testing Using Quantitative Models:** Evaluating the performance of the chatbot's responses using BLEU Score, ROUGE-1, ROUGE-2, ROUGE-L, and METEOR as testing score metrics.


## Project Overview:
This project is dedicated to developing a customized chatbot using OpenAI's pre-trained GPT models, specifically designed to handle customer service FAQs. Originally intended for a B2B consulting company to provide expert responses based on the company's in-house domain knowledge, this project has been repurposed for demonstration to manage e-commerce customer service FAQ data.


## Project Goals:
The primary goal of this project is to create a chatbot that can efficiently answer frequently asked questions (FAQs) by leveraging the capabilities of a Large Language Model (LLM). The project revolves around two main tasks:
#### 1. Quantitative Evaluation and Efficient Training Process:
* Objective: Enhance the training efficiency of the chatbot by mimicking the structure of the 3rd party chatbot system.
* Process: The 3rd party system only provides chatbot responses without quantitative evaluation metrics, making the training process extremely manual and biased. To improve training efficiency, this project emulates their model's structure and uses the METEOR score as the key evaluation metric. 

#### 2. Optimizing Data Input for 3rd Party Chatbot Systems:
* Objective: Improve the quality of data fed into the 3rd party chatbot system.
* Process: This project focuses on refining the input data by performing thorough data preprocessing, generating high-quality embeddings, and optimizing prompts. The ultimate goal is to ensure that the data provided to the 3rd party chatbot system is of the highest quality, leading to more accurate and relevant responses.


## Key Workflow:
![LLM agents flow](https://github.com/user-attachments/assets/b77a4613-a937-41a0-a349-03ccedb3f8a7)

1. **Data Preprocessing**: Collecting data from various sources and transforming it into a unified structure that enhances training performance.
2. **Embedding Model**: Generating embeddings for the given data using OpenAI's API to enable question and answer functionality based on embedding search.
3. **Trained Chatbot with Customized Instruction**: Utilizing OpenAI's Chat Completion API with specified chatbot instructions.
4. **Quantitative Testing & Evaluation**: Evaluate performance using quantitative metrics, focusing on the METEOR score due to its robustness in accounting for synonyms and paraphrasing, making it particularly suitable for natural language generation tasks.


## Outcome:
The result of this project is a well-optimized, efficient customer service chatbot ready to be integrated with a 3rd party chatbot system. The project’s process ensures that both the data and the chatbot's performance are refined to the highest standards, facilitating better customer interactions and streamlined training.

