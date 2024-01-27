# LLM-openai-finetuning
All resources from where I have learnt LLM , fine tuning and transformers

1. 3 basic LLM projects quite good : https://github.com/codebasics/langchain/tree/main/2_news_research_tool_project
2. https://www.datacamp.com/tutorial/fine-tuning-llama-2
3. https://huggingface.co/blog/peft: Lora fine tuning
4. https://www.youtube.com/watch?v=NRVaRXDoI3g : Lora 
5. Transformer explained : https://www.youtube.com/watch?v=TQQlZhbC5ps
6. https://www.youtube.com/watch?v=lixMONUAjfs : Lora concept

Notes on Prompting :
  1. I have found a simple, effective approach to improve the results we obtain from our model. This approach is often labeled as a Zero-Shot CoT.
  
  There are a few words that, when added to the prompt, are likely to solicit better answers since they invite the AI to do step-by-step reasoning, much like a human would when trying to come to a resolution.
  
  According to researchers, two effective phrases are:
  
  Let's think step by step.
  
  And:
  
  Let's work this out in a step by step way to be sure we have the right answer.
