# CV4-project

Through the Rasa framework...
<br>
Aim is to build an advanced chatbot able to react to the mod detected from the computer's webcam. An obvious direction of improvements is Building a chatbot using natural language processing, machine learning, and dialog management. 
## Building a chatbot involves several components, including natural language processing, machine learning, and dialog management.

A breakdown of the key components and steps involved:<br>

## Natural Language Understanding (NLU):<br>
Train the chatbot to understand user inputs using NLU models. In Rasa, this typically involves creating training data in the form of intents (what the user wants) and entities (specific pieces of information within the input).
Use tools like Rasa NLU to train models that can recognize intents and entities accurately from user messages.
<br>
## Machine Learning:<br>
Utilize machine learning algorithms for intent classification and entity extraction. Rasa offers configurable machine learning pipelines for this purpose.
Train the ML models on the annotated data to improve accuracy in understanding user inputs.
<br>
## Dialog Management:<br>
Design the flow of the conversation using stories and rules. Stories represent example conversations between the user and the chatbot, while rules provide specific conditions for triggering certain responses.
Implement dialog management using Rasa Core, which predicts the next best action the chatbot should take based on the current state of the conversation.
Train the dialogue model using the stories and rules to enable the chatbot to handle conversations effectively.
<br>
## Integration with Webcam and Mood Detection:<br>
Integrate the chatbot with the computer's webcam to access real-time video feed.
Implement mood detection algorithms to analyze the video feed and determine the user's mood. This could involve computer vision techniques and machine learning models trained on labeled mood data.
Use the mood information as contextual input for the chatbot, influencing its responses and behavior.
<br>
## Response Generation:<br>
Based on the user input, mood detected, and current conversation context, generate appropriate responses using templates, custom logic, or even by querying external systems.
Train the response generation component to provide relevant and engaging responses across different moods and conversation scenarios.
<br>
## Testing and Iteration:<br>
Test the chatbot extensively to ensure it behaves as expected in various scenarios, including different user inputs and detected moods.
Iterate on the design and implementation based on feedback and performance metrics, continuously improving the chatbot's accuracy and user experience.
