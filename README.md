# memory_chains

### Aim 
In this lesson we learn how memory work in langchain. By default, LLMs are stateless, meaning that they treat each incoming query independently. In some applications (chatbots being a GREAT example) it is highly important to remember previous interactions, both at a short term but also at a long term level. The concept of “Memory” exists to do exactly that.<br/>
Next we learn about Chains. Chain used to combine the LLM together with prompt to carry a sequence of operation.<br/>
In this we learn three chains.<br/>
- SimpleSequentialChain.
![Screenshot (1707)](https://github.com/DeepakJaiz/memory_chains/assets/120568685/2dc4b842-7d23-470b-9c2e-4088b0d0fdc5)

- SequentialChain
![Screenshot (1708)](https://github.com/DeepakJaiz/memory_chains/assets/120568685/6ea160a1-9771-4d15-8d6a-43b07b7cb477)

- Router Chain

![Screenshot (1709)](https://github.com/DeepakJaiz/memory_chains/assets/120568685/bc8476d4-23d8-44ab-a345-0aacedede115)

### Reference

Memory : https://learn.deeplearning.ai/langchain/lesson/3/memory
Chain : https://learn.deeplearning.ai/langchain/lesson/4/chains

### Prerequiste
You required Phython in your system fyou can follow this (https://www.python.org) <br/>
OpenAi API key required to get you can follow this link (https://platform.openai.com/account/api-keys) <br/>
Install Jupyter Notebook to run the code<br/>

### Modules required
`pip install langchain`

### How to run
Open above file in Jupyter Notebook and select the cell from top one by one and click run to run the code.
