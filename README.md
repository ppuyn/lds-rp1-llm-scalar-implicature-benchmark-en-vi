lds-rp1-llm-scalar-implicature-benchmark-en-vi
# Cross-lingual Evaluation of LLMs in Pragmatic Accuracy and Reasoning

This repository contains the code, data processing pipeline, prompts, and evaluation framework for my research project at Linguistic Data Science Lab (RUB) on LLM pragmatic reasoning in English and Vietnamese.

The project focuses on scalar implicatures, a pragmatic phenomenon where a weaker expression often implies that a stronger alternative does not hold. For example, saying `some` may imply `not all`, and saying `may` may contrast with stronger meanings such as `must`. These meanings are context-dependent and cannot be evaluated through surface-level semantics alone.

The goal of this project is to examine whether large language models can accurately detect scalar implicatures across languages and whether their generated explanations are faithful to the pragmatic reasoning required by the task.

The study evaluates three main aspects in LLMs:
- Pragmatic accuracy: whether the model predicts the correct inference label.
- Reasoning faithfulness: whether the model’s explanation correctly supports its prediction.
- Answer–reason alignment: whether correct answers are also supported by faithful reasoning.

The benchmark compares English and Vietnamese data, different open-weight LLMs, and limited prompting strategies, including direct classification and reasoning-oriented prompts. The results aim to show how language, model architecture, and prompt design affect pragmatic inference and explanation quality.
