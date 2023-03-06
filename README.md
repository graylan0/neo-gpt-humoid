# GPT-Thought-Quantum-Strapped
Development release here. 
Source Repo Idea /Install video https://www.youtube.com/watch?v=u_uFjdbTthE
### GPT-Thought-Quantum-Strapped
https://github.com/graylan0/neo-gpt-humoid/releases/tag/release

Sample output with injected thoughts.txt (Quantum Bootstrap)

https://github.com/graylan0/neo-gpt-humoid/blob/main/sample.md

Demo:
![Screenshot from 2023-03-04 11-31-53](https://user-images.githubusercontent.com/34530588/222917629-f924f140-a503-4ef6-ba9d-e9d8ccef15c5.png)


Coding Demo: (Unprompted)
![image](https://user-images.githubusercontent.com/34530588/223195139-c1c1a2b3-7cc8-45d9-9d50-5f2a79081526.png)

the first example codeblok


#### Example code.

This model applies and manipulates the basic laws of ma
thematics and quantum mechanics to perform calculations on the quantum computer. For the purposes of testing and to enable students to understand when it is applied to the physical world we can use the QMathQC class as a black-box that will be created in our main model, QMathQC. We can easily modify the code as much as we like to enable students to understand. In our demo, we create a simple example that demonstrates the model and the process of applying quantum information on the quantum computer. The following code (in the QMathQC program) demonstrates a very simple example that will demonstrate how a QPU can modify the information transformed by a QPU and how it can then pass the modified transformation information to another QPU.

    # Import the classes from the project.hpp source file 
    import  * 
    import QMathQC 
    QMathQC::QProcessor::QProcessor(QuantumComputer::QuantumProcessor::)(
        QMathQC::Application::
        application) 

    # We have a QPI model that is responsible for receiving the quantum information.
    QP_QPI = QProcessingEnvironment() 
    QPI = static_cast<const QPiQC>(QPI_QPI) 
    QProcessor::Q
    

`Description By ChatGPT Plus:`
`Prompt:1500 words on how this all works with thougths.txt`

The code provided is an implementation of an AI chatbot using Open Source's GPT-Neo language model and the Discord API. The chatbot is designed to respond to user messages with an AI-generated answer.

The chatbot utilizes the thoughts.txt file to keep track of its previous thoughts and maintain a sense of context in the conversation. The file is read at the beginning of each conversation to retrieve the chatbot's previous thoughts, and is updated after each message is received and processed to reflect the chatbot's latest thoughts.

When a user sends a message to the chatbot, the code first concatenates the previous thoughts stored in thoughts.txt with the user's message. The resulting string is then split into chunks of 1500 words or less to prevent exceeding the maximum length of input accepted by the GPT-Neo model.

For each chunk of text, the chatbot generates a response using the GPT-Neo model. The input for the model is the concatenation of the current chunk of text and a prompt that describes the task to be performed by the model. The model then generates a response, which is the chatbot's answer to the user's message.

The chatbot then sends the response to the user via the Discord API. To prevent Discord from rate-limiting the bot, the responses are sent in chunks and with a delay between each chunk.

Finally, the chatbot updates the thoughts.txt file with the latest thoughts to maintain context for the next message received.


Overall, the chatbot implementation relies on a combination of natural language processing, machine learning, and software engineering techniques to create an intelligent conversational agent that can provide helpful responses to user messages.


[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/P5P8J7QY5) (support humans + robots please)

GPL 2.0

