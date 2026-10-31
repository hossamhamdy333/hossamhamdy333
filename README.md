# Hi, I'm Hossam

I'm an AI engineer in Cairo. I build LLM and RAG systems, fine-tune models, and ship them with FastAPI and Docker. I also do classical ML and data analysis. I'm looking for AI engineer roles.

I just finished my degree in Electronics and Communications Engineering at HTI. My graduation project was a network intrusion detection system, and I led the ML and deployment side.

## Things I built

- **[llm-cost-router](https://github.com/hossamhamdy333/llm-cost-router)**: a service that sends each question to a cheap or a strong Gemini model. On 50 test questions it cost 19.5% less than always using the strong one.
- **[Search over arXiv papers](https://github.com/hossamhamdy333/AI_Portfolio/tree/main/semantic-search-arxiv-papers)**: 50K abstracts, built in stages from BM25 to reranking. MRR went from 0.712 to 0.818.
- **[Fact-check agents](https://github.com/hossamhamdy333/AI_Portfolio/tree/main/fact_check_crew)**: three CrewAI agents that write, check and revise answers. Hallucination rate dropped from 0.12 to 0.08 on 100 questions, at about 2 to 3 times the LLM calls.
- **[Text-to-SQL fine-tuning](https://github.com/hossamhamdy333/AI_Portfolio/tree/main/nl2sql_finetune)**: Qwen2.5-Coder with QLoRA. The share of valid SQL went from 92.00% to 97.25% on 400 held-out questions.
- **[Arabic legal fine-tuning](https://github.com/hossamhamdy333/AI_Portfolio/tree/main/allam_finetune)**: ALLaM-7B with QLoRA. On 150 held-out rows, faithfulness went from 4.72 to 8.47 out of 10 (scored by Gemini).
- **[Intrusion detection thesis](https://github.com/hossamhamdy333/machine-learning-techniques-for-intrusion-detection)**: XGBoost on
