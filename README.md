# english-learning-chatbot
BOTO is a conversational AI bot designed to help users improve their English. It evaluates sentences, provides a percentage rating for correctness, suggests improvements, and offers engaging responses. BOTO aims to be a friendly assistant that helps users learn English in a fun and interactive way.

Features
Correctness Evaluation: Rates the accuracy of each sentence.
Suggestions for Improvement: Provides corrected sentences.
Engaging Responses: Responds naturally to keep conversations lively and educational.
Few-Shot Prompting: Guided by examples to maintain consistent responses.
How It Works
BOTO leverages Google’s Generative AI API to process user inputs and generate responses that help users with English sentence correction. The model is pre-configured with few-shot examples to demonstrate the expected input-output pattern, making it capable of understanding and responding accurately.
Prerequisites
Python 3.6 or higher
A Google Cloud account with access to the Google Generative AI API
API key for the Google Generative AI API
Example Interaction :
You: HALO IM BATBOT WHIT IST YAR NAM
BOTO: Your sentence is approximately 40% correct. A more accurate way to phrase it would be: "Hello, I'm Batbot. What is your name?"

Hi Batbot, I'm BOTO! Nice to meet you!
You: nice to meet yo tou , haw ar yo dowing
BOTO: output: Your sentence is approximately 60% correct. A more accurate way to phrase it would be: "Nice to meet you too. How are you doing?"

Nice to meet you too!  I'm doing well, thank you for asking. How about you, Batbot?
You: im goud tank yo for ascing
BOTO: output: Your sentence is approximately 60% correct. A more accurate way to phrase it would be: "I'm good, thank you for asking."

I'm glad to hear it! Is there anything I can help you with today?
You: Haw iz may inglich 
BOTO: output: Your sentence is approximately 40% correct. A more accurate way to phrase it would be: "How is my English?"

Customization
Few-Shot Prompting: Modify prompt_template in code to adjust example sentences, improving BOTO’s ability to understand specific correction patterns.
Conversation Context: Customize the initial instructions to tailor BOTO’s tone or response structure.
Contributing
Contributions are welcome! If you’d like to improve BOTO’s features or add new functionality, please submit a pull request or create an issue.
