# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.0306|108.0088|0.9783|0.91%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.6436|107.9622|1.3185|1.24%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|473.6884|1189.7704|716.082|151.17%|
|migraphx_ORT__distilgpt2_1|PASS|progression|61.6802|58.0489|-3.6313|-5.89%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|65.6258|64.1313|-1.4945|-2.28%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|275.4226|273.819|-1.6036|-0.58%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|37.156|34.4628|-2.6932|-7.25%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2836|19.4022|0.1186|0.61%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0631|7.1245|0.0614|0.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|27.5769|55.7116|28.1347|102.02%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.0332|44.2181|0.1849|0.42%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|146.872|143.014|-3.858|-2.63%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.0137|18.0578|2.0441|12.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.4321|9.4439|2.0118|27.07%|
|migraphx_torchvision__inceptioni1|PASS|within tol|60.3198|60.9876|0.6679|1.11%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.5593|32.5203|-0.039|-0.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.559|54.6723|0.1133|0.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|73.1134|84.0034|10.89|14.89%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|11.9067|47.7605|35.8538|301.12%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8985|12.6312|-0.2673|-2.07%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.8889|19.4529|-0.436|-2.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9783|12.7226|-0.2557|-1.97%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.1997|13.262|0.0623|0.47%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.1592|21.2245|0.0652|0.31%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.1602|67.0982|-0.062|-0.09%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.0949|100.1944|2.0995|2.14%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|284.7153|148.5016|-136.2138|-47.84%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3149|14.3493|0.0344|0.24%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.3841|16.7647|-0.6194|-3.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.8944|26.26|-0.6345|-2.36%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.2423|19.1491|-0.0931|-0.48%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.1126|27.3562|0.2436|0.9%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.6474|40.6284|-0.019|-0.05%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|efficientnet_b2_pruned.in1k|compilation|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|compilation|PASS|

