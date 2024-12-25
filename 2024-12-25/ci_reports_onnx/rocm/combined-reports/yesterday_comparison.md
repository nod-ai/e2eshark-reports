# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.5957|101.2716|1.676|1.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.3376|100.5831|1.2455|1.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|503.7741|508.2076|4.4335|0.88%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.8292|53.5507|-0.2785|-0.52%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.5457|63.1252|1.5795|2.57%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|292.0837|296.2112|4.1275|1.41%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.6744|32.4521|0.7777|2.46%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2836|19.4734|0.1898|0.98%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4786|42.6218|0.1432|0.34%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.2945|149.3148|1.0203|0.69%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.2682|114.2809|0.0127|0.01%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|363.6455|369.899|6.2534|1.72%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1891|7.3757|0.1866|2.6%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.0763|24.1819|0.1056|0.44%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.5085|34.828|1.3196|3.94%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.5852|144.412|1.8268|1.28%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.4321|16.1629|-3.2693|-16.82%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.8494|6.8069|-0.0425|-0.62%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.0998|76.6717|0.572|0.75%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7121|39.7231|0.011|0.03%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.7626|100.1238|1.3612|1.38%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.388|11.3479|-0.0401|-0.35%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|189.244|193.6027|4.3588|2.3%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|77.6146|36.6037|-41.011|-52.84%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|88.5762|60.1587|-28.4174|-32.08%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|82.151|81.9714|-0.1797|-0.22%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.061|13.0246|-0.0364|-0.28%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.5644|13.2951|-0.2693|-1.99%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|20.515|19.4862|-1.0289|-5.02%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7175|12.6471|-0.0704|-0.55%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2993|13.2398|-0.0595|-0.45%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|23.5061|22.0956|-1.4105|-6.0%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|1980.4001|73.1989|-1907.2012|-96.3%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|141.9861|115.1138|-26.8723|-18.93%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|200.5577|161.4665|-39.0911|-19.49%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4664|14.4415|-0.0249|-0.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6733|18.2475|0.5742|3.25%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|46.0615|27.389|-18.6726|-40.54%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.388|20.8001|0.4121|2.02%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.9311|30.7022|0.7712|2.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|46.8497|44.9291|-1.9206|-4.1%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|resnetrs270|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|regnety_640.seer|Numerics|PASS|

