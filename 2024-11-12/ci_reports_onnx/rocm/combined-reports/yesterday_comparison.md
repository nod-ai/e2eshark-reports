# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.9551|113.1868|0.2317|0.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.3498|111.9171|0.5672|0.51%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|363.4032|363.7123|0.3091|0.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.2856|61.4629|0.1773|0.29%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0951|72.0441|-0.051|-0.07%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.6928|274.9079|0.2151|0.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.6795|37.2943|0.6149|1.68%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.8902|20.0903|0.2002|1.01%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.1375|152.0132|-0.1243|-0.08%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.3367|218.2506|-0.0861|-0.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4159|7.3946|-0.0214|-0.29%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|41.7955|37.9168|-3.8787|-9.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4571|6.4203|-0.0368|-0.57%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.4421|27.3759|-1.0661|-3.75%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|54.4365|52.6863|-1.7502|-3.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.4472|19.5434|-0.9038|-4.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|12.8548|12.8703|0.0155|0.12%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.7075|50.7128|0.0053|0.01%|
|migraphx_torchvision__inceptioni1|PASS|progression|19.5709|15.7148|-3.8561|-19.7%|
|migraphx_torchvision__inceptioni32|PASS|within tol|138.2104|137.8446|-0.3658|-0.26%|
|migraphx_torchvision__resnet50i64|PASS|within tol|183.0042|182.7376|-0.2666|-0.15%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.5837|33.4565|-0.1272|-0.38%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.8712|57.7903|-0.0809|-0.14%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.3965|73.3507|-0.0457|-0.06%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.47|13.4096|-0.0604|-0.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.661|13.8879|0.227|1.66%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9343|19.8253|-0.109|-0.55%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.2574|13.4566|0.1992|1.5%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9458|13.9402|-0.0056|-0.04%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5473|21.7554|0.2081|0.97%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.6231|69.2432|-0.3799|-0.55%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.9811|104.6539|-0.3272|-0.31%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.812|145.6737|-0.1383|-0.09%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.9849|14.894|-0.0909|-0.61%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|18.4598|17.4304|-1.0294|-5.58%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6111|26.6743|0.0632|0.24%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8685|20.2498|-0.6187|-2.96%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.8795|28.0058|-0.8737|-3.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.3074|41.2697|-0.0378|-0.09%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_xlarge_tf_512.in21k_ft_in1k|compilation|setup|

## 14 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|davit_base.msft_in1k|compilation|Numerics|
|davit_small.msft_in1k|compilation|Numerics|
|davit_tiny.msft_in1k|compilation|Numerics|
|levit_128.fb_dist_in1k|compilation|Numerics|
|levit_128s.fb_dist_in1k|compilation|Numerics|
|levit_192.fb_dist_in1k|compilation|Numerics|
|levit_256.fb_dist_in1k|compilation|Numerics|
|levit_384.fb_dist_in1k|compilation|Numerics|
|maxvit_base_tf_512.in1k|compilation|Numerics|
|maxvit_base_tf_512.in21k_ft_in1k|compilation|Numerics|
|maxvit_large_tf_512.in1k|compilation|Numerics|
|maxvit_large_tf_512.in21k_ft_in1k|compilation|Numerics|
|maxvit_small_tf_512.in1k|compilation|Numerics|
|maxvit_tiny_tf_512.in1k|compilation|Numerics|

