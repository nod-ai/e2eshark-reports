# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.5269|89.2295|0.7026|0.79%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.8307|98.3397|9.509|10.7%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|362.6464|259.7945|-102.8519|-28.36%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.9312|29.8135|-1.1176|-3.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|82.7602|82.8627|0.1025|0.12%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|264.1185|245.3862|-18.7323|-7.09%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.797|39.0587|-1.7383|-4.26%|
|migraphx_bert__bert-large-uncased|PASS|within tol|380.8598|364.493|-16.3667|-4.3%|
|migraphx_cadene__dpn92i1|PASS|within tol|170.3673|173.1535|2.7862|1.64%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5379.7176|5285.5908|-94.1268|-1.75%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|342.6177|322.6422|-19.9755|-5.83%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5109.8962|5144.3895|34.4932|0.68%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.8264|383.7371|3.9107|1.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|455.1114|569.0706|113.9592|25.04%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|89.5441|92.476|2.9319|3.27%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.3247|32.1893|-1.1354|-3.41%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.7278|262.7091|82.9813|46.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|77.2967|90.5278|13.2312|17.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|45.3326|39.2124|-6.1202|-13.5%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1621.6976|1567.794|-53.9036|-3.32%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.7947|203.2103|8.4155|4.32%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5496.0982|5440.8761|-55.2221|-1.0%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.5042|89.7748|3.2705|3.78%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5070.3487|5083.7553|13.4066|0.26%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2686.8134|2583.8162|-102.9972|-3.83%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4246.7513|4123.9601|-122.7912|-2.89%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5783.0032|5828.4847|45.4815|0.79%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|346.3536|176.3384|-170.0152|-49.09%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|273.0708|291.1248|18.054|6.61%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.839|379.3044|6.4655|1.73%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|386.8941|390.1188|3.2247|0.83%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|639.8195|621.3708|-18.4487|-2.88%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|819.3633|825.3827|6.0194|0.73%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5120.6753|5072.1411|-48.5342|-0.95%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8061.6189|8157.8015|96.1827|1.19%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11369.9631|11496.3136|126.3505|1.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|730.1091|707.6997|-22.4094|-3.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1134.9163|1094.9115|-40.0048|-3.52%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1577.0391|1507.2989|-69.7402|-4.42%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1309.1642|1303.9638|-5.2004|-0.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2235.2007|2266.7382|31.5375|1.41%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2908.3059|2886.8728|-21.433|-0.74%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_384_dist|PASS|Numerics|

## No Progressions Found

