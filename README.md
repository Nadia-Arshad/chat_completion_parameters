# chat_completion_parameters
Explanation of the Parameters used in OpenAI Chat Completion system

**Documentation:**

* [Link to Google Doc](https://docs.google.com/document/d/1R-uhQqzy04WLlusZQfNOkms8Ex6gOwtHrCzqJdjG774/edit?usp=sharing)

**Parameters Used in Open AI Chat Completion API:**

Our purpose is to get the best possible answers for our queries. Chat Completion parameters are like little knobs that we can tweak to control how the model responds.

**Messages/Prompts:**

This is a question you ask from the model. 
Or it can be the instructions you give it to get the desired response. 
To get the best response, your message or prompt needs to be clear and specific.

**Model:** 

There are different versions and types of models out there. We specify a model based on our requirements. Our decision can be based on  multiple factors, for example: 

Different models have different strengths and weaknesses, and choosing the right one can significantly improve the quality and relevance of our model. 

Model’s Capabilities:

Language Understanding: Some models are better at understanding complex queries and providing informative responses.
Text Generation: Other models are good at generating creative text like poems, scripts, code etc.
Factual Accuracy: Some models are well-tuned at providing up-to-date information. 
Speech Recognition Models: There are models which are specifically designed to excel at speech related tasks. 
Image Models: These models are trained on massive datasets of images and can be used for generating images or videos at the stroke of a prompt. 

Model’s Size and Complexity:

Larger Models: These models often create sophisticated and nuanced responses but they require more computational resources hence are expensive. 
Smaller Models: They are less expensive and likewise less capable but are best for a number of basic level tasks. 
For example: For Customer Support tasks you would prefer to have a model with more accuracy. On the contrary a regular writing task can aptly be done by a smaller model. 

It is crucial to select the right model to help you get the best outcome eventually. 

**Max Completion Tokens:**

What are tokens?

Models divide text into small parts to process it. These small units of text are called tokens. 

Max Completion tokens is a fancy term to say how much would be the word limit of our required response.

This way you get a very brief, to the point and precise answer where needed. 

**n:** 

Let’s say n stands for numbers. This is the number of times we want a model to print a response. 

We use “n” when we need a couple of outputs for one prompt. 

**Stream:**

Stream is used when we are looking for an answer in chunks or in pieces. For example we want our model to write a poem but write it as if you can see it written by a type-writer or like a fax when received on the other end. 

What are its uses:

Real-time Responses: Stream helps to get an interactive and engaging experience. 
More time to think for the model hence improved response. 
Dynamic Applications: Used in live-chatbots and real-time translators. 

**Temperature:**

You set the temperature, you set the mood!

This really is a marker to specify how creative you want your model’s response to be. 

The higher the temperature the more creative, out of the box response. The lower the temperature the more run of the mill tone of the response. 

It’s a very useful feature to have a model respond differently for one question asked. And the ability to set its boundaries and play around with its imaginative and creative powers is amazing. 

**Top_p:**

Top_p more or less works like the temperature. It also controls the creative powers of the model. 

The higher the top_p, the higher number of words will be used by the model. It will give you more diversity in its response. Which is excellent when you are looking for more unconventional or innovative output. 

**Tools:**

It is thought to be the best strategy for our models to keep on learning and keep on improving themselves to better assist humanity. 

Tools are used to allow the AI to use external tools or knowledge bases to improve its responses.

For instance, you give a robot an access to a calculator or a library to use as reference and then respond. 



