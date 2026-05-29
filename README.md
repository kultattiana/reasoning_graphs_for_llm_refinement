# LLM Reasoning Graphs for Error Prediction and Model Refinement

This repository contains the code base for the research that investigates the possibility of using 
structural information from reasoning graphs to improve the effectiveness of large language model fine-tuning. 
Standard LLM fine-tuning relies on a token-level comparison between the generated solution and the reference one. 
However, this approach does not take into account or regulate the internal logical coherence between reasoning steps. 
In this work, we propose to indirectly influence the graph structure by incorporating additional feedback into the fine-tuning process. 
The main contribution of the work is a systematic comparison of reasoning graph extraction methods and a demonstration that attention-based graphs yield the most informative structure
for error prediction and model refinement. 
