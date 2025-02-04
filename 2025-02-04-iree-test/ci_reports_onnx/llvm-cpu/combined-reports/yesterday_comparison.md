# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.904|88.3965|1.4925|1.72%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.3333|101.1353|14.802|17.15%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|275.7825|308.6803|32.8978|11.93%|
|migraphx_ORT__distilgpt2_1|PASS|regression|35.8878|70.532|34.6442|96.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.0855|97.0398|11.9543|14.05%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|251.2094|287.9559|36.7465|14.63%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.6912|39.4839|-4.2073|-9.63%|
|migraphx_bert__bert-large-uncased|PASS|regression|387.1571|477.5965|90.4393|23.36%|
|migraphx_cadene__dpn92i1|PASS|regression|165.0114|174.4899|9.4785|5.74%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5464.101|5724.7323|260.6313|4.77%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.2752|319.9876|0.7124|0.22%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5092.7284|4967.8154|-124.913|-2.45%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|416.9623|419.7075|2.7452|0.66%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|500.6059|542.2537|41.6478|8.32%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|97.9492|99.73|1.7808|1.82%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|37.1189|57.3824|20.2635|54.59%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.0171|187.2775|3.2604|1.77%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|122.9011|83.1162|-39.785|-32.37%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|44.1418|51.5805|7.4386|16.85%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1491.5596|1502.4443|10.8847|0.73%|
|migraphx_torchvision__inceptioni1|PASS|progression|208.9262|198.3771|-10.5491|-5.05%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5768.4141|5808.8371|40.423|0.7%|
|migraphx_torchvision__resnet50i1|PASS|within tol|90.557|93.805|3.248|3.59%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5340.2176|5398.191|57.9734|1.09%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2581.728|2935.2336|353.5056|13.69%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4326.2975|4609.977|283.6795|6.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|5808.0554|6184.3509|376.2955|6.48%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|163.7189|162.3293|-1.3896|-0.85%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.9843|265.5323|3.548|1.35%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.7901|396.0954|17.3052|4.57%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|410.9864|406.8269|-4.1595|-1.01%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|639.4657|588.4591|-51.0066|-7.98%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|809.5715|874.3805|64.809|8.01%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5679.5036|5527.5096|-151.9939|-2.68%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8795.6805|8366.2757|-429.4048|-4.88%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|11924.8403|11201.9401|-722.9001|-6.06%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|800.9497|834.4432|33.4935|4.18%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1082.1753|1083.0095|0.8342|0.08%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1648.3646|1527.4692|-120.8954|-7.33%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1288.4553|1360.8077|72.3524|5.62%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2087.3922|2184.7417|97.3495|4.66%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2891.427|2910.7286|19.3016|0.67%|

## No Regressions Found

## No Progressions Found

