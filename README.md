# family-intelligence-prototype
Frontend protoype of a conversational agent that helps families manage cross-system context across calendar, meals/groceries, and todos, and facilitates lower friction interaction with these systems via a single entry point.

Backend architecture will include an orchestration layer:
- intent classification (routing layer)
- LLM calls via API
- tool calls to read and write to each system
- guardrails for unstructured input and output quality 
