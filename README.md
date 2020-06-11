# NEO – AI Conversational Agents with personality
#Model file is to bi to be uploaded on github.(outside the range of github filesize limit)
A conversational expert for chit-chat, having its conversation consistent with its persona.

Absence of consistency in a conversational agent has been a long-standing problem. Conversation consistency is very important if a conversational agent wants to build trust and long-term confidence. Personality in a key differentiator in a conversational agent. We have worked on improving the conversation consistency of the agent according to its persona.

 We trained the language model on movie subtitles data set with the use of word embedding and transfer learning techniques in Python. We used personality sentences, history of conversation as the input context to the language model. We have used a next step prediction loss and language model loss and added them together. After fine-tuning the model on our dataset. The model was able to predict the next sentence tokens.

We have used the top-k and top-p sampling as a decoder mechanism. Top k sampling keeps the token that fall in certain range of probability and discard other tokens. It helps the model from going of topic. Trained dialogue model is able to learn its personality and capture the context of the dialogue.


