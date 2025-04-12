# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.432|115.0169|0.5849|0.51%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.042|116.0122|-1.0298|-0.88%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|517.4475|531.2622|13.8147|2.67%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.9906|68.6075|-1.3831|-1.98%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.7795|62.4256|-0.3539|-0.56%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|328.6153|327.5387|-1.0766|-0.33%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.9858|33.841|-0.1448|-0.43%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3256|19.4356|0.1099|0.57%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0085|5.0308|0.0223|0.45%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.1984|27.456|0.2576|0.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.8932|5.8889|-0.0043|-0.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9883|6.9712|-0.0171|-0.24%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.3452|30.4881|4.1429|15.73%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8383|4.914|0.0756|1.56%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|38.9859|38.9987|0.0129|0.03%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|48.0419|45.6651|-2.3768|-4.95%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.1824|17.6886|-0.4938|-2.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.9308|9.5038|1.573|19.83%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.2655|17.3554|0.0898|0.52%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.6722|4.786|0.1139|2.44%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1444|3.1656|0.0212|0.67%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.207|27.2392|0.0322|0.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.4526|38.2121|-0.2406|-0.63%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9731|57.4903|-0.4828|-0.83%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2745|12.0152|-0.2593|-2.11%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6472|12.7066|0.0595|0.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.342|19.4067|0.0647|0.33%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6994|12.4666|-0.2328|-1.83%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.517|19.5253|0.0083|0.04%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.262|20.3432|0.0812|0.4%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.6464|36.9802|0.3338|0.91%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.3046|77.167|-0.1376|-0.18%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|117.9808|118.3096|0.3288|0.28%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5692|19.4363|-0.1329|-0.68%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8355|20.8738|0.0383|0.18%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1762|24.175|-0.0012|-0.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8335|20.89|0.0565|0.27%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5073|27.5034|-0.0039|-0.01%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.8125|34.8619|0.0494|0.14%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|mosaic-9|compilation|Numerics|

