## Passing Summary

**TOTAL TESTS = 57**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 57 | 100.0% | 100.0% |
| IREE Compilation | 52 | 91.2% | 91.2% |
| Gold Inference | 4 | 7.0% | 7.7% |
| IREE Inference Invocation | 4 | 7.0% | 100.0% |
| Inference Comparison (PASS) | 4 | 7.0% | 100.0% |
## Fail Summary

**TOTAL TESTS = 57**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 8.8% |
| Gold Inference | 48 | 84.2% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-question-answering-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-question-answering-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_albert-base-v2-squad2 | construct_inputs | None | |
| hf_bert-base-cased-squad-v1.1-portuguese | construct_inputs | None | |
| hf_bert-base-cased-squad2 | construct_inputs | None | |
| hf_bert-base-spanish-wwm-cased-finetuned-spa-squad2-es | construct_inputs | None | |
| hf_bert-base-turkish-squad | construct_inputs | None | |
| hf_bert-base-uncased-squad-v1 | construct_inputs | None | |
| hf_bert-base-uncased-squad2 | construct_inputs | None | |
| hf_bert-extractive-qa-large-project | construct_inputs | None | |
| hf_bert-large-cased-squad-v1.1-portuguese | construct_inputs | None | |
| hf_bert-large-cased-whole-word-masking-finetuned-squad | construct_inputs | None | |
| hf_bert-large-finetuned-squad2 | construct_inputs | None | |
| hf_bert-large-uncased-whole-word-masking-finetuned-squad | construct_inputs | None | |
| hf_bert-large-uncased-whole-word-masking-squad2 | construct_inputs | None | |
| hf_bert-tiny-finetuned-squadv2 | construct_inputs | None | |
| hf_bertserini-bert-base-squad | construct_inputs | None | |
| hf_biobert-base-cased-v1.1-squad | construct_inputs | None | |
| hf_biobert-large-cased-v1.1-squad | construct_inputs | None | |
| hf_biobert-v1.1-biomedicalQuestionAnswering | construct_inputs | None | |
| hf_BioLinkBERT-base | construct_inputs | None | |
| hf_BioLinkBERT-large | construct_inputs | None | |
| hf_camembert-base-squadFR-fquad-piaf | construct_inputs | None | |
| hf_deberta-v3-base-squad2 | compilation | None | |
| hf_deberta-v3-large-squad2 | compilation | None | |
| hf_distilbert-base-cased-distilled-squad | PASS | None | |
| hf_distilbert-base-uncased-distilled-squad | PASS | None | |
| hf_distilbert-extractive-qa-large-project | construct_inputs | None | |
| hf_distilbert-extractive-qa-project | PASS | None | |
| hf_distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es | construct_inputs | None | |
| hf_dynamic_tinybert | construct_inputs | None | |
| hf_electra_large_discriminator_squad2_512 | construct_inputs | None | |
| hf_gelectra-base-germanquad | construct_inputs | None | |
| hf_gelectra-large-germanquad | construct_inputs | None | |
| hf_indobert-lite-squad | construct_inputs | None | |
| hf_Indobert-QA | construct_inputs | None | |
| hf_koelectra-small-v2-distilled-korquad-384 | construct_inputs | None | |
| hf_LinkBERT-large | construct_inputs | None | |
| hf_mdeberta-v3-base-squad2 | compilation | None | |
| hf_minilm-uncased-squad2 | construct_inputs | None | |
| hf_mobilebert-uncased-squad-v2 | construct_inputs | None | |
| hf_question-answering-qa-may-12-tablang-LOCAL | construct_inputs | None | |
| hf_question-answering-roberta-base-s-v2 | construct_inputs | None | |
| hf_roberta-base-chinese-extractive-qa | construct_inputs | None | |
| hf_roberta-base-on-cuad | construct_inputs | None | |
| hf_roberta-base-squad2 | construct_inputs | None | |
| hf_roberta-base-squad2-distilled | construct_inputs | None | |
| hf_roberta-large-squad2 | construct_inputs | None | |
| hf_rubert_large_squad_2 | construct_inputs | None | |
| hf_sapbert-from-pubmedbert-squad2 | construct_inputs | None | |
| hf_splinter-base | compilation | None | |
| hf_splinter-base-qass | compilation | None | |
| hf_test-demo-qa | construct_inputs | None | |
| hf_test-demo-qa-with-roberta | construct_inputs | None | |
| hf_tiny-distilbert-base-cased-distilled-squad | PASS | None | |
| hf_tinyroberta-squad2 | construct_inputs | None | |
| hf_WSPAlign-ft-kftt | construct_inputs | None | |
| hf_xlm-roberta-base-squad2 | construct_inputs | None | |
| hf_xlm-roberta-base-squad2-distilled | construct_inputs | None | |
