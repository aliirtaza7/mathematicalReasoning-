Qwen2.5-Math-1.5B PRM Training (PRM800K Phase 1)

This project trains a Process Reward Model (PRM) using Qwen2.5-Math-1.5B. The model learns to check math reasoning steps by looking at a problem and a partial solution, then predicting whether the final step is correct or incorrect.

It uses LoRA/QLoRA fine-tuning on the PRM800K Phase 1 dataset and creates a step-level verifier that can score solutions. Unlike a normal language model, it does not generate answers  it evaluates the quality of reasoning and helps select better solutions.
