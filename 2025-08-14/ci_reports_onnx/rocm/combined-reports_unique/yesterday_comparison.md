# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|119.4921|120.8016|1.3095|1.1%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.644|117.9337|1.2897|1.11%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|74.1677|71.8826|-2.285|-3.08%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|74.8445|74.8298|-0.0147|-0.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|302.2826|301.0354|-1.2472|-0.41%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|43.5394|45.0689|1.5296|3.51%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0853|19.2321|0.1467|0.77%|
|migraphx_cadene__dpn92i1|PASS|regression|13.0079|14.7845|1.7766|13.66%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|22.0275|22.7938|0.7663|3.48%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.4678|6.4996|0.0318|0.49%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.2217|7.6019|0.3802|5.26%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|27.0973|26.4074|-0.6899|-2.55%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.7763|15.1385|0.3621|2.45%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.7939|43.6828|-0.1111|-0.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|110.3253|114.099|3.7737|3.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|20.7749|18.9866|-1.7884|-8.61%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.2327|10.2982|1.0655|11.54%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.8523|14.8887|0.0365|0.25%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.0354|4.1253|0.0898|2.23%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.1229|2.1499|0.027|1.27%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7703|25.8454|0.0751|0.29%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.4008|37.0247|-0.3762|-1.01%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.3639|56.0583|0.6943|1.25%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5002|12.6099|0.1098|0.88%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.675|12.6293|-0.0457|-0.36%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.241|19.2733|0.0322|0.17%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.0181|12.8268|-0.1913|-1.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1946|19.3473|0.1527|0.8%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.5817|19.7784|0.1967|1.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.6894|35.7023|0.0128|0.04%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.1593|70.2151|1.0558|1.53%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.9498|109.3232|-0.6267|-0.57%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.558|19.3654|-0.1926|-0.98%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1814|20.1681|-0.0134|-0.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2233|23.3016|0.0783|0.34%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2669|20.2606|-0.0063|-0.03%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.3161|26.2253|-0.0908|-0.34%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5192|32.5483|0.0292|0.09%|

## No Regressions Found

## No Progressions Found

