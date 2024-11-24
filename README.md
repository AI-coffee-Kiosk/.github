# Ai-Driven Voice Recognition Kiosk For Cafe Orders

## 🚀 **Overview**
This organisation showcases the development of an innovative **voice recognition kiosk application** using the **LLaMA model**. Designed to provide a seamless, inclusive, and efficient customer experience, this application leverages advanced conversational AI to handle diverse user commands, including complex and consecutive orders, in real time.

---

## 📝 **Table of Contents**
1. [Introduction](#introduction)
2. [Features](#features)
3. [Architecture](#architecture)
4. [Dataset and Training](#dataset-and-training)
5. [Fine-Tuning and Model Training](#fine-tuning-and-model-training)
6. [Results and Performance](#results-and-performance)
7. [Future Work](#future-work)
8. [Getting Started](#getting-started)
9. [Acknowledgments](#acknowledgments)

---

## 🔍 **Introduction**
The kiosk application utilizes **LLaMA**, a cutting-edge large language model, to enable touch-free, voice-based interactions. By focusing on natural language understanding and real-time response generation, this kiosk is designed to:
- **Enhance user experience** with accurate and context-aware responses.
- **Support accessibility** for elderly and visually impaired users.
- **Streamline operations** in high-demand environments like cafes and retail spaces.

---

## ✨ **Features**
- **Voice-to-Text Conversion**: Real-time processing of spoken commands into actionable text.
- **Natural Language Understanding**: Handles nuanced and context-rich inputs.
- **Dynamic Response Generation**: Generates appropriate responses tailored to user requests.
- **Multilingual Support**: Supports diverse linguistic inputs for global usability.
- **Scalability**: Adaptable to various environments, including cafes, retail stores, and service centers.

---

## 🛠 **Architecture**
### **Core Components**:
1. **Speech-to-Text (STT)**: Converts user speech into text for processing.
2. **Natural Language Understanding (NLU)**: Processes input text, extracting intent and contextual details.
3. **Response Generation**: Formulates responses using the fine-tuned LLaMA model.
4. **Text-to-Speech (TTS)**: Delivers responses as audio for a seamless user experience.

### **Diagram**:
![종간발표2_page-0010](https://github.com/user-attachments/assets/9cd5d349-fb73-4be1-aa77-da69a25212ef)

---

## 📂 **Dataset and Training**
### **Data Preparation**:
- Compiled **4,500+ dialogue scenarios** spanning simple, complex, and consecutive orders.
- Structured data to include diverse inputs, ensuring coverage of real-world scenarios.

### **Training Tools**:
- **Platforms**: Hugging Face, Google Colab.
- **Frameworks**: Python, OpenAI APIs.

### **Prompt Engineering**:
- **Short Prompts**: Prioritized processing speed.
- **Long Prompts**: Optimized for context retention and accuracy.

---

## 🎯 **Fine-Tuning and Model Training**
- Leveraged **LLaMA’s pre-trained models** for fine-tuning using custom datasets.
- Iterative testing to reduce training loss and optimize for real-world scenarios.
- Adjusted hyperparameters to achieve a balance between speed and contextual accuracy.

---

## 📊 **Results and Performance**
- Achieved **high accuracy (90%+)** in handling complex and consecutive orders.
- Demonstrated:
  - **Low error rates**.
  - **Faster response times** with short prompts.
  - **Better context retention** with long prompts.
- Validated model performance using LM Studio and other benchmarking tools.

---

## 🔮 **Future Work**
1. **Enhanced Model Fine-Tuning**: 
   - Expand training datasets to cover additional scenarios.
   - Optimize for lower-resource environments.
2. **Integration and Deployment**:
   - Develop user-friendly interfaces for real-world implementation.
   - Deploy in various high-demand environments for live testing and feedback.

---

## 🛠 **Getting Started**
### **Prerequisites**:
- Install Python 3.8+.
- Install dependencies.

### **Setup**:
1. Clone the repository:
   ```bash
   git clone https://github.com/[YourOrg]/kiosk-llama.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

---

## 🙏 **Acknowledgments**
This project was made possible by:
- The **Dream Idea Soft Team** for technical support and collaboration.
- The **Kyungpook National University** research community for their guidance.
- All contributors who supported the development and testing phases.

---

This README provides a professional and detailed overview while maintaining a focus on the **LLaMA-powered kiosk application**. Let me know if you'd like further tweaks!
