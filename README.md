# Neural-Bot
A neural network inspired architecture for Chatbots using NLP


Neural-Bot is a simple NLP based chatbot. It's architecture is similiar to neural networks, 
but not too much mathematics involved.

# Architecture of our bot

![Architecture of our chatbot](./neuralnets.png?raw=true "Architecture")

Each neuron in this network will be having knowledge on different domains.


# Structure of our dataset

Example structure of data is given below. Humans will be mostly talking about something, and
that something can be a noun. So our bot will be organizing his knowledge based on these noun keywords.
When human ask some question to bot, like what is an aeroplane, it will trigger all the neurons and will
findout an answer from its knowledge set. Finally the activation function in each neuron will decide
whether that neuron should trigger or not. If there is atleast one neuron with aeroplane as a keyword,
then it will check for an approximate match for the given question. And then it will return most matching response.

![Dataset structure of our chatbot](./data.png?raw=true "Dataset structure")


# Example Conversation

![Example conversation of our chatbot](./chatbot.png?raw=true "Dataset structure")
