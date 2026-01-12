# MCP_Simulator-
This notebook demonstrates how to use the OpenRouter API for tool calling, specifically with a weather lookup example. It covers the following steps:

Tool Definition: Defining a get_current_weather function as a tool for the LLM.
User Question: Sending a user query that requires the tool.
LLM Tool Call: The LLM identifies and requests to call the get_current_weather tool with appropriate arguments.
Tool Execution: Simulating the execution of the tool (fetching weather data).
Result to LLM: Sending the tool's result back to the LLM.
Final Response: The LLM processes the tool's output and generates a natural language answer to the user's initial question.
This provides a clear example of how to integrate external functions or APIs with LLMs using tool calling.
