# Autism_Companian_GenAi_Project_Kaggle

# Autism Companion

![Autism Companion Banner](./images/children-using-technology.jpg)

## 💡 Overview

Autism Companion is an AI-powered platform designed to support children with Autism Spectrum Disorder (ASD), their families, and therapists. Using advanced generative AI techniques, the platform creates personalized therapy materials, simulates social interactions, and adapts to each child's unique needs while maintaining privacy and ethical standards.

> "Every child deserves a voice, a safe space, and a story they can understand."

## 🧠 Key Features

### ✍️ Personalized Social Story Generator
- Creates custom stories tailored to a child's age, sensitivities, and specific needs
- Employs prompt engineering with large language models to generate safe, relevant content
- Helps children understand social situations through relatable narratives

### 🧬 Adaptive Learning System
- Utilizes Sentence-BERT embeddings and FAISS for efficient content matching
- Recommends relevant stories and activities based on past interactions
- Detects potential sensory triggers and avoids them in generated content

### 🤖 AI Peer Interaction Simulator
- Provides safe conversation practice using LangChain agents
- Adjusts complexity levels based on the child's responses
- Offers encouraging feedback in a low-pressure environment

### 🔐 Privacy-Preserving Architecture
- Implements LoRA (Low-Rank Adaptation) for fine-tuning models on anonymized data
- Complies with medical data privacy regulations
- Prioritizes data security throughout the platform

### 🛡️ Hallucination Detection
- Filters generated content for unrealistic, confusing, or unsafe elements
- Ensures outputs are appropriate and beneficial for therapy contexts
- Provides review mechanisms for flagged content

## 🚧 Current Limitations & Future Development

- **Expanding hallucination control** for complex emotional concepts
- **Improving synthetic training data** to better reflect real therapy scenarios
- **Edge deployment** for offline use in rural or connectivity-challenged areas
- **Voice-to-story features** for non-verbal children
- **LangGraph agents** for more sophisticated therapeutic simulations
- **Mobile application** with dual interfaces for caregivers and children
- **Localization** for diverse cultural and language contexts

## 💻 Installation and Setup

```bash
# Clone the repository
git clone https://github.com/yessasvini/autism-companion.git
cd autism-companion

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys and configuration

# Run the application
python app.py
```

## 🔧 Tech Stack

- **Language Models**: GPT-4, BERT
- **Vector Storage**: FAISS
- **Framework**: LangChain
- **Fine-tuning**: LoRA (PEFT)
- **Backend**: Python, Flask
- **Frontend**: React, Tailwind CSS

## 📊 Research Base

This project is built on evidence-based approaches to autism therapy, including:
- Social Stories™ methodology
- Visual schedules and supports
- Cognitive-behavioral techniques
- Sensory integration theory

## 🤝 Contributing

Contributions are welcome! Please check our [Contributing Guidelines](CONTRIBUTING.md) before submitting PRs.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ❤️ Acknowledgements

- Special thanks to the autism therapy community for guidance and feedback
- All the families and children who inspired this work
- Open-source AI community for tools and libraries that made this possible

## 📬 Contact

Sudarshanam Yessasvini - [yessasvini.s@gmail.com](mailto:yessasvini.s@gmail.com)  
Project Link: [https://github.com/yessasvini/autism-companion](https://github.com/yessasvini/autism-companion)
