# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.7387|114.432|-1.3066|-1.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.0631|117.042|-0.0211|-0.02%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|554.1035|517.4475|-36.656|-6.62%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.0254|69.9906|0.9651|1.4%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.1003|62.7795|0.6792|1.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|328.1115|328.6153|0.5038|0.15%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.3786|33.9858|-0.3928|-1.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2999|19.3256|0.0258|0.13%|
|migraphx_cadene__dpn92i1|PASS|progression|5.4647|5.0085|-0.4563|-8.35%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.2789|27.1984|-0.0805|-0.3%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.0952|5.8932|-0.202|-3.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9173|6.9883|0.071|1.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|28.7917|26.3452|-2.4464|-8.5%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.0201|4.8383|-0.1818|-3.62%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|38.3393|38.9859|0.6465|1.69%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.839|48.0419|1.2029|2.57%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.355|18.1824|-1.1726|-6.06%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.5595|7.9308|-1.6287|-17.04%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.2132|17.2655|0.0523|0.3%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8101|4.6722|-0.1379|-2.87%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1558|3.1444|-0.0114|-0.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.8372|27.207|0.3698|1.38%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.7953|38.4526|0.6574|1.74%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.2306|57.9731|0.7425|1.3%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1432|12.2745|0.1313|1.08%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.719|12.6472|-0.0718|-0.56%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.353|19.342|-0.0111|-0.06%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8421|12.6994|-0.1427|-1.11%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5323|19.517|-0.0153|-0.08%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3526|20.262|-0.0906|-0.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.5708|36.6464|0.0756|0.21%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|76.4215|77.3046|0.8832|1.16%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|116.8138|117.9808|1.167|1.0%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6949|19.5692|-0.1256|-0.64%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9669|20.8355|-0.1314|-0.63%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0623|24.1762|0.114|0.47%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6984|20.8335|0.1351|0.65%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.2882|27.5073|0.2191|0.8%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.4749|34.8125|0.3377|0.98%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|mosaic-9|Numerics|compilation|

## No Progressions Found

