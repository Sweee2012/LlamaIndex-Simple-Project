# LlamaIndex-Simple-Project

**Starter Tutorial (Using Gemini API) For LlamaIndex:**

#Basic Agent Example (Source: LlamaIndex Docs)#

As a hands-on project, I followed a starter tutorial to build a simple yet functional AI agent using LlamaIndex with Gemini API. This agent was designed to solve math problems by calling a custom tool specifically for multiplication showcasing how to integrate tools and local models efficiently.

**What the Agent Can Do:**
•	Takes a user prompt like: "What is 1234 * 4567?"

•	Internally routes the query to a Python multiply (a, b) function.

•	Returns the correct computed answer, e.g., "The answer to 1234 * 4567 is: 5,618,916."

#AI Agent Using RAG Capabilities#

Using the LlamaIndex Starter Tutorial, I extended a basic function-agent by adding RAG capabilities enabling the AI assistant to solve math problems and answer natural language questions from documents.

**What the Agent Can Do:**
•	Respond to multi-part queries like:
"What did the author do in college? Also, what's 7 * 8?"

•	Routes the question to the right tool:
o	RAG for answering from the document.
o	Math tool for computation.

•	Returns combined, accurate, and context-aware responses.
