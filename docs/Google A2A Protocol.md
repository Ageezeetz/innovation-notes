**What is the Google A2A (Agent to Agent) Protocol?**
	- Open-source program for AI agents to efficiently connect and communicate tasks while maintaining user security.
	- Idea is to **combine multiple agents**, which are trained for specific tasks, **into an area** ("ecosystem) **they can all interact and communicate in** to produce fast, accurate information.
	1. **Very flexible**; allows communication between AI agents from different LLMs and coding languages, and standardizes APIs, message formats, and any information given.
	2. **Secure**; uses **encryption for all messages sent** between agents, **authentication checks** for agents, and **user consent** for information sharing
	3. Designed for **multitasking** (**scalability**, I think?); Works in conjunction with multiple AI agents at a time.
	  
**How it works:**
	1. Agents first connect, sharing authentication to ensure proper agent has been found.
	2. Primary agent breaks apart primary task (**find blue shorts for women over age 45**) into smaller details with no connection to user (**blue, shorts, women**) and sends the relevant parts to the specified agents.
	3. Agents return relevant information (Walmart Agent, Target Agent, Best Buy Agent) to primary agent.
	4. Primary agent compiles all information to then return prompt result to user.
	*Each agent only sees information relevant to **THEIR OWN PURPOSE***
	
**Google A2A Examples:**
	1. Adobe:
		- Using A2A to combine their own agents with Google's, allowing for access to Google elements and information while using Adobe agents.
		- Allows for more powerful digital experiences, better workflows, and improved automated system data integrations.
	2. S&P Global Market Intelligence:
		- Provider of information to global markets
		- Allows for better flexibility (allows for different systems and tools to work together), scalability (capable of increasing workload depending on usage from information from agents), and readiness for future changes.
	3. Twilio:
		- Uses A2A for Latency Aware Agent Selection
		- Ensures that when a user sends a request/query, the system chooses the agent with the least latency, allowing for faster responses.

Created 9.17.25