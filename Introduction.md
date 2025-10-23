## Agentic AI

Agentic AI refers to an AI system that acts autonomously to achieve goals by making its own decisions and taking action, rather than just responding to human prompts or following predefined rules. 

Agentic AI development manages the interaction between uses , LLMs, backend functions, and data sources. 

Customer --> Text --> gives to LLM --> check weather and book tax --> LLM to rationalize --> 
- In order to check weather, which city ?
- Taxi : From and to location.

### Vertex AI

Use cases for AI Agents 
 - Data Science
 - Employee Productivity
 - Research
 - Developer

Build your own ( use function calling to build your own agent framework )
Low Level orchestraction framework : Langchain, GenKit
Agent - Specific framework ( balance of deterministic control and convenience ) -- smolagent, CrewAI, LangGraph, AG2/AutoGen
Solutions : AgentSpace and coversational Agents. 


### ADK allows to build mutli-agent system

                                |--------> Sub_agent
                                |--------> Sub_agent ........ Tool
                                |--------> Sub_agent
                              
 |root Agent ---> Sub Agent --> |

                                |--------> Sub_agent
                                |--------> Sub_agent ........ Tool
                                |--------> Sub_agent

Tool could a function, mathematcal calucation, or external API.

Run an agentic AI code from github or colab on your local and notice how adk interacts. 
The couple of example you main notice and the chatbot that companies develop
and ask what you need information with
- Account
- billing
  
once you say billing then billing subagent is called and handsover the function call there
- Lastest Bill
- Payment History
- Statements
  
Further you keep on going into subagent to perform action. 

These main_Agent can call the separate python file agent itself that is a whole agent in itslef. 
