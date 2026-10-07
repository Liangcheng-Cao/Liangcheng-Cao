# Liangcheng Cao

**ML Systems & Machine Learning | Mathematics @ University of Rochester**

I work on machine learning systems, LLM inference, retrieval/ranking, and performance analysis.  
My projects focus on controlled experiments, reproducible systems, and understanding why models or serving pipelines behave the way they do.

## Featured Projects

### SGLang Decode Execution Regimes
GPU-level study of CUDA Graph versus eager decode in SGLang.

At fixed useful batch size, CUDA Graph replay improved decode cadence by **3.24×** while observed GPU work remained nearly unchanged. Nsight Systems analysis showed **16.6× more individual kernel launches** and **28.3× larger inter-kernel gaps** under eager execution.

[View Repository](https://github.com/Liangcheng-Cao/llm-serving-regime-study)

### Production Retrieval & Ranking
End-to-end product-search system built from retrieval through reranking, serving, benchmarking, and observability.

Includes BM25 retrieval, neural reranking, FastAPI serving, latency benchmarking, monitoring, drift analysis, and champion/challenger evaluation.

[View Repository](YOUR_WANDS_REPOSITORY_URL)

### LLM Inference Gateway
Async inference gateway for SGLang with admission control, scheduling, streaming, observability, and reproducible load experiments.

Designed to study how serving policies affect latency, throughput, and reliability under concurrent workloads.

[View Repository](https://github.com/Liangcheng-Cao/llm-inference-gateway)

## Areas of Interest

LLM inference · ML systems · retrieval & ranking · GPU performance · serving systems · applied machine learning
