## Passing Summary

**TOTAL TESTS = 57**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 53 | 93.0% | 93.0% |
| IREE Compilation | 53 | 93.0% | 100.0% |
| Gold Inference | 49 | 86.0% | 92.5% |
| IREE Inference Invocation | 39 | 68.4% | 79.6% |
| Inference Comparison (PASS) | 39 | 68.4% | 100.0% |
## Fail Summary

**TOTAL TESTS = 57**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 4 | 7.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 4 | 7.0% |
| IREE Inference Invocation | 10 | 17.5% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-multiple-choice-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-multiple-choice-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_1_microsoft_deberta_V1.0 | PASS | None | |
| hf_1_microsoft_deberta_V1.1 | PASS | None | |
| hf_bert-base-japanese-v3-jcommonsenseqa | PASS | None | |
| hf_bert-base-uncased-e_CARE | PASS | None | |
| hf_bert-base-uncased-Figurative_Language | PASS | None | |
| hf_bert-base-uncased-finetune-kggpu | PASS | None | |
| hf_bert-base-uncased-finetuned-swag | PASS | None | |
| hf_bert-base-uncased-Vitamin_C_Fact_Verification | PASS | None | |
| hf_bert_base_swag_model | PASS | None | |
| hf_bert_multiple_choice | PASS | None | |
| hf_bert_science_multiple_choice | PASS | None | |
| hf_checkpoints_10_1_microsoft_deberta_V1.1_384 | PASS | None | |
| hf_checkpoints_1_16 | PASS | None | |
| hf_checkpoints_26_9_microsoft_deberta_21_9 | PASS | None | |
| hf_checkpoints_28_9_microsoft_deberta_V2 | PASS | None | |
| hf_checkpoints_28_9_microsoft_deberta_V4 | PASS | None | |
| hf_checkpoints_28_9_microsoft_deberta_V5 | PASS | None | |
| hf_checkpoints_29_9_microsoft_deberta_V1 | PASS | None | |
| hf_checkpoints_30_9_microsoft_deberta_V1.0_384 | PASS | None | |
| hf_checkpoints_3_14 | compiled_inference | None | |
| hf_chinese_paragraph_bert-ext | PASS | None | |
| hf_content | compiled_inference | None | |
| hf_COPA_10_shot | PASS | None | |
| hf_COPA_albert_base_finetuned | construct_inputs | None | |
| hf_COPA_Bert_Base_Uncased_Finetuned | PASS | None | |
| hf_CRAB_bert_base_uncased_finetuned | PASS | None | |
| hf_deberta-v3-large_test | PASS | None | |
| hf_deberta-v3-large_test_9e-6 | PASS | None | |
| hf_Debertalarg_model_multichoice_Version2 | compiled_inference | None | |
| hf_distilbert_distilbert-base-uncased-15-epoch | compiled_inference | None | |
| hf_distilbert_multiple_choice | compiled_inference | None | |
| hf_distilbert_science_multiple_choice | compiled_inference | None | |
| hf_e_care_albert_base_finetuned | construct_inputs | None | |
| hf_e_care_bert_base_uncased_finetuned | PASS | None | |
| hf_electra-base-fp16 | PASS | None | |
| hf_electra-base-multiple-choice-v2 | PASS | None | |
| hf_electra_multiple_choice | PASS | None | |
| hf_fine-tuned-MoritzLaurer-deberta-v3-large-zeroshot-v2.0-arceasy | setup | None | |
| hf_finetuned-bert-piqa | PASS | None | |
| hf_kda-albert-xxlarge-v2-race | construct_inputs | None | |
| hf_KUCI_albert_base_Finetuned | construct_inputs | None | |
| hf_KUCI_Bert_Base_Finetuned | PASS | None | |
| hf_LLM | PASS | None | |
| hf_llm-mdeberta-v3-swag | PASS | None | |
| hf_mbert-base-parsinlu-multiple-choice | PASS | None | |
| hf_mcQA_model_bert | PASS | None | |
| hf_mDeBERTa-v3-xnli-ft-bs-multiple-choice | compiled_inference | None | |
| hf_Multiple_Choice | setup | None | |
| hf_Multiple_Choice_EN | setup | None | |
| hf_multiple_choice_model | setup | None | |
| hf_my_awesome_swag_model | PASS | None | |
| hf_NLP_HW3 | PASS | None | |
| hf_output | compiled_inference | None | |
| hf_parsbert-base-parsinlu-multiple-choice | PASS | None | |
| hf_phobert-base-finetuned | compiled_inference | None | |
| hf_phobert-large-finetuned | compiled_inference | None | |
| hf_wikibert-base-parsinlu-multiple-choice | PASS | None | |
