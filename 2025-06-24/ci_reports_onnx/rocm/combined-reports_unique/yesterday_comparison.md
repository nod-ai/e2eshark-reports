# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.5702|121.7123|0.1422|0.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.8857|126.4522|2.5664|2.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|536.5708|538.5056|1.9348|0.36%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.4495|69.0489|-0.4006|-0.58%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.5877|66.1211|-0.4667|-0.7%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.3973|340.6698|0.2724|0.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2594|34.321|0.0616|0.18%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.028|19.0237|-0.0043|-0.02%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.6517|3.6571|0.0053|0.15%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.3807|19.3063|-0.0744|-0.38%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.2212|4.2056|-0.0156|-0.37%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.002|6.8758|-0.1262|-1.8%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.24|25.7293|-0.5107|-1.95%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9186|13.9842|0.0656|0.47%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.9591|41.4548|-0.5043|-1.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|104.4415|103.2661|-1.1754|-1.13%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.887|17.4355|-1.4515|-7.68%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.6826|9.8382|1.1556|13.31%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.8523|13.4482|0.5959|4.64%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.3598|3.3949|0.0351|1.05%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2453|2.2654|0.0201|0.9%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.2361|26.293|0.0569|0.22%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.022|37.8496|-0.1724|-0.45%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.3488|56.3136|-0.0351|-0.06%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3713|12.1609|-0.2104|-1.7%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3442|12.3723|0.028|0.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0166|19.0585|0.0419|0.22%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5643|12.5984|0.0341|0.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9463|18.9676|0.0213|0.11%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6678|19.7644|0.0966|0.49%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.9178|36.6712|-0.2465|-0.67%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.9008|71.8792|-0.0216|-0.03%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|116.3586|116.7625|0.4039|0.35%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|18.9862|19.0135|0.0273|0.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0022|19.9712|-0.031|-0.16%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.1593|23.0775|-0.0817|-0.35%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0335|20.6239|0.5904|2.95%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.457|26.5239|0.0669|0.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5017|33.4122|0.9105|2.8%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--pythia-410mn-ntoxic--skrishna|PASS|Numerics|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|swinv2_base_window12to16_192to256.ms_in22k_ft_in1k|Numerics|PASS|
|tf_efficientnetv2_xl.in21k_ft_in1k|Numerics|PASS|

