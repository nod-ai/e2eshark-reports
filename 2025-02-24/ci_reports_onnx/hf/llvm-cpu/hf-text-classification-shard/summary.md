## Passing Summary

**TOTAL TESTS = 72**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 68 | 94.4% | 94.4% |
| IREE Compilation | 60 | 83.3% | 88.2% |
| Gold Inference | 3 | 4.2% | 5.0% |
| IREE Inference Invocation | 2 | 2.8% | 66.7% |
| Inference Comparison (PASS) | 2 | 2.8% | 100.0% |
## Fail Summary

**TOTAL TESTS = 72**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 4 | 5.6% |
| IREE Compilation | 8 | 11.1% |
| Gold Inference | 57 | 79.2% |
| IREE Inference Invocation | 1 | 1.4% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-text-classification-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-text-classification-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_51-languages-classifier | construct_inputs | None | |
| hf_albert-xlarge-vitaminc-mnli | construct_inputs | None | |
| hf_autonlp-Gibberish-Detector-492513457 | construct_inputs | None | |
| hf_bart-large-mnli | construct_inputs | None | |
| hf_bert-base-multilingual-uncased-sentiment | construct_inputs | None | |
| hf_bert-base-personality | construct_inputs | None | |
| hf_bert-base-uncased-emotion | construct_inputs | None | |
| hf_bert-base-uncased-hatexplain | construct_inputs | None | |
| hf_bert-base-uncased-snli | construct_inputs | None | |
| hf_bert-japanese-finetuned-sentiment | construct_inputs | None | |
| hf_bert-tiny-finetuned-sms-spam-detection | construct_inputs | None | |
| hf_bert-toxic-comment-classification | construct_inputs | None | |
| hf_bert_turkish_sentiment | construct_inputs | None | |
| hf_bertweet-base-sentiment-analysis | compiled_inference | None | |
| hf_beto-sentiment-analysis | construct_inputs | None | |
| hf_bge-reranker-base | construct_inputs | None | |
| hf_CentralBankRoBERTa-sentiment-classifier | construct_inputs | None | |
| hf_deberta-large-mnli | compilation | None | |
| hf_deberta-v3-base-absa-v1.1 | compilation | None | |
| hf_deberta-v3-base-injection | compilation | None | |
| hf_DeBERTa-v3-base-mnli-fever-anli | compilation | None | |
| hf_deberta-v3-base-zeroshot-v1.1-all-33 | compilation | None | |
| hf_deberta-v3-large_boolq | compilation | None | |
| hf_dehatebert-mono-english | construct_inputs | None | |
| hf_dehatebert-mono-portugese | construct_inputs | None | |
| hf_distilbert-base-multilingual-cased-sentiments-student | PASS | None | |
| hf_distilbert-base-uncased-finetuned-sst-2-english | PASS | None | |
| hf_distilroberta-finetuned-financial-news-sentiment-analysis | construct_inputs | None | |
| hf_emotion-english-distilroberta-base | construct_inputs | None | |
| hf_emotion_text_classifier | construct_inputs | None | |
| hf_english-abusive-MuRIL | construct_inputs | None | |
| hf_finbert | construct_inputs | None | |
| hf_finbert-tone | construct_inputs | None | |
| hf_Gender-Classification | construct_inputs | None | |
| hf_german-sentiment-bert | construct_inputs | None | |
| hf_indonesian-roberta-base-sentiment-classifier | construct_inputs | None | |
| hf_koelectra-small-v3-nsmc | construct_inputs | None | |
| hf_mDeBERTa-v3-base-mnli-xnli | compilation | None | |
| hf_MeaningBERT | construct_inputs | None | |
| hf_ms-marco-electra-base | construct_inputs | None | |
| hf_ms-marco-MiniLM-L-12-v2 | construct_inputs | None | |
| hf_ms-marco-MiniLM-L-2-v2 | construct_inputs | None | |
| hf_ms-marco-MiniLM-L-4-v2 | construct_inputs | None | |
| hf_ms-marco-MiniLM-L-6-v2 | construct_inputs | None | |
| hf_ms-marco-TinyBERT-L-2-v2 | construct_inputs | None | |
| hf_mxbai-rerank-base-v1 | setup | None | |
| hf_mxbai-rerank-xsmall-v1 | setup | None | |
| hf_my_awesome_model | construct_inputs | None | |
| hf_nli-deberta-v3-base | compilation | None | |
| hf_NSFW_text_classifier | construct_inputs | None | |
| hf_query_wellformedness_score | construct_inputs | None | |
| hf_raceBERT-ethnicity | construct_inputs | None | |
| hf_roberta-base-go_emotions | construct_inputs | None | |
| hf_roberta-base-suicide-prediction-phr | construct_inputs | None | |
| hf_roberta-hate-speech-dynabench-r4-target | construct_inputs | None | |
| hf_roberta-large-mnli | construct_inputs | None | |
| hf_robertuito-sentiment-analysis | construct_inputs | None | |
| hf_rubert-base-cased-nli-threeway | setup | None | |
| hf_rubert-tiny2-russian-sentiment | setup | None | |
| hf_Sentimental-Analysis | construct_inputs | None | |
| hf_stsb-TinyBERT-L-4 | construct_inputs | None | |
| hf_suicidality | construct_inputs | None | |
| hf_tamil-codemixed-abusive-MuRIL | construct_inputs | None | |
| hf_toxic-bert | construct_inputs | None | |
| hf_toxic-comment-model | construct_inputs | None | |
| hf_twitter-roberta-base-irony | construct_inputs | None | |
| hf_twitter-roberta-base-sentiment | construct_inputs | None | |
| hf_twitter-roberta-base-sentiment-latest | construct_inputs | None | |
| hf_twitter-xlm-roberta-base-sentiment | construct_inputs | None | |
| hf_twitter-xlm-roberta-base-sentiment-multilingual | construct_inputs | None | |
| hf_unbiased-toxic-roberta | construct_inputs | None | |
| hf_xlm-roberta-base-language-detection | construct_inputs | None | |
