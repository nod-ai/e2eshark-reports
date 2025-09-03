# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__distilgpt2_1|PASS|within tol|66.4828|67.0508|0.568|0.85%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.0899|38.1332|-0.9567|-2.45%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8323|18.8065|-0.0258|-0.14%|
|migraphx_cadene__dpn92i1|PASS|progression|4.3019|3.9785|-0.3235|-7.52%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|18.0323|17.6887|-0.3436|-1.91%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|3.392|3.436|0.044|1.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|8.0028|7.028|-0.9748|-12.18%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.0451|26.2714|0.2263|0.87%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|16.1742|15.6256|-0.5486|-3.39%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|116.5163|116.47|-0.0463|-0.04%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.9625|19.6174|1.6549|9.21%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|14.0638|10.5311|-3.5327|-25.12%|
|migraphx_torchvision__densenet121i32|PASS|within tol|12.8968|12.495|-0.4019|-3.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.2991|3.4138|0.1147|3.48%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.1698|2.1655|-0.0043|-0.2%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.6261|26.098|-0.5281|-1.98%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.0202|38.0669|-0.9533|-2.44%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.7381|57.2327|-0.5053|-0.88%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.153|12.134|-0.019|-0.16%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7478|12.2064|-0.5415|-4.25%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4936|19.2565|-0.2371|-1.22%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4411|12.3353|-0.1058|-0.85%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.0055|19.0117|0.0062|0.03%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.1587|19.9401|-0.2187|-1.08%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8915|36.4402|-1.4513|-3.83%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|73.4226|71.435|-1.9876|-2.71%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|119.102|115.6811|-3.4209|-2.87%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5314|19.1775|-0.354|-1.81%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2503|20.2718|0.0215|0.11%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.6974|23.258|-0.4395|-1.85%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8812|20.5492|-0.332|-1.59%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.6942|27.1885|-0.5058|-1.83%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.7153|34.136|0.4206|1.25%|

## No Regressions Found

## No Progressions Found

