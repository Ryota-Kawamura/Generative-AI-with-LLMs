**1.** Which of the following are true in regards to Constitutional AI? Select all that apply.
- [x] Red Teaming is the process of eliciting undesirable responses by interacting with a model.
- [ ] For constitutional AI, it is necessary to provide human feedback to guide the revisions.
- [x] To obtain revised answers for possible harmful prompts, we need to go through a Critique and Revision process.
- [x] In Constitutional AI, we train a model to choose between different prompts.

**2.** What does the "Proximal" in Proximal Policy Optimization refer to?
- [ ] The algorithm's ability to handle proximal policies
- [ ] The algorithm's proximity to the optimal policy
- [ ] The use of a proximal gradient descent algorithm
- [x] The constraint that limits the distance between the new and old policy

**3.** "You can use an algorithm other than Proximal Policy Optimization to update the model weights during RLHF."

Is this true or false?
- [x] True
- [ ] False

**4.** In reinforcement learning, particularly with the Proximal Policy Optimization (PPO) algorithm, what is the role of KL-Divergence? Select all that apply.
- [x] KL divergence measures the difference between two probability distributions.
- [x] KL divergence is used to enforce a constraint that limits the extent of LLM weight updates.
- [ ] KL divergence encourages large updates to the LLM weights to increase differences from the original model.
- [ ] KL divergence is used to train the reward model by scoring the difference of the new completions from the original human-labeled ones.

**5.** Fill in the blanks: When fine-tuning a large language model with human feedback, the action that the agent (in this case the LLM) carries out is ________ and the action space is the _________.
- [x] Generating the next token, vocabulary of all tokens.
- [ ] Processing the prompt, context window.
- [ ] Calculating the probability distribution, the LLM model weights.
- [ ] Generating the next token, the context window

**6.** How does Retrieval Augmented Generation (RAG) enhance generation-based models?
- [ ] By applying reinforcement learning techniques to augment completions. 
- [x] By making external knowledge available to the model
- [ ] By increasing the training data size.
- [ ] By optimizing model architecture to generate factual completions.

**7.** How can incorporating information retrieval techniques improve your LLM application? Select all that apply.
- [x] Overcome Knowledge Cut-offs
- [ ] Faster training speed when compared to traditional models
- [ ] Reduced memory footprint for the model
- [x] Improve relevance and accuracy of responses

**8.** What is a correct definition of Program-aided Language (PAL) models?
- [x] Models that offload computational tasks to other programs.
- [ ] Models that integrate language translation and coding functionalities.
- [ ] Models that assist programmers in writing code through natural language interfaces.
- [ ] Models that enable automatic translation of programming languages to human languages.

**9.** Which of the following best describes the primary focus of ReAct?
- [ ] Investigating reasoning abilities in LLMs through chain-of-thought prompting.
- [ ] Studying the separate topics of reasoning and acting in LLMs.
- [ ] Exploring action plan generation in LLMs.
- [x] Enhancing language understanding and decision making in LLMs.

**10.** What is the main purpose of the LangChain framework?
- [x] To chain together different components and create advanced use cases around LLMs, such as chatbots, Generative Question-Answering (GQA), and summarization.
- [ ] To evaluate the LLM's completions and provide fast prototyping and deployment capabilities.
- [ ] To connect with external APIs and datasets and offload computational tasks.
- [ ] To provide prompt templates, agents, and memory components for working with LLMs.
