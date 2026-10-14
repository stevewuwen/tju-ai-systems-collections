# OSDI 2026 / SOSP 2026 大模型论文集

收录大模型训练、推理、缓存、Agent 及相关系统基础设施论文。

一共包含 73 篇：OSDI 46 篇，SOSP 27 篇。

文件分别存放在 `OSDI2026/` 和 `SOSP2026/`。

点击论文标题进入 PDF 页面，再点击下载按钮保存。

<a id="osdi-2026"></a>

## OSDI 2026 · 46 篇

| 编号 | 论文（点击查看） | 主题 |
| --- | --- | --- |
| 01 | [Strata: Hierarchical Context Caching for Long Context Language Model Serving](OSDI2026/OSDI26-01_Strata_Hierarchical_Context_Caching_for_Long_Context_Language_Model_Serving.pdf) | KV 缓存与长上下文 |
| 02 | [ECHO: Efficient KV Cache Offloading with Lossless Prefetching for Serving Native Sparse Attention LLMs](OSDI2026/OSDI26-02_ECHO_Efficient_KV_Cache_Offloading_with_Lossless_Prefetching_for_Serving_Native_Sparse_Attention_LLMs.pdf) | KV 缓存与长上下文 |
| 03 | [No Buffer, No Bottleneck: Efficient Zero-Copy KV Cache Offloading for Long-Context LLMs](OSDI2026/OSDI26-03_No_Buffer_No_Bottleneck_Efficient_Zero_Copy_KV_Cache_Offloading_for_Long_Context_LLMs.pdf) | KV 缓存与长上下文 |
| 04 | [Simple Is Better: Multiplication May Be All You Need for LLM Request Scheduling](OSDI2026/OSDI26-04_Simple_Is_Better_Multiplication_May_Be_All_You_Need_for_LLM_Request_Scheduling.pdf) | 推理服务与调度 |
| 05 | [Prism: Cost-Efficient Multi-LLM Serving via GPU Memory Ballooning](OSDI2026/OSDI26-05_Prism_Cost_Efficient_Multi_LLM_Serving_via_GPU_Memory_Ballooning.pdf) | 推理服务与调度 |
| 06 | [Tessera: A Holistic Pipeline Parallelism Framework for Trillion-Parameter Heterogeneous MoE Training (Operational Systems)](OSDI2026/OSDI26-06_Tessera_A_Holistic_Pipeline_Parallelism_Framework_for_Trillion_Parameter_Heterogeneous_MoE_Training_Operational_Systems.pdf) | 训练与强化学习 |
| 07 | [Hetu v2: A General and Scalable Deep Learning System with Hierarchical and Heterogeneous Single Program Multiple Data Annotations](OSDI2026/OSDI26-07_Hetu_v2_A_General_and_Scalable_Deep_Learning_System_with_Hierarchical_and_Heterogeneous_Single_Program_Multiple_Data_Annotations.pdf) | 训练与强化学习 |
| 08 | [Syncopate: Efficient Multi-GPU AI Kernels via Automatic Chunk-Centric Compute-Communication Overlap](OSDI2026/OSDI26-08_Syncopate_Efficient_Multi_GPU_AI_Kernels_via_Automatic_Chunk_Centric_Compute_Communication_Overlap.pdf) | 编译、算子与通信 |
| 09 | [Teaching the Old Dog New Tricks: Building Efficient Data Pipelines for Large-Scale LLM Pre-Training (Operational Systems)](OSDI2026/OSDI26-09_Teaching_the_Old_Dog_New_Tricks_Building_Efficient_Data_Pipelines_for_Large_Scale_LLM_Pre_Training_Operational_Systems.pdf) | 训练与强化学习 |
| 10 | [Breaking the Reward Barrier: Accelerating Tree-of-Thought Reasoning via Speculative Exploration](OSDI2026/OSDI26-10_Breaking_the_Reward_Barrier_Accelerating_Tree_of_Thought_Reasoning_via_Speculative_Exploration.pdf) | 推理服务与调度 |
| 11 | [Murakkab: Resource-Efficient Agentic Workflow Orchestration in Cloud Platforms](OSDI2026/OSDI26-11_Murakkab_Resource_Efficient_Agentic_Workflow_Orchestration_in_Cloud_Platforms.pdf) | Agent 与大模型系统应用 |
| 12 | [ECO: An AI-Driven Code Efficiency Optimizer for Warehouse Scale Computers (Operational Systems)](OSDI2026/OSDI26-12_ECO_An_AI_Driven_Code_Efficiency_Optimizer_for_Warehouse_Scale_Computers_Operational_Systems.pdf) | Agent 与大模型系统应用 |
| 13 | [StriaTrace: Efficient Tracing and Diagnosis for Online LLM Inference (Operational Systems)](OSDI2026/OSDI26-13_StriaTrace_Efficient_Tracing_and_Diagnosis_for_Online_LLM_Inference_Operational_Systems.pdf) | 可靠性、调试与安全 |
| 14 | [Diagnosing Performance Issues in Application-Defined Resources](OSDI2026/OSDI26-14_Diagnosing_Performance_Issues_in_Application_Defined_Resources.pdf) | Agent 与大模型系统应用 |
| 15 | [Weave: Efficient Co-Scheduling for Disaggregated RL Post-Training](OSDI2026/OSDI26-15_Weave_Efficient_Co_Scheduling_for_Disaggregated_RL_Post_Training.pdf) | 训练与强化学习 |
| 16 | [RLinf: Flexible and Efficient Large-Scale Reinforcement Learning via Macro-to-Micro Flow Transformation](OSDI2026/OSDI26-16_RLinf_Flexible_and_Efficient_Large_Scale_Reinforcement_Learning_via_Macro_to_Micro_Flow_Transformation.pdf) | 训练与强化学习 |
| 17 | [DynaRL: Flexible and Dynamic Scheduling of Large-Scale Reinforcement Learning Training](OSDI2026/OSDI26-17_DynaRL_Flexible_and_Dynamic_Scheduling_of_Large_Scale_Reinforcement_Learning_Training.pdf) | 训练与强化学习 |
| 18 | [RollArt: Disaggregated Multi-Task Agentic RL Training at Scale](OSDI2026/OSDI26-18_RollArt_Disaggregated_Multi_Task_Agentic_RL_Training_at_Scale.pdf) | 训练与强化学习 |
| 19 | [Seer: Online Context Learning for Fast Synchronous LLM Reinforcement Learning](OSDI2026/OSDI26-19_Seer_Online_Context_Learning_for_Fast_Synchronous_LLM_Reinforcement_Learning.pdf) | 训练与强化学习 |
| 20 | [Achieving Cloud-Grade SLOs for Local Mixture-of-Experts Inference through CPU–GPU Hybrid Design](OSDI2026/OSDI26-20_Achieving_Cloud_Grade_SLOs_for_Local_Mixture_of_Experts_Inference_through_CPU_GPU_Hybrid_Design.pdf) | 推理服务与调度 |
| 21 | [UEP: Portable Expert-Parallel Communication](OSDI2026/OSDI26-21_UEP_Portable_Expert_Parallel_Communication.pdf) | 编译、算子与通信 |
| 22 | [BatchGen: An Architecture for Scalable and Efficient Batch Inference](OSDI2026/OSDI26-22_BatchGen_An_Architecture_for_Scalable_and_Efficient_Batch_Inference.pdf) | 推理服务与调度 |
| 23 | [UCCL-Tran: An Extensible Software Transport Layer for GPU Networking](OSDI2026/OSDI26-23_UCCL_Tran_An_Extensible_Software_Transport_Layer_for_GPU_Networking.pdf) | 编译、算子与通信 |
| 24 | [Kareus: Joint Reduction of Dynamic and Static Energy in Large Model Training](OSDI2026/OSDI26-24_Kareus_Joint_Reduction_of_Dynamic_and_Static_Energy_in_Large_Model_Training.pdf) | 资源管理与基础设施 |
| 25 | [Quota Marketplace: Dynamic Pricing for Efficient Allocation of ML Training Resources](OSDI2026/OSDI26-25_Quota_Marketplace_Dynamic_Pricing_for_Efficient_Allocation_of_ML_Training_Resources.pdf) | 资源管理与基础设施 |
| 26 | [SDCs in the Wild: Characterizing and Diagnosing SDC-Defective GPUs in Production LLM Training (Operational Systems)](OSDI2026/OSDI26-26_SDCs_in_the_Wild_Characterizing_and_Diagnosing_SDC_Defective_GPUs_in_Production_LLM_Training_Operational_Systems.pdf) | 可靠性、调试与安全 |
| 27 | [Safeguarding LLM Training at Scale: Online SDC Detection and Insights from 35 Million GPU Hours](OSDI2026/OSDI26-27_Safeguarding_LLM_Training_at_Scale_Online_SDC_Detection_and_Insights_from_35_Million_GPU_Hours.pdf) | 可靠性、调试与安全 |
| 28 | [OpGuard: Bitwise Alignment for Precise and General Debugging of Production LLM Training](OSDI2026/OSDI26-28_OpGuard_Bitwise_Alignment_for_Precise_and_General_Debugging_of_Production_LLM_Training.pdf) | 可靠性、调试与安全 |
| 29 | [RobustRL: Role-Based Fault Tolerance System for RL Post-Training](OSDI2026/OSDI26-29_RobustRL_Role_Based_Fault_Tolerance_System_for_RL_Post_Training.pdf) | 可靠性、调试与安全 |
| 30 | [CoPilotIO: CPU as a Co-Pilot for GPU I/O to Free GPU Compute](OSDI2026/OSDI26-30_CoPilotIO_CPU_as_a_Co_Pilot_for_GPU_I_O_to_Free_GPU_Compute.pdf) | 编译、算子与通信 |
| 31 | [Efficient LLM Serving on Commodity GPU Clusters with Data-Reduced Cross-Instance Orchestration](OSDI2026/OSDI26-31_Efficient_LLM_Serving_on_Commodity_GPU_Clusters_with_Data_Reduced_Cross_Instance_Orchestration.pdf) | 推理服务与调度 |
| 32 | [Revisiting Pipeline Parallelism for LLM Serving](OSDI2026/OSDI26-32_Revisiting_Pipeline_Parallelism_for_LLM_Serving.pdf) | 推理服务与调度 |
| 33 | [OpenTela: Unifying Decentralized Computing Resources for Heterogeneous LLM Serving (Operational Systems)](OSDI2026/OSDI26-33_OpenTela_Unifying_Decentralized_Computing_Resources_for_Heterogeneous_LLM_Serving_Operational_Systems.pdf) | 推理服务与调度 |
| 34 | [Kairox: Adaptive GPU-CPU Hybrid LLM Inference via Online Neuron Balancing](OSDI2026/OSDI26-34_Kairox_Adaptive_GPU_CPU_Hybrid_LLM_Inference_via_Online_Neuron_Balancing.pdf) | 推理服务与调度 |
| 35 | [ADAngel: Accelerating Arbitrary-Precision Quantized LLMs with Adaptive Computing Mapping](OSDI2026/OSDI26-35_ADAngel_Accelerating_Arbitrary_Precision_Quantized_LLMs_with_Adaptive_Computing_Mapping.pdf) | 编译、算子与通信 |
| 36 | [Optimal Software Pipelining and Warp Specialization for Tensor Core GPUs](OSDI2026/OSDI26-36_Optimal_Software_Pipelining_and_Warp_Specialization_for_Tensor_Core_GPUs.pdf) | 编译、算子与通信 |
| 37 | [MPK: A Compiler and Runtime for Mega-Kernelizing Tensor Programs](OSDI2026/OSDI26-37_MPK_A_Compiler_and_Runtime_for_Mega_Kernelizing_Tensor_Programs.pdf) | 编译、算子与通信 |
| 38 | [GraCE: Unlocking CUDA Graphs with Compiler Support for ML Workloads](OSDI2026/OSDI26-38_GraCE_Unlocking_CUDA_Graphs_with_Compiler_Support_for_ML_Workloads.pdf) | 编译、算子与通信 |
| 39 | [VTC: DNN Compilation with Virtual Tensors for Data Movement Elimination](OSDI2026/OSDI26-39_VTC_DNN_Compilation_with_Virtual_Tensors_for_Data_Movement_Elimination.pdf) | 编译、算子与通信 |
| 40 | [TrainMover: An Interruption-Resilient Runtime for ML Training](OSDI2026/OSDI26-40_TrainMover_An_Interruption_Resilient_Runtime_for_ML_Training.pdf) | 可靠性、调试与安全 |
| 41 | [MoonBright: A GPU Memory Allocator with Device-Side Page Table Materialization and Deferred TLB Coherence](OSDI2026/OSDI26-41_MoonBright_A_GPU_Memory_Allocator_with_Device_Side_Page_Table_Materialization_and_Deferred_TLB_Coherence.pdf) | 资源管理与基础设施 |
| 42 | [Nixie: Efficient, Transparent Temporal Multiplexing for Consumer GPUs](OSDI2026/OSDI26-42_Nixie_Efficient_Transparent_Temporal_Multiplexing_for_Consumer_GPUs.pdf) | 资源管理与基础设施 |
| 43 | [Heterogeneity at Hyperscale: Characterization and Scheduling of Large Production AI Clusters at Alibaba (Operational Systems)](OSDI2026/OSDI26-43_Heterogeneity_at_Hyperscale_Characterization_and_Scheduling_of_Large_Production_AI_Clusters_at_Alibaba_Operational_Systems.pdf) | 资源管理与基础设施 |
| 44 | [Inference in the Shadows: Taming Memory Bandwidth Contention in Mobile LLM Inference with Sereno](OSDI2026/OSDI26-44_Inference_in_the_Shadows_Taming_Memory_Bandwidth_Contention_in_Mobile_LLM_Inference_with_Sereno.pdf) | 推理服务与调度 |
| 45 | [SMARTTalk: Teaching SMART Logs to Talk to LLMs](OSDI2026/OSDI26-45_SMARTTalk_Teaching_SMART_Logs_to_Talk_to_LLMs.pdf) | Agent 与大模型系统应用 |
| 46 | [Neuro-Symbolic Proof Generation for Scaling Systems Software Verification](OSDI2026/OSDI26-46_Neuro_Symbolic_Proof_Generation_for_Scaling_Systems_Software_Verification.pdf) | Agent 与大模型系统应用 |

<a id="sosp-2026"></a>

## SOSP 2026 · 27 篇

| 编号 | 论文（点击查看） | 主题 | 文件版本 |
| --- | --- | --- | --- |
| 01 | [Janus: Multi-LLM Serving at Production Scale](SOSP2026/SOSP26-01_Janus_Multi_LLM_Serving_at_Production_Scale.pdf) | 推理服务与调度 | 正式版 |
| 02 | [SANDHI: Fine-grained Merging for Memory Efficient Multi-Model Serving](SOSP2026/SOSP26-02_SANDHI_Fine_grained_Merging_for_Memory_Efficient_Multi_Model_Serving.pdf) | 推理服务与调度 | 正式版 |
| 03 | [Batched in Back: Characterizing and Optimizing Offline LLM Inference in Production with ACDC](SOSP2026/SOSP26-03_Batched_in_Back_Characterizing_and_Optimizing_Offline_LLM_Inference_in_Production_with_ACDC.pdf) | 推理服务与调度 | 作者版 |
| 04 | [Taming Inference Workloads at Global Scale: Foundation Model Serving in Amazon Bedrock](SOSP2026/SOSP26-04_Taming_Inference_Workloads_at_Global_Scale_Foundation_Model_Serving_in_Amazon_Bedrock.pdf) | 推理服务与调度 | 正式版 |
| 05 | [Beyond Utilization: Energy-Conscious GPU Sharing for Inference Serving](SOSP2026/SOSP26-05_Beyond_Utilization_Energy_Conscious_GPU_Sharing_for_Inference_Serving.pdf) | 资源管理与基础设施 | 正式版 |
| 06 | [Cerium: A Multi-GPU Framework for Terabyte-Scale Encrypted Inference](https://arxiv.org/pdf/2512.11269) | 可靠性、调试与安全 | arXiv · 原站 |
| 07 | [Don't Let AI Agents YOLO Your Files: Information and Control in Agent-Native Filesystems](SOSP2026/SOSP26-07_Don_t_Let_AI_Agents_YOLO_Your_Files_Information_and_Control_in_Agent_Native_Filesystems.pdf) | Agent 与大模型系统应用 | arXiv |
| 08 | [TensorDex: A Compact, Tensor-Centric Storage System for Modern AI Models](https://arxiv.org/pdf/2604.17104) | 资源管理与基础设施 | arXiv · 原站 |
| 09 | [AgileLog: A Forkable Shared Log for Agents on Data Streams](SOSP2026/SOSP26-09_AgileLog_A_Forkable_Shared_Log_for_Agents_on_Data_Streams.pdf) | Agent 与大模型系统应用 | arXiv |
| 10 | [Skill VM: Write Once, Run Everywhere Efficiently](https://arxiv.org/pdf/2604.03088) | Agent 与大模型系统应用 | arXiv · 原站 |
| 11 | [DiFlow: A System for Micro-Serving Text-to-Image Diffusion Workflows](SOSP2026/SOSP26-11_DiFlow_A_System_for_Micro_Serving_Text_to_Image_Diffusion_Workflows.pdf) | 多模态与扩散模型 | arXiv |
| 12 | [LMTracer: Fine-Grained and Real-Time Performance Profiling for Production LLM Systems](SOSP2026/SOSP26-12_LMTracer_Fine_Grained_and_Real_Time_Performance_Profiling_for_Production_LLM_Systems.pdf) | 可靠性、调试与安全 | 正式版 |
| 13 | [Scalable Context Orchestration for Serving LLMs Over Voice](SOSP2026/SOSP26-13_Scalable_Context_Orchestration_for_Serving_LLMs_Over_Voice.pdf) | 多模态与扩散模型 | arXiv |
| 14 | [TuxBot: Semantic-Aware Online OS Tuning with LLMs](SOSP2026/SOSP26-14_TuxBot_Semantic_Aware_Online_OS_Tuning_with_LLMs.pdf) | Agent 与大模型系统应用 | arXiv |
| 15 | [StreamEP: Straggler-Tolerant MoE Decoding without Communication Barriers](SOSP2026/SOSP26-15_StreamEP_Straggler_Tolerant_MoE_Decoding_without_Communication_Barriers.pdf) | 推理服务与调度 | 正式版 |
| 16 | [I3DP: Neuro-symbolic Inductive Invariant Inference for Distributed Protocols](https://arxiv.org/pdf/2605.24619) | Agent 与大模型系统应用 | arXiv · 原站 |
| 17 | [Anchor: Mitigating GPU Shallow Disruptions with Decoupled Memory](SOSP2026/SOSP26-17_Anchor_Mitigating_GPU_Shallow_Disruptions_with_Decoupled_Memory.pdf) | 可靠性、调试与安全 | 正式版 |
| 18 | [TensorHub: Scalable and Elastic Weight Transfer for LLM RL Training](SOSP2026/SOSP26-18_TensorHub_Scalable_and_Elastic_Weight_Transfer_for_LLM_RL_Training.pdf) | 训练与强化学习 | arXiv |
| 19 | [A Few GPUs, A Whole Lotta Scale: Faithful LLM Training Emulation with CrystalLLM](SOSP2026/SOSP26-19_A_Few_GPUs_A_Whole_Lotta_Scale_Faithful_LLM_Training_Emulation_with_CrystalLLM.pdf) | 训练与强化学习 | 作者版 |
| 20 | [LLM-42: Enabling Determinism in LLM Inference with Verified Speculation](SOSP2026/SOSP26-20_LLM_42_Enabling_Determinism_in_LLM_Inference_with_Verified_Speculation.pdf) | 可靠性、调试与安全 | arXiv |
| 21 | [State-Aware Fuzzing of JavaScript Engines with LLM-Guided Instrumentation](SOSP2026/SOSP26-21_State_Aware_Fuzzing_of_JavaScript_Engines_with_LLM_Guided_Instrumentation.pdf) | Agent 与大模型系统应用 | arXiv |
| 22 | [Efficient GPU Multitasking with Morphable Kernels](SOSP2026/SOSP26-22_Efficient_GPU_Multitasking_with_Morphable_Kernels.pdf) | 资源管理与基础设施 | 正式版 |
| 23 | [Ave: Guiding Agentic GPU Optimization Using Data-Flow Invariants](SOSP2026/SOSP26-23_Ave_Guiding_Agentic_GPU_Optimization_Using_Data_Flow_Invariants.pdf) | Agent 与大模型系统应用 | arXiv |
| 24 | [Taming Dynamism on GPUs: Cross-SM Kernel Fusion via SM Cooperation and Just-in-Time Reduction](SOSP2026/SOSP26-24_Taming_Dynamism_on_GPUs_Cross_SM_Kernel_Fusion_via_SM_Cooperation_and_Just_in_Time_Reduction.pdf) | 编译、算子与通信 | 正式版 |
| 25 | [M2K: Making the Model-Kernel Interface Explicit for Reliable CUDA Kernel Verification](SOSP2026/SOSP26-25_M2K_Making_the_Model_Kernel_Interface_Explicit_for_Reliable_CUDA_Kernel_Verification.pdf) | 可靠性、调试与安全 | arXiv |
| 26 | [Wavel: A Fast and Efficient Compilation System for Wafer-Scale Accelerators](SOSP2026/SOSP26-26_Wavel_A_Fast_and_Efficient_Compilation_System_for_Wafer_Scale_Accelerators.pdf) | 编译、算子与通信 | 正式版 |
| 27 | [MeshRT: Compile-Time Governed Wafer-Scale Runtime for Low-Latency High-Throughput Inference](SOSP2026/SOSP26-27_MeshRT_Compile_Time_Governed_Wafer_Scale_Runtime_for_Low_Latency_High_Throughput_Inference.pdf) | 推理服务与调度 | 正式版 |
