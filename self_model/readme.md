
Qwen2MultiTaskForCausalLM 继承自 Qwen2PreTrainedModel 和 GenerationMixin，基于Qwen2模型主干，设计了多个任务专用的输出头（task heads），支持不同任务共用同一主干模型，方便多任务微调和推理。

模型存在自己的虚拟环境里的transformers包内，例如vllm_env环境将模型存在：~/miniforge3/envs/vllm_env/lib/python3.11/site-packages/transformers/models/qwen2/modeling_qwen2.py

