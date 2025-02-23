# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.2351|108.9529|-1.2822|-1.16%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.9124|109.5655|-1.3469|-1.21%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|474.3757|461.784|-12.5917|-2.65%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.2366|59.9867|-1.2499|-2.04%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.9234|61.6662|-1.2571|-2.0%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|246.2922|242.0217|-4.2705|-1.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.3341|35.3197|-1.0143|-2.79%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.0264|1.9542|-0.0722|-3.56%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9587|18.9905|0.0319|0.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.868|7.0848|-0.7832|-9.95%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.6891|27.907|1.2179|4.56%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7729|4.8029|0.03|0.63%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.9918|43.8047|-0.1871|-0.43%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.4587|45.7416|-1.7171|-3.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.1472|17.4701|-0.6772|-3.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.8135|9.6666|1.8531|23.72%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8831|4.9073|0.0242|0.5%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.2699|32.2877|-0.9822|-2.95%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.4256|53.5367|-0.889|-1.63%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|71.2485|68.8733|-2.3751|-3.33%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|28.6102|12.4797|-16.1304|-56.38%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3225|12.4351|0.1125|0.91%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.269|19.2017|-0.0673|-0.35%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9017|12.8994|-0.0023|-0.02%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.7607|13.4301|-0.3307|-2.4%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0129|20.895|-0.1179|-0.56%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.9815|66.1773|-1.8042|-2.65%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.3621|97.6961|-2.666|-2.66%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|141.3428|137.6437|-3.6991|-2.62%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.7623|14.4424|-0.3199|-2.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.8574|16.9229|0.0655|0.39%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.5986|25.0174|-0.5812|-2.27%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.5262|19.0719|-0.4543|-2.33%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3496|27.3852|0.0356|0.13%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|39.9742|76.0414|36.0673|90.23%|

## 12 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnextv2_base.fcmae_ft_in1k|PASS|Numerics|
|maxvit_large_tf_224.in1k|PASS|Numerics|
|model--bert-finetuned-squad--MyMild|PASS|Numerics|
|model--bert-finetuned-squad--SiraH|PASS|Numerics|
|model--bert-finetuned-squad--jatinshah|PASS|Numerics|
|model--bert-large-NER--51la5|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-imdb--sahn|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad-frozen-v2--ericRosello|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.05_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--Namig|PASS|Numerics|
|model--hebrew_poetry-gpt_neo-small--Norod78|PASS|Numerics|
|xcit_medium_24_p8_384_dist|PASS|Numerics|

## 17 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large.fb_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_4_384|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--bert-large-uncased-en-ner--n6ai|Numerics|PASS|
|model--bert-large-uncased-finetuned-ner--Jorgeutd|Numerics|PASS|
|model--bert-large-uncased-whole-word-masking-squad2--deepset|Numerics|PASS|
|model--camembert-base-squadFR-fquad-piaf--etalab-ia|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--aaraki|Numerics|PASS|
|model--expanded-multilingual-ner--gamzenurmadan|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--aneeshmb02|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--kosec39|Numerics|PASS|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|Numerics|PASS|
|model--roberta-base-finetuned-ner--dominiqueblok|Numerics|PASS|
|swin_s3_small_224.ms_in1k|Numerics|PASS|
|xcit_small_24_p16_224_dist|Numerics|PASS|

