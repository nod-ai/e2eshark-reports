# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|95.5894|92.7067|-2.8827|-3.02%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|91.4883|90.1922|-1.2961|-1.42%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|259.8924|260.4496|0.5571|0.21%|
|migraphx_ORT__distilgpt2_1|PASS|progression|39.6941|31.6657|-8.0284|-20.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.2836|86.4985|2.2149|2.63%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|275.2026|261.2243|-13.9782|-5.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|45.113|44.5996|-0.5134|-1.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|375.2562|375.8756|0.6193|0.17%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.7626|173.2807|7.5181|4.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5375.3694|5337.3616|-38.0078|-0.71%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|836.5982|324.7162|-511.882|-61.19%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5109.1225|5099.2289|-9.8935|-0.19%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|381.6421|380.4149|-1.2272|-0.32%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|483.8754|474.6711|-9.2043|-1.9%|
|migraphx_mlperf__resnet50_v1|PASS|regression|91.9057|98.6303|6.7246|7.32%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.154|32.3054|-4.8486|-13.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.1474|180.3814|-3.7661|-2.05%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|81.9852|222.02|140.0348|170.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|43.7669|51.5741|7.8071|17.84%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1615.5658|1576.1168|-39.449|-2.44%|
|migraphx_torchvision__inceptioni1|PASS|within tol|196.2955|194.1003|-2.1951|-1.12%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5393.9027|5348.836|-45.0666|-0.84%|
|migraphx_torchvision__resnet50i1|PASS|progression|91.9535|84.8852|-7.0683|-7.69%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5067.3728|5089.0553|21.6824|0.43%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2603.3288|2659.0232|55.6944|2.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4186.1143|4070.6536|-115.4607|-2.76%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5690.0809|5796.7745|106.6936|1.88%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|162.085|169.9531|7.8682|4.85%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|274.2931|275.2607|0.9677|0.35%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|413.3384|375.8822|-37.4562|-9.06%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|405.7349|388.0458|-17.6891|-4.36%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|624.0296|646.1056|22.076|3.54%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|889.4106|840.0486|-49.362|-5.55%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5085.0162|5042.7318|-42.2844|-0.83%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|7844.2375|8492.4035|648.166|8.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11263.192|11224.7963|-38.3957|-0.34%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|703.7546|712.1993|8.4448|1.2%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1086.4545|1074.8799|-11.5746|-1.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1562.7674|1563.6369|0.8695|0.06%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1292.1256|1330.6109|38.4853|2.98%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2091.2767|2081.3202|-9.9565|-0.48%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2886.3697|2886.0004|-0.3693|-0.01%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|

