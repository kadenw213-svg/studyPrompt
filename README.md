**About**

Rule-driven prompt framework for controlled tutoring: scoped knowledge hierarchy, drift-resistant grading, multi-mode delivery (Q&A, simulation, 
synthesis), internal state tracking, and serialized context export for session persistence.

While the prompt is designed to be capable of handling mutliple subjects in the same context file, it is reccomended to separate subject context 
files in order to minimize drift and keep the context window managable. The optimal structutre would be to create a folder or project for studying 
and make a separate chat, each with the prompt, for each major subject or area of study.

Paste the prompt into an empty chat in order to startup the prompt, and it full futher instruct the user on what further steps to perform.

Study session data will use a Google Drive connector to automatically save responses to keep persistent memory across chats. This is important because
due to the quantity of infomration the chat is processing, response quality will degrade without regular refreshing of the chat due to context
pollution.

**Dependencies**

Google Drive Connector
