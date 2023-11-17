# Finetuning Llama 2 using QLoRa method: Project Overview
- Finetuned ``Llama 2`` (7B parameters) on a T4 GPU using Google Colab in a ``4-bit`` precision 
- Employed Supervised Fine-Tuning (``SFTTrainer``) to finetune the model with the ``miniguanaco`` dataset of 1000 instruction-response pairs 
- Utilized ``PEFT`` (parameter-efficient fine-tuning) techniques to save resources

## Code and Resources Used
**Python Version:** 3.8 <br>
**Packages:** pytorch, transformers, peft, trl, accelerate, bitsandbytes <br>
**Dataset**: https://huggingface.co/datasets/mlabonne/guanaco-llama2-1k <br>
**SFTTrainer Documentation**: https://huggingface.co/docs/trl/main/en/sft_trainer <br>
**PEFT Documentation**: https://huggingface.co/docs/peft/package_reference/peft_model <br>
**Younes Belkada's Github Gist:** https://gist.github.com/younesbelkada/9f7f75c94bdc1981c8ca5cc937d4a4da <br>
**How to prompt Llama 2 by Hugging Face**: https://huggingface.co/blog/llama2#how-to-prompt-llama-2<br>

## Detailed blog post
https://hahoangpro.wixsite.com/datascience/post/instruction-finetuning-llama-2-with-peft-s-qlora-method

## Additional projects
https://hahoangpro.wixsite.com/datascience/blog
