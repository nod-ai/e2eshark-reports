## Passing Summary

**TOTAL TESTS = 31**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 26 | 83.9% | 83.9% |
| IREE Compilation | 11 | 35.5% | 42.3% |
| Gold Inference | 11 | 35.5% | 100.0% |
| IREE Inference Invocation | 11 | 35.5% | 100.0% |
| Inference Comparison (PASS) | 11 | 35.5% | 100.0% |
## Fail Summary

**TOTAL TESTS = 31**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 5 | 16.1% |
| IREE Compilation | 15 | 48.4% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-text-generation-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-text-generation-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_distilgpt2 | import_model | None | |
| hf_gpt2 | import_model | None | |
| hf_gpt2-small-spanish | PASS | None | |
| hf_llama-68m | import_model | None | |
| hf_llama-7b | import_model | None | |
| hf_Llama3-8B-1.58-100B-tokens-GGUF | setup | None | |
| hf_Meta-Llama-3.1-8B-Instruct-AWQ-INT4 | setup | None | |
| hf_Meta-Llama-3.1-8B-Instruct-bnb-4bit | setup | None | |
| hf_Midnight-Miqu-70B-v1.5-4bit | setup | None | |
| hf_Mistral-7B-Instruct-v0.2-GPTQ | setup | None | |
| hf_oasst-sft-4-pythia-12b-epoch-3.5 | import_model | None | |
| hf_opt-125m | PASS | None | |
| hf_Phi-3-mini-128k-instruct | import_model | None | |
| hf_Phi-3-mini-4k-instruct | import_model | None | |
| hf_Phi-3.5-mini-instruct | import_model | None | |
| hf_Qwen1.5-0.5B-Chat | PASS | None | |
| hf_Qwen2-0.5B | PASS | None | |
| hf_Qwen2-7B-Instruct | import_model | None | |
| hf_Qwen2.5-0.5B-Instruct | PASS | None | |
| hf_Qwen2.5-1.5B-Instruct | import_model | None | |
| hf_Qwen2.5-7B-Instruct | import_model | None | |
| hf_really-tiny-falcon-testing | PASS | None | |
| hf_tiny-dummy-qwen2 | PASS | None | |
| hf_tiny-Qwen2ForCausalLM-2.5 | PASS | None | |
| hf_tiny-random-GemmaForCausalLM | PASS | None | |
| hf_tiny-random-LlamaForCausalLM | PASS | None | |
| hf_tiny-random-mistral | import_model | None | |
| hf_tiny-random-Phi3ForCausalLM | PASS | None | |
| hf_TinyLlama-1.1B-Chat-v1.0 | import_model | None | |
| hf_vicuna-7b-v1.5 | import_model | None | |
| hf_zephyr-7b-beta | import_model | None | |
