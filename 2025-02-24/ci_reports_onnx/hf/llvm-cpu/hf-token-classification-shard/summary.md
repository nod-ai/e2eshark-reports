## Passing Summary

**TOTAL TESTS = 62**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 61 | 98.4% | 98.4% |
| IREE Compilation | 57 | 91.9% | 93.4% |
| Gold Inference | 8 | 12.9% | 14.0% |
| IREE Inference Invocation | 8 | 12.9% | 100.0% |
| Inference Comparison (PASS) | 8 | 12.9% | 100.0% |
## Fail Summary

**TOTAL TESTS = 62**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 1 | 1.6% |
| IREE Compilation | 4 | 6.5% |
| Gold Inference | 49 | 79.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-token-classification-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-token-classification-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_albert-tiny-chinese-ws | construct_inputs | None | |
| hf_bcms-bertic-ner | construct_inputs | None | |
| hf_bert-base-arabic-camelbert-mix-ner | construct_inputs | None | |
| hf_bert-base-chinese-ner | construct_inputs | None | |
| hf_bert-base-chinese-pos | construct_inputs | None | |
| hf_bert-base-chinese-ws | construct_inputs | None | |
| hf_bert-base-indonesian-NER | construct_inputs | None | |
| hf_bert-base-japanese-v3-ner-wikipedia-dataset | construct_inputs | None | |
| hf_bert-base-multilingual-cased-ner-hrl | construct_inputs | None | |
| hf_bert-base-NER | construct_inputs | None | |
| hf_bert-base-NER-uncased | construct_inputs | None | |
| hf_bert-base-parsbert-ner-uncased | construct_inputs | None | |
| hf_bert-base-romanian-ner | construct_inputs | None | |
| hf_bert-base-swedish-cased-ner | construct_inputs | None | |
| hf_bert-base-thai-upos | construct_inputs | None | |
| hf_bert-base-turkish-cased-ner | construct_inputs | None | |
| hf_bert-english-uncased-finetuned-pos | construct_inputs | None | |
| hf_bert-fa-base-uncased-ner-peyma | construct_inputs | None | |
| hf_bert-large-cased-finetuned-conll03-english | construct_inputs | None | |
| hf_bert-large-NER | construct_inputs | None | |
| hf_bert-large-uncased_med-ner | construct_inputs | None | |
| hf_bert-spanish-cased-finetuned-ner | construct_inputs | None | |
| hf_bert_cased_ner | construct_inputs | None | |
| hf_biomedical-ner-all | construct_inputs | None | |
| hf_bpmn-information-extraction-v2 | construct_inputs | None | |
| hf_camembert-keyword-extractor | construct_inputs | None | |
| hf_camembert-ner | PASS | None | |
| hf_camembert-ner-with-dates | construct_inputs | None | |
| hf_deberta-v3-base_finetuned_ai4privacy_v2 | compilation | None | |
| hf_deberta_finetuned_pii | compilation | None | |
| hf_deid_roberta_i2b2 | setup | None | |
| hf_distilbert-base-cased-finetuned-conll03-english | PASS | None | |
| hf_distilbert-base-multilingual-cased-ner-hrl | PASS | None | |
| hf_distilbert-NER | PASS | None | |
| hf_distilbert-SBD-en-judgements-laws | PASS | None | |
| hf_distilcamembert-base-ner | PASS | None | |
| hf_french-camembert-postag-model | construct_inputs | None | |
| hf_IndicNER | construct_inputs | None | |
| hf_indobert-model-ner | construct_inputs | None | |
| hf_indonesian-roberta-base-posp-tagger | construct_inputs | None | |
| hf_ivila-row-layoutlm-finetuned-s2vl-v2 | PASS | None | |
| hf_keyphrase-extraction-distilbert-inspec | PASS | None | |
| hf_keyphrase-extraction-kbir-inspec | construct_inputs | None | |
| hf_KoELECTRA-small-v3-modu-ner | construct_inputs | None | |
| hf_llmlingua-2-bert-base-multilingual-cased-meetingbank | construct_inputs | None | |
| hf_Medical-NER | compilation | None | |
| hf_nbailab-base-ner-scandi | construct_inputs | None | |
| hf_ner-bert-base-cased-pt-lenerbr | construct_inputs | None | |
| hf_NER-Indian-xlm-roberta | construct_inputs | None | |
| hf_ner-vietnamese-electra-base | construct_inputs | None | |
| hf_nerkor-cars-onpp-hubert | construct_inputs | None | |
| hf_piiranha-v1-detect-personal-information | compilation | None | |
| hf_punctuate-all | construct_inputs | None | |
| hf_robbert-v2-dutch-ner | construct_inputs | None | |
| hf_roberta-large-ner-english | construct_inputs | None | |
| hf_roberta-large-ontonotes5 | construct_inputs | None | |
| hf_stanford-deidentifier-base | construct_inputs | None | |
| hf_tner-xlm-roberta-base-ontonotes5 | construct_inputs | None | |
| hf_wikineural-multilingual-ner | construct_inputs | None | |
| hf_xlm-roberta-base-ner-silvanus | construct_inputs | None | |
| hf_xlm-roberta-ner-japanese | construct_inputs | None | |
| hf_ZeroShotBioNER | construct_inputs | None | |
