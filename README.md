Agentic AI Notebook

A hands-on notebook exploring agentic AI patterns using Google's Gemini models through the OpenAI-compatible API. It progresses from basic API calls to a deployable CV chatbot with tool-calling and a self-evaluation loop.

What's inside?

1. Getting started with basics	Sets up the OpenAI client pointed at Gemini's OpenAI-compatible endpoint and makes a first call
2. Business sector → pain point → solution	Chains three LLM calls: pick a sector, identify a pain point, propose a solution
3. Math problem generator & checker	Generates a grade-8 word problem, solves it, then has a model verify the solution
4. Examiner/Student Q&A	Two role-played agents (examiner, student) go back and forth over several rounds
5. CV Chatbot	Loads a CV from PDF, builds a system prompt so the model answers as the CV's owner, and serves it via a Gradio chat UI
6. CV Chatbot + self-evaluation	Adds an evaluator agent that checks each reply before it's shown, and reruns the response if rejected
7. CV Chatbot + Pushover	Adds tool-calling so the agent can push notifications (e.g. record a visitor's contact details, log unanswered questions)
8. Deploying with Render	Step-by-step guide to take the chatbot from notebook to a live URL
