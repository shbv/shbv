## Overview

Projects/Codes spanning LLMs/VLMs, Agentic AI, RAG, Generative models, classical ML, and algorithms.

## LLMs / VLMs

### [LLMs_VLMs_1](https://github.com/shbv/LLMs_VLMs_1)
LLM/VLM fundamentals: GPT2/Llama3 built from scratch in PyTorch, pre-training, fine-tuning (classification, instruction following), Hugging Face usage, and optimizations.
- [1_pytorch_from_scratch_toy_model_code](https://github.com/shbv/LLMs_VLMs_1/tree/main/1_pytorch_from_scratch_toy_model_code): toy network training on single and multiple GPUs.
- [2_pytorch_from_scratch_notebooks](https://github.com/shbv/LLMs_VLMs_1/tree/main/2_pytorch_from_scratch_notebooks): notebooks building LLM components in PyTorch.
- [3_pytorch_from_scratch_llm_code](https://github.com/shbv/LLMs_VLMs_1/tree/main/3_pytorch_from_scratch_llm_code): modular code for LLM pre-training and fine-tuning.
- [4_huggingface_api_notebooks](https://github.com/shbv/LLMs_VLMs_1/tree/main/4_huggingface_api_notebooks): training, fine-tuning and inference with Hugging Face.
- [5_pytorch_from_scratch_vlm_code](https://github.com/shbv/LLMs_VLMs_1/tree/main/5_pytorch_from_scratch_vlm_code): VLM code and customizing HF models.

### [LLMs_VLMs_2](https://github.com/shbv/LLMs_VLMs_2)
Continuation of LLM/VLMs: pre-training, post-training, distillation, quantization, serving and evaluation.
- [PreTraining_LLMs](https://github.com/shbv/LLMs_VLMs_2/tree/main/PreTraining_LLMs): continual pre-training with data cleanup and depth upscaling.
- [PostTraining_LLMs](https://github.com/shbv/LLMs_VLMs_2/tree/main/PostTraining_LLMs): SFT, DPO and GRPO with Hugging Face.
- [PostTraining_LLMs_1](https://github.com/shbv/LLMs_VLMs_2/tree/main/PostTraining_LLMs_1): RLHF with PPO.
- [PostTraining_LLMs_2](https://github.com/shbv/LLMs_VLMs_2/tree/main/PostTraining_LLMs_2): SFT/GRPO, offline and production evaluation, Constitutional AI.
- [PostTraining_GRPO_StructuredOutput](https://github.com/shbv/LLMs_VLMs_2/tree/main/PostTraining_GRPO_StructuredOutput): GRPO + LoRA on LFM2.5-350M for structured output (pass rate 22.1% → 29.4%), with GGUF/llama.cpp inference.
- [PostTraining_AgentTraces](https://github.com/shbv/LLMs_VLMs_2/tree/main/PostTraining_AgentTraces): training better agents via tool traces, distillation, verifiable rewards and environments.
- [Distillation](https://github.com/shbv/LLMs_VLMs_2/tree/main/Distillation): knowledge distillation for neural nets.
- [Quantization](https://github.com/shbv/LLMs_VLMs_2/tree/main/Quantization): linear quantization, `quanto`, and a custom 8-bit quantizer from scratch.
- [Efficienly_Serving_LLMs](https://github.com/shbv/LLMs_VLMs_2/tree/main/Efficienly_Serving_LLMs): KV cache, batching and continuous batching.
- [Efficient_Inference_with_vLLM](https://github.com/shbv/LLMs_VLMs_2/tree/main/Efficient_Inference_with_vLLM): vLLM serving, prefix caching, `llm-compressor`, `guidellm` and `lm_eval`.
- [Evaluating_Debugging_GenAI_WandB](https://github.com/shbv/LLMs_VLMs_2/tree/main/Evaluating_Debugging_GenAI_WandB): Weights & Biases tracking, artifacts and evaluation.


## Agentic AI

### [Agentic_AI](https://github.com/shbv/Agentic_AI)
Agent concepts, design patterns and frameworks with examples.
- [AgenticAI_ConceptsExamples_1](https://github.com/shbv/Agentic_AI/tree/main/AgenticAI_ConceptsExamples_1): reflection, tool use, planning and multi-agent workflows, framework-agnostic.
- [AgenticAI_ConceptsExamples_2](https://github.com/shbv/Agentic_AI/tree/main/AgenticAI_ConceptsExamples_2): agents from scratch and framework overview.
- [LangGraph](https://github.com/shbv/Agentic_AI/tree/main/LangGraph): stateful agentic workflows, concepts and apps.
- [CrewAI](https://github.com/shbv/Agentic_AI/tree/main/CrewAI): multi-agent systems with CrewAI.
- [SmolAgents](https://github.com/shbv/Agentic_AI/tree/main/SmolAgents): code agents and secure code execution.
- [MCP](https://github.com/shbv/Agentic_AI/tree/main/MCP): Model Context Protocol basics.
- [CodingAgents_E2B](https://github.com/shbv/Agentic_AI/tree/main/CodingAgents_E2B): coding agents executed in E2B sandboxes (data analyst, full-stack developer).
- [ContextEngineering](https://github.com/shbv/Agentic_AI/tree/main/ContextEngineering): context failure modes, agentic search, context management and memory.
- [LoopEngineering](https://github.com/shbv/Agentic_AI/tree/main/LoopEngineering): agent loops (verification, learning, event-driven) with LangChain Deep Agents.

## RAG / Embeddings / Recommenders

### [Embeddings_RAG_Search_Recommenders](https://github.com/shbv/Embeddings_RAG_Search_Recommenders)
Embedding models, RAG, retrieval/search, recommenders and vector DBs.
- [RAG](https://github.com/shbv/RAG): RAG concepts, retrieval, retrieval metrics, vector embeddings, chunking strategies, building RAG systems with a vector DB (Weaviate), developing and improving a RAG chatbot.
- [EmbeddingModels](https://github.com/shbv/Embeddings_RAG_Search_Recommenders/tree/main/EmbeddingModels): embedding model concepts and examples.
- [Advanced_Retrieval_Chromadb](https://github.com/shbv/Embeddings_RAG_Search_Recommenders/tree/main/Advanced_Retrieval_Chromadb): advanced retrieval techniques with Chroma.

## Generative Models

### [GenerativeModels](https://github.com/shbv/GenerativeModels)
GANs, diffusion models, VAE, VQ-VAE and auto-regressive models.
- [AE_VAE_VQVAE](https://github.com/shbv/GenerativeModels/tree/main/AE_VAE_VQVAE): autoencoders, VAE and VQ-VAE.
- [DiffusionModels](https://github.com/shbv/GenerativeModels/tree/main/DiffusionModels): diffusion models from scratch.
- [GANs](https://github.com/shbv/GANs): GAN basics, improvements and applications.
- [TextToImage_Seg_Gen_FT](https://github.com/shbv/GenerativeModels/tree/main/TextToImage_Seg_Gen_FT): text-to-image generation, object detection/segmentation, image inpainting & fine-tuning diffusion models.

## Image captioning research
- [Partially_Supervised_Novel_Object_Captioning](https://github.com/shbv/BMVC_Partially_Supervised_Novel_Object_Captioning): BMVC 2022 paper code on novel object captioning using context from paired data. Involves Cross-entropy training followed by RL training. [Paper](https://papers.bmvc2022.cvml.group/0649.pdf) [Arxiv](https://arxiv.org/abs/2109.05115)

## ML / Algorithms

- [ML_Projects](https://github.com/shbv/ML_Projects): projects on Supervised learning, Unsupervised learning, Reinforcement learning, NLP classification.
- [AI_Search_Algorithm_Projects](https://github.com/shbv/AI_Search_Algorithm_Projects): projects on search (8-puzzle search with bfs/dfs/A*), minimax algo (2048 adversarial game), CSP (Sudoku).
- [ML_Models_From_Scratch](https://github.com/shbv/ML_Models_From_Scratch): random forests (decision tree regressor/classifier) and K-means from scratch.
- [Data_Structures_Algorithms](https://github.com/shbv/Data_Structures_Algorithms): lists, linked lists, stacks/queues, hash tables, heaps, trees and graphs, with complexity notes.
- [Python](https://github.com/shbv/Python): Python concepts such as iterators/generators, itertools, context managers, regex and functional programming.
