# Marketing Agent
This is a quick example of using tools, Genie, and LangGraph to make an Agent.

It builds off the Genie [multiagent documentation](https://docs.databricks.com/aws/en/generative-ai/agent-framework/multi-agent-genie) and the [CME Marketing Campaign demo](https://www.databricks.com/resources/demos/tutorials/aibi-genie-marketing-campaign-effectiveness), but tried to build a more realistic dataset for natural language work using Batch Inference, then uses that dataset as a creative tool for Vector search via a ReACT agent.

It is fully notebook based and broken down as follows:
- Dataset creation