## Passing Summary

**TOTAL TESTS = 57**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 0 | 0.0% | 0.0% |
| IREE Compilation | 0 | 0.0% | 0.0% |
| Gold Inference | 0 | 0.0% | 0.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 57**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 57 | 100.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-question-answering-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-question-answering-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_albert-base-v2-squad2 | setup | None | |
| hf_bert-base-cased-squad-v1.1-portuguese | setup | None | |
| hf_bert-base-cased-squad2 | setup | None | |
| hf_bert-base-spanish-wwm-cased-finetuned-spa-squad2-es | setup | None | |
| hf_bert-base-turkish-squad | setup | None | |
| hf_bert-base-uncased-squad-v1 | setup | None | |
| hf_bert-base-uncased-squad2 | setup | None | |
| hf_bert-extractive-qa-large-project | setup | None | |
| hf_bert-large-cased-squad-v1.1-portuguese | setup | None | |
| hf_bert-large-cased-whole-word-masking-finetuned-squad | setup | None | |
| hf_bert-large-finetuned-squad2 | setup | None | |
| hf_bert-large-uncased-whole-word-masking-finetuned-squad | setup | None | |
| hf_bert-large-uncased-whole-word-masking-squad2 | setup | None | |
| hf_bert-tiny-finetuned-squadv2 | setup | None | |
| hf_bertserini-bert-base-squad | setup | None | |
| hf_biobert-base-cased-v1.1-squad | setup | None | |
| hf_biobert-large-cased-v1.1-squad | setup | None | |
| hf_biobert-v1.1-biomedicalQuestionAnswering | setup | None | |
| hf_BioLinkBERT-base | setup | None | |
| hf_BioLinkBERT-large | setup | None | |
| hf_camembert-base-squadFR-fquad-piaf | setup | None | |
| hf_deberta-v3-base-squad2 | setup | None | |
| hf_deberta-v3-large-squad2 | setup | None | |
| hf_distilbert-base-cased-distilled-squad | setup | None | |
| hf_distilbert-base-uncased-distilled-squad | setup | None | |
| hf_distilbert-extractive-qa-large-project | setup | None | |
| hf_distilbert-extractive-qa-project | setup | None | |
| hf_distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es | setup | None | |
| hf_dynamic_tinybert | setup | None | |
| hf_electra_large_discriminator_squad2_512 | setup | None | |
| hf_gelectra-base-germanquad | setup | None | |
| hf_gelectra-large-germanquad | setup | None | |
| hf_indobert-lite-squad | setup | None | |
| hf_Indobert-QA | setup | None | |
| hf_koelectra-small-v2-distilled-korquad-384 | setup | None | |
| hf_LinkBERT-large | setup | None | |
| hf_mdeberta-v3-base-squad2 | setup | None | |
| hf_minilm-uncased-squad2 | setup | None | |
| hf_mobilebert-uncased-squad-v2 | setup | None | |
| hf_question-answering-qa-may-12-tablang-LOCAL | setup | None | |
| hf_question-answering-roberta-base-s-v2 | setup | None | |
| hf_roberta-base-chinese-extractive-qa | setup | None | |
| hf_roberta-base-on-cuad | setup | None | |
| hf_roberta-base-squad2 | setup | None | |
| hf_roberta-base-squad2-distilled | setup | None | |
| hf_roberta-large-squad2 | setup | None | |
| hf_rubert_large_squad_2 | setup | None | |
| hf_sapbert-from-pubmedbert-squad2 | setup | None | |
| hf_splinter-base | setup | None | |
| hf_splinter-base-qass | setup | None | |
| hf_test-demo-qa | setup | None | |
| hf_test-demo-qa-with-roberta | setup | None | |
| hf_tiny-distilbert-base-cased-distilled-squad | setup | None | |
| hf_tinyroberta-squad2 | setup | None | |
| hf_WSPAlign-ft-kftt | setup | None | |
| hf_xlm-roberta-base-squad2 | setup | None | |
| hf_xlm-roberta-base-squad2-distilled | setup | None | |
