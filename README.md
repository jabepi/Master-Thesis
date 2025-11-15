# Master-Thesis
Performance analysis of AI models, focusing on computational and memory requirements on GPUs. Utilized hardware counters, the roofline model, and memory bandwidth-latency curves to evaluate and optimize system performance


# Abstract 

This thesis presents a theoretical and experimental analysis of modern AI models, focusing on
their structure and hardware performance characteristics. The work is divided into three main
parts.
First, we analyze the most widely used AI models in the industry, including Deep Neural
Networks (DNNs), Deep Learning Recommendation Systems (DLRMs), Recurrent Neural Net-
works (RNNs) and Transformers. We study their layer structures, compute and memory re-
quirements, data types, and execution patterns. The goal is to identify common operations, such
as matrix-vector multiplications or attention layers, that are frequently used across models and
have a strong impact on hardware performance. This analysis is summarized in the FAiNDER
platform, a live web tool that provides structured and interactive access to model details and
their hardware demands. FAiNDER has received the HiPEAC Technology Transfer Award for its
contribution to power technologies, which will support the development of the next generation of
high-performance AI applications. This platform helps researchers and developers explore model
architectures, compare performance characteristics, and find optimization opportunities based on
reliable information from scientific publications.
In the second part of the thesis, we perform over Llama3, one of the most widely used LLM
open source models, a detailed performance evaluation. We present a methodology to measure
the compute and memory behavior of the model under different configurations and execution sce-
narios. The experimental setup includes analysis across layers and execution phases, helping to
understand how models behave in real applications. Finally, we apply this knowledge in a practical
case study, exploring how part of the model can be offloaded to an alternative hardware platform.
This allows for improved resource utilization and system performance. The proposed methodology
and results serve as a guide for future work in AI model profiling and hardware optimization.
Finally, we use the insights gained from the analysis to propose offloading part of the model
to another hardware platform, with the goal of improving hardware utilization. This serves as a real-
world example of how the theoretical and experimental analysis can be applied to enhance system
performance. The case study demonstrates the potential benefits of offloading and provides a
practical reference for future research in this area.
