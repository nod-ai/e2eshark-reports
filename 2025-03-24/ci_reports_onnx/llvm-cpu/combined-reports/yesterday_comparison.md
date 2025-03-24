# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.3704|87.6777|-2.6927|-2.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|90.3731|85.8532|-4.5199|-5.0%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|246.8032|255.0395|8.2363|3.34%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.0737|31.6885|1.6148|5.37%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|88.6104|85.3273|-3.2831|-3.71%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|246.9696|248.9968|2.0272|0.82%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|44.1765|48.0003|3.8238|8.66%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.0867|0.9701|-0.1166|-10.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.9073|381.9674|10.0601|2.7%|
|migraphx_cadene__dpn92i1|PASS|progression|215.0286|173.0045|-42.0241|-19.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5451.7972|5319.0566|-132.7407|-2.43%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|326.7146|316.0149|-10.6997|-3.27%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5122.6877|6495.7889|1373.1012|26.8%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|412.4838|401.0919|-11.3919|-2.76%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|428.2825|430.3567|2.0742|0.48%|
|migraphx_mlperf__resnet50_v1|PASS|regression|98.7441|337.2449|238.5008|241.53%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.0056|31.7093|-2.2963|-6.75%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.0772|182.1977|1.1206|0.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|82.4742|81.5217|-0.9525|-1.15%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.158|52.4198|10.2618|24.34%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1457.9532|1468.548|10.5948|0.73%|
|migraphx_torchvision__inceptioni1|PASS|within tol|201.2712|208.9001|7.6289|3.79%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5784.9673|5753.0271|-31.9402|-0.55%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.971|92.8046|8.8336|10.52%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5428.677|5454.3616|25.6845|0.47%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1481.3294|1410.0979|-71.2315|-4.81%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3027.0912|3151.9905|124.8994|4.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4809.2125|4746.7293|-62.4833|-1.3%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.6021|163.058|2.4559|1.53%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.9334|256.4731|-9.4603|-3.56%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|379.1589|361.2156|-17.9433|-4.73%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|254.4818|241.0937|-13.3881|-5.26%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|467.3213|493.3147|25.9934|5.56%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|781.5716|686.7582|-94.8134|-12.13%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2920.3044|2776.856|-143.4483|-4.91%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5826.0135|5932.5605|106.547|1.83%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9140.2754|9241.2565|100.9811|1.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|403.1621|403.1391|-0.023|-0.01%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|790.3964|796.9323|6.5359|0.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1278.4855|1252.391|-26.0944|-2.04%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|736.7532|753.1917|16.4385|2.23%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1625.6742|1530.0204|-95.6537|-5.88%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2412.7321|2402.8|-9.932|-0.41%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|PASS|Numerics|

## No Progressions Found

