# PythonAIAgentFromScratch

This code creates a agents and includes the following tools - wikipedia search, duckduckgo search and writes the output to the file.

Steps
1. Define the LLM - llm = ChatAnthropic(model="claude-3-5-sonnet-20241022")
2. Create the output parser.
3. Create the ChatPrompt template.
4. Create the agent - the agent takes the following input - llm, prompttemplate, tools(wiki, duckduckgo search)
5. Define the Agentexecutor
6. Invoke the agentexecutor.
