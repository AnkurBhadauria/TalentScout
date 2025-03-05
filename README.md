Usage Guide
How to Use the Chatbot
Start the Chatbot:

The chatbot will greet you and ask for your full name.

Follow the prompts to provide your email, phone number, years of experience, desired position, current location, and tech stack.

Tech Stack Declaration:

Specify your tech stack (e.g., Python, React, Java, etc.).

The chatbot will generate 3-5 technical questions based on your tech stack.

Answer Technical Questions:

Respond to the technical questions generated by the chatbot.

Once all questions are answered, the chatbot will conclude the interview and thank you.

End Conversation:

The chatbot will gracefully end the conversation and inform you about the next steps.

Technical Details
Libraries & Tools
Streamlit: Used for developing the frontend interface.

Google Generative AI: Used for generating responses and technical questions.

Regex: Used for validating email, phone number, and other inputs.

Model Used
Gemini 2.0 Flash: A pre-trained language model by Google, used for generating responses and technical questions.

Prompt Design
Information Gathering Prompts:

The chatbot uses structured prompts to gather candidate information (e.g., name, email, phone number, etc.).

Example: "What is your full name?", "What is your email address?"

Technical Question Generation Prompts:

The chatbot generates technical questions based on the candidate's tech stack.

Example: "Generate a technical interview question about Python."

Fallback Mechanism:

If the chatbot does not understand the input, it provides a meaningful response like: "I'm sorry, I didn't understand that. Please provide the requested information."

Data Handling
Simulated Data
The chatbot uses simulated or anonymized data for backend processes, such as storing candidate information and technical responses.

Data Privacy
All candidate data is handled in compliance with data privacy standards (e.g., GDPR).

Sensitive information (e.g., email, phone number) is not stored permanently and is only used during the conversation.

Challenges & Solutions
Challenges Faced
Maintaining Conversation Context:

Ensuring the chatbot remembers the candidate's previous inputs and maintains a coherent flow.

Solution: Used session state in Streamlit to store and manage conversation context.

Generating Relevant Technical Questions:

Ensuring the technical questions are relevant to the candidate's tech stack.

Solution: Designed prompts that dynamically generate questions based on the candidate's specified tech stack.

Handling Unexpected Inputs:

Providing meaningful responses when the chatbot does not understand the input.

Solution: Implemented a fallback mechanism to handle unexpected inputs gracefully.

Optional Enhancements (Bonus Features)
Sentiment Analysis: Integrate sentiment analysis to gauge the candidate's emotions during the conversation.

Multilingual Support: Add support for multiple languages to interact with candidates in their preferred language.

Cloud Deployment: Deploy the chatbot on a cloud platform (e.g., AWS, GCP) and provide a live demo link.

Documentation
Project Overview: This README file provides a detailed overview of the project.

Installation Instructions: Step-by-step guide to set up and run the application.

Usage Guide: Instructions on how to interact with the chatbot.

Technical Details: Information about the libraries, tools, and model used.

Prompt Design: Explanation of how prompts were crafted for information gathering and technical question generation.

Challenges & Solutions: Discussion of challenges faced during development and how they were addressed.