# Title: Towards Temporal Knowledge-Base Creation for Fine-Grained Opinion Analysis with Language Models

## Summary
We propose a scalable method for constructing a temporal opinion knowledge
base with large language models (LLMs) as automated annotators. Despite the
demonstrated utility of time-series opinion analysis of text for downstream
applications such as forecasting and trend analysis, existing methodologies
underexploit this potential due to the absence of temporally grounded
fine-grained annotations. Our approach addresses this gap by integrating
well-established opinion mining formulations into a declarative LLM annotation
pipeline, enabling structured opinion extraction without manual prompt
engineering. We define three data models grounded in sentiment and opinion
mining literature, serving as schemas for structured representation. We perform
rigorous quantitative evaluation of our pipeline using human-annotated test
samples. We carry out the final annotations using two separate LLMs, and
inter-annotator agreement is computed label-wise across the fine-grained
opinion dimensions, analogous to human annotation protocols. The resulting
knowledge base encapsulates time-aligned, structured opinions and is compatible
with applications in Retrieval-Augmented Generation (RAG), temporal question
answering, and timeline summarisation.


Paper link: http://arxiv.org/abs/2509.02363
