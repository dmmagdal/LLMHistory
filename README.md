# LLM History

Description: Simple repo keeping track of the history of LLMs as they evolve. Starting from the first GPT, each folder will contain any associated materials, including white papers and repos as submodules (where possible).


## Models

### GPT 1

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible: No
 - Additional links:


### GPT 2

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### GPT 3

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint
 - RAG compatible:
 - Additional links:


### GPT Neo(X)

 - paper: [](), 
 - GitHub: [EleutherAI/gpt-neo](https://github.com/EleutherAI/gpt-neo) [EleutherAI/gpt-neox](https://github.com/EleutherAI/gpt-neox)
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:
     - Huggingface [model documentation](https://huggingface.co/docs/transformers/model_doc/gpt_neo) (GPT Neo)
     - Huggingface [model documentation](https://huggingface.co/docs/transformers/model_doc/gpt_neox) (GPT NeoX)


### GPT J

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### OPT

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### MPT

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### Llama

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### Llama 2

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint
 - RAG compatible:
 - Additional links:


### Falcon

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### LongNet

 - paper: [Longnet: Scaling Transformers to 1,000,000,000 Tokens](https://arxiv.org/pdf/2307.02486.pdf), submitted Jul 2023 
 - GitHub: [Microsoft/unillm](https://github.com/microsoft/unilm/)
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


### RAG

 - paper: [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401.pdf), submitted May 2020
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible: Yes
 - Additional links:
     - Huggingface [model documentation](https://huggingface.co/docs/transformers/model_doc/rag)


### REALM

 - paper: [REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909.pdf), submitted Feb 2020
 - GitHub: [google-research/language](https://github.com/google-research/language/tree/master/language/realm)
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible: Yes
 - Additional links:
     - Google Research [blog post](https://blog.research.google/2020/08/realm-integrating-retrieval-into.html)
     - Huggingface [model documentation](https://huggingface.co/docs/transformers/model_doc/realm)


### RETRO

 - paper: [](), 
 - GitHub: 
 - Number of parameters: 
 - Memory footprint:
 - RAG compatible:
 - Additional links:


## Attention Improvemments

### Performer

 - paper: [Rethinking Attention with Performers](https://arxiv.org/pdf/2009.14794.pdf), submitted Sep 2020
 - GitHub: 
 - Additional links:
     - lucidrains [unofficial performer implementation](https://github.com/lucidrains/performer-pytorch)
     - xl402s [tensorflow implementation](https://github.com/xl402/performer)


### Reformer

 - paper: [Reformer: The Efficient Transformer](https://arxiv.org/pdf/2001.04451.pdf), submitted Jan 2020
 - GitHub: 
 - Additional links:
     - Huggingface [model documentation](https://huggingface.co/docs/transformers/model_doc/reformer)
     - Huggingface [contributed code](https://github.com/google/trax/tree/master/trax/models/reformer)
     - lucidrains [unofficial reformer implementation](https://github.com/lucidrains/reformer-pytorch)
     - Medium article: [The Illustrated Reformer](https://towardsdatascience.com/illustrating-the-reformer-393575ac6ba0) (member only story)
     - [Efficient Transformers: A survey](https://arxiv.org/pdf/2009.06732.pdf), submitted Sep 2020
     - Medium article: [Sparse Transformers and Longformers: A comprehensive summary of space and time optimizations on Transformers(Part — 1)](https://medium.com/walmartglobaltech/sparse-transformers-and-longformers-a-comprehensive-summary-of-space-and-time-optimizations-on-4caa5c388693)
     - Medium article: [Reformers and Performers: A comprehensive summary of space and time optimizations on Transformers (Part — 2)](https://medium.com/walmartglobaltech/reformers-and-performers-a-comprehensive-summary-of-space-and-time-optimizations-on-transformers-c00178e31843)


### Roformer

 - paper: [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/pdf/2104.09864.pdf), submitted Apr 2021
 - GitHub: 
 - Additional links:
     - Huggingface [model documentation](https://huggingface.co/docs/transformers/model_doc/roformer)
     - Huggingface [contributed code](https://github.com/ZhuiyiTechnology/roformer)
     - AryaAftabs [tensorflow implementation](https://github.com/AryaAftab/rotary-embedding-tensorflow)


## Datasets

### OpenWebText

 - Size: 
 - Huggingface datasets [model card](https://huggingface.co/datasets/Skylion007/openwebtext)

### The Pile

 - Size: 
 - [The Pile datasheet](https://arxiv.org/pdf/2201.07311.pdf)
 - Huggingface datasets [model card](https://huggingface.co/datasets/EleutherAI/pile)
 - Huggingface datasets [model card](https://huggingface.co/datasets/the_pile_openwebtext2) (openwebtext2, derived from The Pile dataset)


### Misc Resources

 - Comparison of LLMs (from sapling.ai):
     - [falcon v wizard](https://sapling.ai/llm/falcon-vs-wizard)
     - [falcon v mpt](https://sapling.ai/llm/falcon-vs-mpt)
     - [falcon v opt](https://sapling.ai/llm/falcon-vs-opt)
     - [falcon v gpt-j](https://sapling.ai/llm/falcon-vs-gpt-j)
     - [falcon v flan-t5](https://sapling.ai/llm/falcon-vs-flan-t5)
     - [falcon v llama2](https://sapling.ai/llm/falcon-vs-llama2)