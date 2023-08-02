# Abstractive Conversation Summarizer With Open Source AI Tools (ACSWOSAT)
ACSWOSAT is an AI-powered text summarization tool designed for law enforcement officers and departments in the Impact Intell industry. 
The tool analyzes text conversations from a database, generates brief summaries, and integrates into a Python Django web server. 
It enables users to communicate efficiently across cases and agencies, combatting criminals' use of information silos to evade law enforcement. 
The tool's algorithm is designed to mimic human-like summaries and can retrieve text conversations based on a user's specified date range.
The tool will be based on open-source machine learning libraries and will be implemented on the client's Python Django based web server.

# Intended Users : 
The intended users of ACSWOSAT are Impact Intell’s users, importantly law enforcement officers and departments who need to summarize text conversations to communicate efficiently across cases and agencies.
The AI-powered tool analyzes text conversations from a database, generates brief summaries, and integrates into a Python Django web server. 
The tool aims to combat criminals using information silos to evade law enforcement by facilitating better communication across agencies. 

# Working : 
ACSWOSAT is a machine learning transformer model that has been trained to summarize text conversations in a manner similar to how humans summarize information. 
The model takes input in the form of text conversations, which are fed into the system as a sequence of tokens. 
The model then processes these tokens using multi-head attention mechanisms, which help it to identify the key information in the conversation. 
The output of the model is a summary of the conversation, which is generated using a decoder network that has been trained to produce a compressed representation of the input. 
This model has been integrated into the web application of the client, allowing users to easily access and utilize the summarization functionality.

# Deployment & set-up procedures : 
The application exists on a development server branch and must be merged with the live server branch for deployment. 
Configuration for end-users includes the creation of an interface on the front-end of the web application. 
