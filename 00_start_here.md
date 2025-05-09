# Marketing Agent
This respository contains a walkthrough to make an agent using tools, Genie, and LangGraph.

It builds off the Genie [multiagent documentation](https://docs.databricks.com/aws/en/generative-ai/agent-framework/multi-agent-genie) and the [CME Marketing Campaign demo](https://www.databricks.com/resources/demos/tutorials/aibi-genie-marketing-campaign-effectiveness).

But it does a couple of extra things - first it builds a more realistic dataset using Batch Inference. It then leverages that new dataset to build a creative ReAct agent with Vector Search. We don't stop there - we also give the agent access to two tools - a simple UC function and a Genie Agent. We deploy this model and evaluate it using the Agent Evaluation framework.

## Running the repo
Follow the notebooks in the repo in order.