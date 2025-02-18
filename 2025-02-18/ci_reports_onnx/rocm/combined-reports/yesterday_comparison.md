# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|134.238|122.9443|-11.2936|-8.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|116.0176|127.6414|11.6238|10.02%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|478.0184|509.3315|31.3131|6.55%|
|migraphx_ORT__distilgpt2_1|PASS|regression|61.3621|68.8886|7.5265|12.27%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|63.7475|402.3363|338.5888|531.14%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|268.0215|267.1329|-0.8886|-0.33%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|35.8198|41.9841|6.1643|17.21%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.5561|2.448|-0.1082|-4.23%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2186|19.1756|-0.0431|-0.22%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4783|7.2355|-0.2428|-3.25%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|41.7782|32.1273|-9.6509|-23.1%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.9059|4.8917|-0.0143|-0.29%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|55.4111|44.4255|-10.9855|-19.83%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|54.522|64.6327|10.1108|18.54%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.5895|17.8135|0.224|1.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.3745|9.2407|1.8662|25.31%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.3427|5.3246|-0.0181|-0.34%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.7802|31.9689|0.1888|0.59%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.9687|53.8549|-0.1138|-0.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.0528|70.6108|0.558|0.8%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0934|12.538|0.4446|3.68%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.4627|13.3039|0.8412|6.75%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.1766|20.3178|1.1411|5.95%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.7505|13.7248|0.9744|7.64%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.5529|13.5119|-0.041|-0.3%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.2479|21.4241|0.1762|0.83%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.4028|66.9351|0.5323|0.8%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.7194|100.0564|1.3369|1.35%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|139.4721|140.1746|0.7024|0.5%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.3996|15.8082|1.4087|9.78%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.607|17.2617|0.6547|3.94%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.7398|26.5925|0.8527|3.31%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.1|20.2124|1.1124|5.82%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5609|27.4136|0.8527|3.21%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.3272|40.4135|1.0862|2.76%|

## No Regressions Found

## No Progressions Found

