# FAQ

## 1. How does the agent handle missing data or incomplete code?

The agent focuses only on what it finds in your code. If certain metrics or information are not available, it simply omits them from the documentation. It never comments on missing data or generates speculative content. The output is based strictly on your actual source code.

## 2. Can I customize the documentation output?

Yes. The agent uses a RAG (Retrieval-Augmented Generation) framework file that contains the instructions for what sections to generate and how to format them. You can provide your own framework file via the --framework-file parameter, allowing you to customize the structure, content, and style of the generated documentation to match your organization's standards.

## 3. What are the prerequisites to run Agent Technical Writer?

You need:

Python 3.9 or higher

LLM API key

Your source code organized in a project folder
