<h1>RAFT Fine Tuning</h1>

02_raft_datagen.ipynb is a copy of **1_raft_datagen.ipynb** in the **[RAFT repository](https://github.com/Azure-Samples/azure-openai-raft).**
<br><br>
RAFT uses the training dataset to provide thought process for getting to the answers.<br>
The structure of the training dataset is shown in Figure 1.<br>
<br>
<br>
![Data Structure](./streamlit/images/raft_dataStructure.png)
<br>
<br>
Since the generated training dataset does not include system prompts, we do not include them during inference either. Also, make sure that you don't include the log of function calls in the chat history, so keep the assistants separate. Figure 2
<br>
<br>
![Data Structure](./streamlit/images/raft_2assistants.png)
