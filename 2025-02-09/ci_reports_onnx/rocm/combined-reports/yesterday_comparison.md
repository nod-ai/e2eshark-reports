# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.316|109.1029|2.787|2.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|109.4414|105.819|-3.6224|-3.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|494.456|464.3267|-30.1293|-6.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|56.9168|58.5398|1.623|2.85%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1907|63.1556|-0.0351|-0.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|270.4207|269.7114|-0.7093|-0.26%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.821|34.5117|-0.3094|-0.89%|
|migraphx_bert__bert-large-uncased|PASS|progression|29.3548|18.8903|-10.4646|-35.65%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0711|7.0907|0.0196|0.28%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|29.6714|27.3083|-2.3631|-7.96%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.0215|4.6952|-0.3263|-6.5%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.0336|42.4815|-1.5521|-3.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|46.3206|54.4388|8.1182|17.53%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.3264|16.6761|-0.6502|-3.75%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.9327|7.4081|0.4754|6.86%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8366|4.968|0.1314|2.72%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.8967|32.4346|-0.4621|-1.4%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.7576|54.8722|0.1146|0.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|71.9405|72.2531|0.3127|0.43%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1773|12.1567|-0.0206|-0.17%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5009|12.3579|-0.143|-1.14%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2083|19.6379|0.4296|2.24%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7896|13.2061|0.4164|3.26%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.1786|14.8956|1.717|13.03%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.1642|20.9223|-0.2418|-1.14%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.5925|67.4828|-0.1097|-0.16%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|100.8018|356.5066|255.7048|253.67%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.5402|142.8674|-2.6727|-1.84%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4262|14.3293|-0.0969|-0.67%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|47.3305|17.2929|-30.0376|-63.46%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.0782|25.9509|-0.1273|-0.49%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.4418|46.9418|27.5|141.45%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|47.1968|27.1261|-20.0707|-42.53%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.318|40.245|-0.073|-0.18%|

## No Regressions Found

## No Progressions Found

