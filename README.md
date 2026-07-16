# NoiosoAI-Server
NoiosoAI-Server Is For NoiosoAI-Desktop. (WIP Work In Progress)

What Is This One? It Hosts A LLM Thats Compatible For Everything Like Control Device On HA (Stil Don't Know If I Should Include This) Search On Websites To Give Best Responds Or Info (if needed)

## Map For How It Works:
NoiosoAI (User NoiosoAI-Desktop): Sends chat prompts.
                          ▼
Server (LLM Noioso Ollama Host): Thinks and calls tools.
                          ▼
Python Agent Web Script: Generates tool JSON and runs commands.
                          ▼
Server (Executor): Runs OS commands and API requests.
  
Runs Everything On The Server For Example When Run A Command Like: "hey ai could you send a email to my friend "email" to say at what time should i be there?" LLM Responds And Executes A Agent Broswer Lightweight And Does The Task For You (this is an example im thinking how does the server have a login to your email it's kinda not safe)
