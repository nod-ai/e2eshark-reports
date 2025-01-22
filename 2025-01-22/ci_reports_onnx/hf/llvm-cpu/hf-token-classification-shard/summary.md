## Passing Summary

**TOTAL TESTS = 62**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 62 | 100.0% | 100.0% |
| IREE Compilation | 62 | 100.0% | 100.0% |
| Gold Inference | 57 | 91.9% | 91.9% |
| IREE Inference Invocation | 46 | 74.2% | 80.7% |
| Inference Comparison (PASS) | 46 | 74.2% | 100.0% |
## Fail Summary

**TOTAL TESTS = 62**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 5 | 8.1% |
| IREE Inference Invocation | 11 | 17.7% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-token-classification-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-token-classification-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_albert-tiny-chinese-ws | PASS | None | |
| hf_bcms-bertic-ner | PASS | None | |
| hf_bert-base-arabic-camelbert-mix-ner | PASS | None | |
| hf_bert-base-chinese-ner | PASS | None | |
| hf_bert-base-chinese-pos | PASS | None | |
| hf_bert-base-chinese-ws | PASS | None | |
| hf_bert-base-indonesian-NER | PASS | None | |
| hf_bert-base-japanese-v3-ner-wikipedia-dataset | PASS | None | |
| hf_bert-base-multilingual-cased-ner-hrl | PASS | None | |
| hf_bert-base-NER | PASS | None | |
| hf_bert-base-NER-uncased | PASS | None | |
| hf_bert-base-parsbert-ner-uncased | PASS | None | |
| hf_bert-base-romanian-ner | PASS | None | |
| hf_bert-base-swedish-cased-ner | PASS | None | |
| hf_bert-base-thai-upos | PASS | None | |
| hf_bert-base-turkish-cased-ner | PASS | None | |
| hf_bert-english-uncased-finetuned-pos | PASS | None | |
| hf_bert-fa-base-uncased-ner-peyma | PASS | None | |
| hf_bert-large-cased-finetuned-conll03-english | PASS | None | |
| hf_bert-large-NER | PASS | None | |
| hf_bert-large-uncased_med-ner | PASS | None | |
| hf_bert-spanish-cased-finetuned-ner | PASS | None | |
| hf_bert_cased_ner | PASS | None | |
| hf_biomedical-ner-all | PASS | None | |
| hf_bpmn-information-extraction-v2 | PASS | None | |
| hf_camembert-keyword-extractor | construct_inputs | None | |
| hf_camembert-ner | compiled_inference | None | |
| hf_camembert-ner-with-dates | construct_inputs | None | |
| hf_deberta-v3-base_finetuned_ai4privacy_v2 | compiled_inference | None | |
| hf_deberta_finetuned_pii | compiled_inference | None | |
| hf_deid_roberta_i2b2 | PASS | None | |
| hf_distilbert-base-cased-finetuned-conll03-english | compiled_inference | None | |
| hf_distilbert-base-multilingual-cased-ner-hrl | compiled_inference | None | |
| hf_distilbert-NER | compiled_inference | None | |
| hf_distilbert-SBD-en-judgements-laws | compiled_inference | None | |
| hf_distilcamembert-base-ner | compiled_inference | None | |
| hf_french-camembert-postag-model | construct_inputs | None | |
| hf_IndicNER | PASS | None | |
| hf_indobert-model-ner | PASS | None | |
| hf_indonesian-roberta-base-posp-tagger | PASS | None | |
| hf_ivila-row-layoutlm-finetuned-s2vl-v2 | native_inference | None | |
| hf_keyphrase-extraction-distilbert-inspec | compiled_inference | None | |
| hf_keyphrase-extraction-kbir-inspec | PASS | None | |
| hf_KoELECTRA-small-v3-modu-ner | PASS | None | |
| hf_llmlingua-2-bert-base-multilingual-cased-meetingbank | PASS | None | |
| hf_Medical-NER | compiled_inference | None | |
| hf_nbailab-base-ner-scandi | PASS | None | |
| hf_ner-bert-base-cased-pt-lenerbr | PASS | None | |
| hf_NER-Indian-xlm-roberta | PASS | None | |
| hf_ner-vietnamese-electra-base | PASS | None | |
| hf_nerkor-cars-onpp-hubert | PASS | None | |
| hf_piiranha-v1-detect-personal-information | compiled_inference | None | |
| hf_punctuate-all | PASS | None | |
| hf_robbert-v2-dutch-ner | construct_inputs | None | |
| hf_roberta-large-ner-english | PASS | None | |
| hf_roberta-large-ontonotes5 | PASS | None | |
| hf_stanford-deidentifier-base | PASS | None | |
| hf_tner-xlm-roberta-base-ontonotes5 | PASS | None | |
| hf_wikineural-multilingual-ner | PASS | None | |
| hf_xlm-roberta-base-ner-silvanus | PASS | None | |
| hf_xlm-roberta-ner-japanese | PASS | None | |
| hf_ZeroShotBioNER | PASS | None | |
