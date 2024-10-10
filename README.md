# Summarization using FLAN-T5 with Prompt Engineering, Fine-Tuning, and Reinforcement Learning

## Project Overview

This project focuses on generating summaries using the pre-trained *Large Language Model (LLM) FLAN-T5* from Hugging Face. The workflow includes:

- *Prompt Engineering: Comparisons between **Zero Shot, **One Shot, and **Few Shot* inferences to identify the best approach for generating accurate summaries.
  
- *Model Fine-Tuning*:
  - *Full Fine-Tuning*: Modifying all model weights based on task-specific data.
  - *Parameter Efficient Fine-Tuning (PEFT)*: Fine-tuning only a subset of model parameters, allowing for more efficient and quicker adjustments.
  
- *Evaluation: The results of the fine-tuning approaches are evaluated using the **ROUGE metrics*.
  
- *Reinforcement Learning (RL): RL is applied to generate less-toxic summaries by incorporating **Meta AI's hate speech reward model*.

## Key Findings

- *Prompt Engineering* results showed that *Few Shot* inferences provided the most accurate summaries.
- *PEFT Fine-Tuning* achieved a *17.47% absolute improvement* over the original model using *ROUGE metrics*.
- *Reinforcement Learning* led to more ethical and less-toxic summaries, incorporating the *hate speech reward model* to reduce harmful content.
