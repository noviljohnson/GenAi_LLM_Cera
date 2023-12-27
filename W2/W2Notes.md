## Week 2 Notes

### Fine Tuning an LLM with Instruction Prompts

=> In context Learning (ICL) - Zero Shot Inference 
    - Some LLMs performs zero shot infence well with simple prompt.
    - some small language models perform well few shot inference.

  - limitation of ICL
    - ICL may not work for small LMs even with few shot
    - examples take up space in the context window
  * use fine tune
    
=> LLM fine tuning at high level
    - LLM pretraining is Unsupervised Learning process
        - GB/TB/PB of unstructured data will be used to pretrain the llms
    - LLM fine tuning is Supervised Learning Process
        - GB/TB of structured( Labeled Dataset ) to update the weights of LLM
        - Task specific examples will be used
          - Prompt[...] & Completion[...] pairs

=> Instruction Fine tuning
    - using prompts to fine tune LLMs with instructions
    - each prompt/completion pair includes a specific "instruction" to the LLM
    - " The Instruction fine tuning where all the weights of the model are updated called full finetuning "
      
