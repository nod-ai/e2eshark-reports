## Passing Summary

**TOTAL TESTS = 72**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 68 | 94.4% | 94.4% |
| IREE Compilation | 59 | 81.9% | 86.8% |
| Gold Inference | 6 | 8.3% | 10.2% |
| IREE Inference Invocation | 3 | 4.2% | 50.0% |
| Inference Comparison (PASS) | 3 | 4.2% | 100.0% |
## Fail Summary

**TOTAL TESTS = 72**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 4 | 5.6% |
| IREE Compilation | 9 | 12.5% |
| Gold Inference | 53 | 73.6% |
| IREE Inference Invocation | 3 | 4.2% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-fill-mask-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-fill-mask-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_albert-base-v2 | construct_inputs | None | |
| hf_albert-japanese-v2 | construct_inputs | None | |
| hf_all-mpnet-base-v1 | setup | None | |
| hf_ARBERTv2 | construct_inputs | None | |
| hf_astroBERT | construct_inputs | None | |
| hf_bert-base-5lang-cased | construct_inputs | None | |
| hf_bert-base-arabertv02 | construct_inputs | None | |
| hf_bert-base-cased | construct_inputs | None | |
| hf_bert-base-chinese | construct_inputs | None | |
| hf_bert-base-german-cased | construct_inputs | None | |
| hf_bert-base-indonesian-1.5G | construct_inputs | None | |
| hf_bert-base-italian-xxl-cased | construct_inputs | None | |
| hf_bert-base-italian-xxl-uncased | setup | None | |
| hf_bert-base-japanese | construct_inputs | None | |
| hf_bert-base-japanese-char | construct_inputs | None | |
| hf_bert-base-japanese-char-v2 | construct_inputs | None | |
| hf_bert-base-japanese-whole-word-masking | construct_inputs | None | |
| hf_bert-base-multilingual-cased | construct_inputs | None | |
| hf_bert-base-multilingual-uncased | construct_inputs | None | |
| hf_bert-base-portuguese-cased | construct_inputs | None | |
| hf_bert-base-spanish-wwm-uncased | construct_inputs | None | |
| hf_bert-base-uncased | construct_inputs | None | |
| hf_bert-kor-base | construct_inputs | None | |
| hf_bert-large-cased | construct_inputs | None | |
| hf_bert-large-portuguese-cased | construct_inputs | None | |
| hf_bert-large-uncased | construct_inputs | None | |
| hf_bertweet-base | compiled_inference | None | |
| hf_Bio_ClinicalBERT | construct_inputs | None | |
| hf_biobert-base-cased-v1.2 | construct_inputs | None | |
| hf_BiomedNLP-BiomedBERT-base-uncased-abstract | construct_inputs | None | |
| hf_BiomedNLP-BiomedBERT-base-uncased-abstract-fulltext | construct_inputs | None | |
| hf_camembert-base | construct_inputs | None | |
| hf_ChemBERTa-77M-MLM | construct_inputs | None | |
| hf_chinese-roberta-wwm-ext | construct_inputs | None | |
| hf_codebert-base-mlm | construct_inputs | None | |
| hf_codebert-java | construct_inputs | None | |
| hf_codebert-python | construct_inputs | None | |
| hf_deberta-base | compilation | None | |
| hf_deberta-v2-base-japanese | compilation | None | |
| hf_deberta-v2-base-japanese-char-wwm | compilation | None | |
| hf_deberta-v3-base | compilation | None | |
| hf_deberta-v3-large | compilation | None | |
| hf_deberta-v3-small | compilation | None | |
| hf_deberta-v3-xsmall | compilation | None | |
| hf_distilbert-base-cased | PASS | None | |
| hf_distilbert-base-multilingual-cased | PASS | None | |
| hf_distilbert-base-uncased | PASS | None | |
| hf_distilroberta-base | construct_inputs | None | |
| hf_efficient-splade-VI-BT-large-doc | construct_inputs | None | |
| hf_efficient-splade-VI-BT-large-query | construct_inputs | None | |
| hf_esm2_t12_35M_UR50D | construct_inputs | None | |
| hf_esm2_t30_150M_UR50D | construct_inputs | None | |
| hf_esm2_t36_3B_UR50D | import_model | None | |
| hf_esm2_t6_8M_UR50D | construct_inputs | None | |
| hf_IndicBERTv2-MLM-only | construct_inputs | None | |
| hf_legal-bert-base-uncased | construct_inputs | None | |
| hf_legal-bert-small-uncased | construct_inputs | None | |
| hf_mdeberta-v3-base | compilation | None | |
| hf_multi-qa-mpnet-base-cos-v1 | setup | None | |
| hf_opensearch-neural-sparse-encoding-doc-v2-distill | setup | None | |
| hf_phobert-base | compiled_inference | None | |
| hf_phobert-base-v2 | compiled_inference | None | |
| hf_prot_bert | construct_inputs | None | |
| hf_robbert-v2-dutch-base | construct_inputs | None | |
| hf_robeczech-base | construct_inputs | None | |
| hf_roberta-base | construct_inputs | None | |
| hf_roberta-large | construct_inputs | None | |
| hf_splade-cocondenser-ensembledistil | construct_inputs | None | |
| hf_splade-cocondenser-selfdistil | construct_inputs | None | |
| hf_Splade_PP_en_v1 | construct_inputs | None | |
| hf_wangchanberta-base-att-spm-uncased | construct_inputs | None | |
| hf_xlm-roberta-base | construct_inputs | None | |
