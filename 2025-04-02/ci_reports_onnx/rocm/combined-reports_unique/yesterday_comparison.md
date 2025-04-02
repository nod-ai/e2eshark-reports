# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.0972|115.935|0.8379|0.73%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.5218|115.7581|0.2363|0.2%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.4706|527.3701|5.8994|1.13%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.6885|69.2807|0.5923|0.86%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.0075|62.0759|0.0685|0.11%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|328.2383|327.1802|-1.0581|-0.32%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2024|34.6285|0.4262|1.25%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3157|19.4133|0.0976|0.51%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0412|5.0758|0.0347|0.69%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.1076|29.7649|0.6573|2.26%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.4126|6.1173|-0.2953|-4.61%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2661|6.9303|-0.3358|-4.62%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.4234|28.2923|1.8689|7.07%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7936|4.79|-0.0035|-0.07%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|38.661|40.7306|2.0697|5.35%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.0004|47.1873|0.1869|0.4%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.5641|20.4965|1.9324|10.41%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.2851|9.7972|1.5121|18.25%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8612|18.1178|0.2566|1.44%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9537|4.8971|-0.0566|-1.14%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.2224|3.1576|-0.0648|-2.01%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.0488|26.8659|-0.1829|-0.68%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.2858|38.5459|0.2601|0.68%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.1067|58.1266|0.0199|0.03%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2567|12.0014|-0.2553|-2.08%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.743|12.6508|-0.0922|-0.72%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3511|19.5943|0.2432|1.26%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8482|12.7118|-0.1364|-1.06%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5359|19.5426|0.0067|0.03%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3008|20.305|0.0042|0.02%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.8475|36.9061|0.0587|0.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.735|77.7051|-0.0299|-0.04%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.7661|119.0591|0.293|0.25%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6576|19.4979|-0.1597|-0.81%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.7094|20.8429|0.1335|0.64%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1388|24.0717|-0.0671|-0.28%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7937|20.8784|0.0847|0.41%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3391|27.5248|0.1857|0.68%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7744|35.0575|0.2831|0.81%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|vit_large_patch16_384_Opset16_timm|Numerics|PASS|

