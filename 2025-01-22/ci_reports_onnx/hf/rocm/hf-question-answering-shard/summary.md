## Passing Summary

**TOTAL TESTS = 57**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 57 | 100.0% | 100.0% |
| IREE Compilation | 55 | 96.5% | 96.5% |
| Gold Inference | 52 | 91.2% | 94.5% |
| IREE Inference Invocation | 45 | 78.9% | 86.5% |
| Inference Comparison (PASS) | 45 | 78.9% | 100.0% |
## Fail Summary

**TOTAL TESTS = 57**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 2 | 3.5% |
| Gold Inference | 3 | 5.3% |
| IREE Inference Invocation | 7 | 12.3% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-question-answering-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-question-answering-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_albert-base-v2-squad2 | construct_inputs | None | |
| hf_bert-base-cased-squad-v1.1-portuguese | PASS | None | |
| hf_bert-base-cased-squad2 | PASS | None | |
| hf_bert-base-spanish-wwm-cased-finetuned-spa-squad2-es | PASS | None | |
| hf_bert-base-turkish-squad | PASS | None | |
| hf_bert-base-uncased-squad-v1 | PASS | None | |
| hf_bert-base-uncased-squad2 | PASS | None | |
| hf_bert-extractive-qa-large-project | PASS | None | |
| hf_bert-large-cased-squad-v1.1-portuguese | PASS | None | |
| hf_bert-large-cased-whole-word-masking-finetuned-squad | PASS | None | |
| hf_bert-large-finetuned-squad2 | PASS | None | |
| hf_bert-large-uncased-whole-word-masking-finetuned-squad | PASS | None | |
| hf_bert-large-uncased-whole-word-masking-squad2 | PASS | None | |
| hf_bert-tiny-finetuned-squadv2 | PASS | None | |
| hf_bertserini-bert-base-squad | PASS | None | |
| hf_biobert-base-cased-v1.1-squad | PASS | None | |
| hf_biobert-large-cased-v1.1-squad | PASS | None | |
| hf_biobert-v1.1-biomedicalQuestionAnswering | PASS | None | |
| hf_BioLinkBERT-base | PASS | None | |
| hf_BioLinkBERT-large | PASS | None | |
| hf_camembert-base-squadFR-fquad-piaf | construct_inputs | None | |
| hf_deberta-v3-base-squad2 | compiled_inference | None | |
| hf_deberta-v3-large-squad2 | compiled_inference | None | |
| hf_distilbert-base-cased-distilled-squad | compiled_inference | None | |
| hf_distilbert-base-uncased-distilled-squad | compiled_inference | None | |
| hf_distilbert-extractive-qa-large-project | PASS | None | |
| hf_distilbert-extractive-qa-project | compiled_inference | None | |
| hf_distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es | PASS | None | |
| hf_dynamic_tinybert | PASS | None | |
| hf_electra_large_discriminator_squad2_512 | PASS | None | |
| hf_gelectra-base-germanquad | PASS | None | |
| hf_gelectra-large-germanquad | PASS | None | |
| hf_indobert-lite-squad | PASS | None | |
| hf_Indobert-QA | PASS | None | |
| hf_koelectra-small-v2-distilled-korquad-384 | PASS | None | |
| hf_LinkBERT-large | PASS | None | |
| hf_mdeberta-v3-base-squad2 | compiled_inference | None | |
| hf_minilm-uncased-squad2 | PASS | None | |
| hf_mobilebert-uncased-squad-v2 | PASS | None | |
| hf_question-answering-qa-may-12-tablang-LOCAL | PASS | None | |
| hf_question-answering-roberta-base-s-v2 | PASS | None | |
| hf_roberta-base-chinese-extractive-qa | construct_inputs | None | |
| hf_roberta-base-on-cuad | PASS | None | |
| hf_roberta-base-squad2 | PASS | None | |
| hf_roberta-base-squad2-distilled | PASS | None | |
| hf_roberta-large-squad2 | PASS | None | |
| hf_rubert_large_squad_2 | PASS | None | |
| hf_sapbert-from-pubmedbert-squad2 | PASS | None | |
| hf_splinter-base | compilation | None | |
| hf_splinter-base-qass | compilation | None | |
| hf_test-demo-qa | PASS | None | |
| hf_test-demo-qa-with-roberta | PASS | None | |
| hf_tiny-distilbert-base-cased-distilled-squad | compiled_inference | None | |
| hf_tinyroberta-squad2 | PASS | None | |
| hf_WSPAlign-ft-kftt | PASS | None | |
| hf_xlm-roberta-base-squad2 | PASS | None | |
| hf_xlm-roberta-base-squad2-distilled | PASS | None | |
