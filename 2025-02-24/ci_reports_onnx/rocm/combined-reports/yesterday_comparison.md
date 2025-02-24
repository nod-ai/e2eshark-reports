# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|108.9529|119.1593|10.2064|9.37%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|109.5655|108.584|-0.9816|-0.9%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|461.784|464.206|2.4221|0.52%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.9867|59.3619|-0.6248|-1.04%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.6662|61.2884|-0.3779|-0.61%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|242.0217|240.009|-2.0127|-0.83%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.3197|35.3545|0.0348|0.1%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.9542|1.7219|-0.2323|-11.89%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9905|18.9317|-0.0588|-0.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0848|7.0204|-0.0644|-0.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|27.907|31.3692|3.4622|12.41%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8029|4.8272|0.0243|0.51%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.8047|44.3811|0.5764|1.32%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.7416|45.7584|0.0168|0.04%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.4701|17.3311|-0.139|-0.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.6666|9.6754|0.0089|0.09%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9073|4.9087|0.0013|0.03%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2877|32.2987|0.011|0.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.5367|53.5123|-0.0243|-0.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|68.8733|70.3283|1.4549|2.11%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4797|12.0656|-0.4141|-3.32%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4351|12.4153|-0.0198|-0.16%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2017|19.2507|0.049|0.26%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8994|12.8689|-0.0305|-0.24%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4301|13.5278|0.0977|0.73%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.895|20.7159|-0.1791|-0.86%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.1773|66.0798|-0.0975|-0.15%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.6961|99.01|1.3139|1.34%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|137.6437|138.8489|1.2053|0.88%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4424|14.5552|0.1128|0.78%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.9229|16.3802|-0.5427|-3.21%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.0174|24.9511|-0.0663|-0.26%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.0719|18.8773|-0.1946|-1.02%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3852|26.678|-0.7072|-2.58%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|76.0414|38.9209|-37.1205|-48.82%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|VGG19_vaiq|PASS|Numerics|
|flexivit_base.600ep_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_16_384|PASS|Numerics|
|model--GPyT--Sentdex|PASS|Numerics|
|model--PT_GPTNEO125_ATG--xhyi|PASS|Numerics|
|model--bert-finetuned-squad--shash2409|PASS|Numerics|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|PASS|Numerics|

## 12 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|maxvit_large_tf_224.in1k|Numerics|PASS|
|model--bert-finetuned-squad--MyMild|Numerics|PASS|
|model--bert-finetuned-squad--SiraH|Numerics|PASS|
|model--bert-finetuned-squad--jatinshah|Numerics|PASS|
|model--bert-large-NER--51la5|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-imdb--sahn|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad-frozen-v2--ericRosello|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.05_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--Namig|Numerics|PASS|
|model--hebrew_poetry-gpt_neo-small--Norod78|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|

