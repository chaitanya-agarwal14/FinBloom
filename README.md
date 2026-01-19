# FinBloom: Knowledge Grounding Large Langage Model with Real-Time Financial Data

Finbloom is a retrieval-augmented framework that empowers Large Language Models to provide accurate answers to diverse financial queries by dynamically sourcing and integrating relevant real-time financial data.

## Features

- **Financial Context Dataset**: The Financial Context Dataset is a custom-built collection of over 50,000 natural language user queries mapped to structured data requirements for seamless retrieval via data modules. Developed through a combination of direct retail customer interactions across digital channels and expert consultations with financial advisors and investors, this comprehensive dataset bridges the gap between complex financial inquiries and actionable data structures. The dataset and more details about it can be found at the [kaggle page](https://www.kaggle.com/datasets/ankurzing/financial-context-dataset) for the dataset.

- **FinBloom 7B LLM**: FinBloom 7B is an open-source Large Language Model optimized for downstream financial tasks, developed by fine-tuning the BLOOM-7B architecture on an extensive dataset of historical Reuters and DPA financial news articles alongside years of SEC filings. Designed for high-precision financial analysis, the model is publicly available for integration and experimentation via its [Hugging Face link](https://huggingface.co/Chaitanya14/FinBloom_7B).
