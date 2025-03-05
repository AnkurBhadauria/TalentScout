📌 Chatbot Usage Guide

🚀 How to Use the Chatbot

1️⃣ Start the Chatbot

The chatbot will greet you and ask for your full name.

Follow the prompts to provide:

📧 Email

📞 Phone Number

📅 Years of Experience

💼 Desired Position

📍 Current Location

🛠️ Tech Stack (e.g., Python, React, Java, etc.)

2️⃣ Tech Stack Declaration

Specify your primary technologies.

The chatbot will generate 3-5 technical questions based on your selection.

3️⃣ Answer Technical Questions

Respond to the generated technical questions.

Once all questions are answered, the chatbot will conclude the interview.

4️⃣ End Conversation

The chatbot will gracefully end the conversation and provide next steps.

⚙️ Technical Details

📚 Libraries & Tools

Streamlit – For developing the frontend interface.

Google Generative AI – For generating responses and technical questions.

Regex – For validating email, phone number, and other inputs.

🤖 Model Used

Gemini 2.0 Flash – A pre-trained language model by Google, used for response and question generation.

💡 Prompt Design

🔹 Information Gathering Prompts

The chatbot uses structured prompts to gather candidate information.

Examples:

"What is your full name?"

"What is your email address?"

🔹 Technical Question Generation

The chatbot generates relevant questions based on the tech stack.

Example: "Generate a technical interview question about Python."

🔹 Fallback Mechanism

If the chatbot does not understand the input, it provides a meaningful response:

❌ "I'm sorry, I didn't understand that. Please provide the requested information."

🔐 Data Handling & Privacy

🔹 Simulated Data

The chatbot uses simulated/anonymized data for backend processes.

🔹 Data Privacy Compliance

Follows GDPR & other privacy standards.

Sensitive data (email, phone number) is not stored permanently.

🛠️ Challenges & Solutions

🔹 Maintaining Conversation Context

Challenge: Ensuring the chatbot remembers previous inputs.

Solution: Implemented Session State in Streamlit to store and manage conversation flow.

🔹 Generating Relevant Questions

Challenge: Ensuring questions are tailored to the candidate's tech stack.

Solution: Designed dynamic prompt structures that generate precise questions.

🔹 Handling Unexpected Inputs

Challenge: Providing meaningful responses for unrecognized inputs.

Solution: Implemented a fallback mechanism to handle unexpected inputs gracefully.
