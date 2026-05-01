Fine-Tuning a Small LLM for Tool Routing

Built a system to fine-tune a 1B parameter LLM (Llama 3.2) to perform accurate tool routing for customer queries, mapping user intent to structured API calls.

Created a custom dataset (~80 examples) for intent classification + JSON tool calling
Fine-tuned using LoRA (Unsloth) for efficient training on limited compute (~10 min on Colab)
Improved model performance from inconsistent outputs to 100% correct structured tool calls
Implemented evaluation pipelines to validate tool selection, parameters, and JSON format
Demonstrated strong generalization on unseen queries
