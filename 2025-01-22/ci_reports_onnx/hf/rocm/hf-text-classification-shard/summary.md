## Passing Summary

**TOTAL TESTS = 72**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 72 | 100.0% | 100.0% |
| IREE Compilation | 71 | 98.6% | 98.6% |
| Gold Inference | 67 | 93.1% | 94.4% |
| IREE Inference Invocation | 56 | 77.8% | 83.6% |
| Inference Comparison (PASS) | 56 | 77.8% | 100.0% |
## Fail Summary

**TOTAL TESTS = 72**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 1 | 1.4% |
| Gold Inference | 4 | 5.6% |
| IREE Inference Invocation | 11 | 15.3% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-text-classification-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-text-classification-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_51-languages-classifier | PASS | None | |
| hf_albert-xlarge-vitaminc-mnli | construct_inputs | None | |
| hf_autonlp-Gibberish-Detector-492513457 | PASS | None | |
| hf_bart-large-mnli | compilation | None | |
| hf_bert-base-multilingual-uncased-sentiment | PASS | None | |
| hf_bert-base-personality | PASS | None | |
| hf_bert-base-uncased-emotion | PASS | None | |
| hf_bert-base-uncased-hatexplain | PASS | None | |
| hf_bert-base-uncased-snli | PASS | None | |
| hf_bert-japanese-finetuned-sentiment | PASS | None | |
| hf_bert-tiny-finetuned-sms-spam-detection | PASS | None | |
| hf_bert-toxic-comment-classification | PASS | None | |
| hf_bert_turkish_sentiment | construct_inputs | None | |
| hf_bertweet-base-sentiment-analysis | PASS | None | |
| hf_beto-sentiment-analysis | PASS | None | |
| hf_bge-reranker-base | PASS | None | |
| hf_CentralBankRoBERTa-sentiment-classifier | construct_inputs | None | |
| hf_deberta-large-mnli | compiled_inference | None | |
| hf_deberta-v3-base-absa-v1.1 | compiled_inference | None | |
| hf_deberta-v3-base-injection | compiled_inference | None | |
| hf_DeBERTa-v3-base-mnli-fever-anli | compiled_inference | None | |
| hf_deberta-v3-base-zeroshot-v1.1-all-33 | compiled_inference | None | |
| hf_deberta-v3-large_boolq | compiled_inference | None | |
| hf_dehatebert-mono-english | PASS | None | |
| hf_dehatebert-mono-portugese | PASS | None | |
| hf_distilbert-base-multilingual-cased-sentiments-student | compiled_inference | None | |
| hf_distilbert-base-uncased-finetuned-sst-2-english | PASS | None | |
| hf_distilroberta-finetuned-financial-news-sentiment-analysis | PASS | None | |
| hf_emotion-english-distilroberta-base | PASS | None | |
| hf_emotion_text_classifier | PASS | None | |
| hf_english-abusive-MuRIL | PASS | None | |
| hf_finbert | PASS | None | |
| hf_finbert-tone | PASS | None | |
| hf_Gender-Classification | PASS | None | |
| hf_german-sentiment-bert | PASS | None | |
| hf_indonesian-roberta-base-sentiment-classifier | PASS | None | |
| hf_koelectra-small-v3-nsmc | PASS | None | |
| hf_mDeBERTa-v3-base-mnli-xnli | compiled_inference | None | |
| hf_MeaningBERT | PASS | None | |
| hf_ms-marco-electra-base | PASS | None | |
| hf_ms-marco-MiniLM-L-12-v2 | PASS | None | |
| hf_ms-marco-MiniLM-L-2-v2 | PASS | None | |
| hf_ms-marco-MiniLM-L-4-v2 | PASS | None | |
| hf_ms-marco-MiniLM-L-6-v2 | PASS | None | |
| hf_ms-marco-TinyBERT-L-2-v2 | PASS | None | |
| hf_mxbai-rerank-base-v1 | compiled_inference | None | |
| hf_mxbai-rerank-xsmall-v1 | compiled_inference | None | |
| hf_my_awesome_model | PASS | None | |
| hf_nli-deberta-v3-base | compiled_inference | None | |
| hf_NSFW_text_classifier | PASS | None | |
| hf_query_wellformedness_score | PASS | None | |
| hf_raceBERT-ethnicity | PASS | None | |
| hf_roberta-base-go_emotions | PASS | None | |
| hf_roberta-base-suicide-prediction-phr | PASS | None | |
| hf_roberta-hate-speech-dynabench-r4-target | PASS | None | |
| hf_roberta-large-mnli | PASS | None | |
| hf_robertuito-sentiment-analysis | construct_inputs | None | |
| hf_rubert-base-cased-nli-threeway | PASS | None | |
| hf_rubert-tiny2-russian-sentiment | PASS | None | |
| hf_Sentimental-Analysis | PASS | None | |
| hf_stsb-TinyBERT-L-4 | PASS | None | |
| hf_suicidality | PASS | None | |
| hf_tamil-codemixed-abusive-MuRIL | PASS | None | |
| hf_toxic-bert | PASS | None | |
| hf_toxic-comment-model | PASS | None | |
| hf_twitter-roberta-base-irony | PASS | None | |
| hf_twitter-roberta-base-sentiment | PASS | None | |
| hf_twitter-roberta-base-sentiment-latest | PASS | None | |
| hf_twitter-xlm-roberta-base-sentiment | PASS | None | |
| hf_twitter-xlm-roberta-base-sentiment-multilingual | PASS | None | |
| hf_unbiased-toxic-roberta | PASS | None | |
| hf_xlm-roberta-base-language-detection | PASS | None | |
