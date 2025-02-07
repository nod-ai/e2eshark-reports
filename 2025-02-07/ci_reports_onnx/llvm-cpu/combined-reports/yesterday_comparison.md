# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|86.8036|110.9448|24.1412|27.81%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|87.8805|92.7516|4.8711|5.54%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|250.8993|370.6139|119.7146|47.71%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|33.887|33.7858|-0.1012|-0.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.2207|86.2211|-0.9996|-1.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|247.3479|263.805|16.4571|6.65%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.4011|42.1297|2.7285|6.92%|
|migraphx_bert__bert-large-uncased|PASS|progression|585.6797|371.2289|-214.4508|-36.62%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.3337|168.4904|4.1567|2.53%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5561.6939|5614.2399|52.546|0.94%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.3107|320.3225|-2.9882|-0.92%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|6563.5889|5809.4752|-754.1137|-11.49%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|376.2011|474.8266|98.6256|26.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|418.0503|414.889|-3.1613|-0.76%|
|migraphx_mlperf__resnet50_v1|PASS|regression|298.7395|320.6454|21.9058|7.33%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.8191|32.0478|0.2287|0.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.6256|189.8398|8.2141|4.52%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|80.2857|96.8032|16.5174|20.57%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.7906|46.169|3.3785|7.9%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1484.4645|1468.6411|-15.8233|-1.07%|
|migraphx_torchvision__inceptioni1|PASS|regression|198.7028|218.0747|19.3719|9.75%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5780.9931|5772.3415|-8.6516|-0.15%|
|migraphx_torchvision__resnet50i1|PASS|within tol|90.0486|89.9301|-0.1184|-0.13%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5418.5957|5412.2094|-6.3863|-0.12%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2770.2508|2537.0999|-233.151|-8.42%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4073.9992|4135.0989|61.0996|1.5%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6116.0607|5810.2428|-305.8179|-5.0%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|168.3238|160.9746|-7.3492|-4.37%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.4612|260.2316|-3.2295|-1.23%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|370.2551|411.8472|41.592|11.23%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|428.8047|402.5475|-26.2572|-6.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|628.7612|654.0368|25.2756|4.02%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|848.7977|809.1087|-39.6889|-4.68%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5890.1104|5655.0263|-235.0841|-3.99%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8107.9735|8369.744|261.7706|3.23%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11330.6713|11325.4803|-5.191|-0.05%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1106.2204|720.8713|-385.3491|-34.83%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1091.0488|1079.816|-11.2328|-1.03%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1633.5281|1499.6333|-133.8949|-8.2%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|3249.2373|1286.6066|-1962.6308|-60.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2149.1125|2088.3022|-60.8104|-2.83%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3127.9037|2885.1793|-242.7244|-7.76%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|Numerics|PASS|

