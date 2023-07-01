**1.** Fill in the blanks: __________ involves using many prompt-completion examples as the labeled training dataset to continue training the model by updating its weights.  This is different from _________ where you provide prompt-completion examples during inference.
- [ ] In-context learning, Instruction fine-tuning 
- [ ] Prompt engineering, Pre-training
- [ ] Pre-training, Instruction fine-tuning
- [x] Instruction fine-tuning, In-context learning

**2.** Fine-tuning a model on a single task can improve model performance specifically on that task; however, it can also degrade the performance of other tasks as a side effect. This phenomenon is known as:
- [ ] Catastrophic loss
- [x] Catastrophic forgetting
- [ ] Instruction bias
- [ ] Model toxicity

**3.** Which evaluation metric below focuses on precision in matching generated output to the reference text and is used for text translation?
- [ ] HELM
- [x] BLEU
- [ ] ROUGE-2
- [ ] ROUGE-1

**4.** Which of the following statements about multi-task finetuning is correct? Select all that apply:
- [ ] Performing multi-task finetuning may lead to slower inference.
- [x] Multi-task finetuning can help prevent catastrophic forgetting.
- [x] FLAN-T5 was trained with multi-task finetuning.
- [ ] Multi-task finetuning requires separate models for each task being performed.

**5.** "Smaller LLMs can struggle with one-shot and few-shot inference:"

Is this true or false?
- [x] True
- [ ] False

**6.** Which of the following are Parameter Efficient Fine-Tuning (PEFT) methods? Select all that apply.
- [x] Reparametrization
- [ ] Subtractive
- [x] Selective
- [x] Additive

**7.** Which of the following best describes how LoRA works?
- [x] LoRA decomposes weights into two smaller rank matrices and trains those instead of the full model weights.
- [ ] LoRA freezes all weights in the original model layers and introduces new components which are trained on new data.
- [ ] LoRA trains  a smaller, distilled version of the pre-trained LLM to reduce model size
- [ ] LoRA continues the original pre-training objective on new data to update the weights of the original model.

**8.** What is a soft prompt in the context of LLMs (Large Language Models)?
- [x] A set of trainable tokens that are added to a prompt and whose values are updated during additional training to improve performance on specific tasks.
- [ ] A strict and explicit input text that serves as a starting point for the model's generation.
- [ ] A technique to limit the creativity of the model and enforce specific output patterns.
- [ ] A method to control the model's behavior by adjusting the learning rate during training.

**9.** "Prompt Tuning is a technique used to adjust all hyperparameters of a language model."

Is this true or false?
- [ ] True
- [x] False

**10.** "PEFT methods can reduce the memory needed for fine-tuning dramatically, sometimes to just 12-20% of the memory needed for full fine-tuning."

Is this true or false?
- [x] True
- [ ] False
