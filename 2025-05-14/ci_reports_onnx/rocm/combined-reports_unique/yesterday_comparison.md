# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.7766|117.3633|0.5868|0.5%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.976|119.2062|2.2301|1.91%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|522.3604|521.9315|-0.4289|-0.08%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.6468|68.8303|-0.8165|-1.17%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.7446|62.793|0.0484|0.08%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|309.8234|307.547|-2.2764|-0.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.7158|36.1053|1.3895|4.0%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1946|19.1065|-0.0881|-0.46%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.8233|3.7983|-0.0251|-0.66%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.4506|27.2464|-0.2042|-0.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.4997|4.4318|-0.0679|-1.51%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0875|7.1003|0.0128|0.18%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|28.2414|27.9163|-0.3251|-1.15%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0093|14.5323|0.523|3.73%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.6585|39.3853|-0.2732|-0.69%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|126.028|126.4698|0.4418|0.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.3338|18.6126|-0.7213|-3.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.1986|9.6617|-0.5369|-5.26%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.6698|17.7763|0.1065|0.6%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.4405|4.4371|-0.0034|-0.08%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.179|3.1458|-0.0332|-1.04%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.371|27.246|-0.125|-0.46%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.2679|39.4258|0.1579|0.4%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|58.0623|58.0541|-0.0081|-0.01%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2666|12.2059|-0.0607|-0.49%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3789|12.3758|-0.0031|-0.03%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.197|19.3011|0.1041|0.54%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6392|12.8345|0.1953|1.55%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2006|19.2917|0.0911|0.47%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.1478|20.0703|-0.0775|-0.38%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8724|37.8613|-0.011|-0.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|73.7961|73.8008|0.0047|0.01%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|115.5574|115.4117|-0.1457|-0.13%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4969|19.7343|0.2374|1.22%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.6637|20.7161|0.0525|0.25%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|32.2776|24.1989|-8.0788|-25.03%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8492|21.0037|0.1546|0.74%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.8194|27.858|0.0385|0.14%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.591|34.5716|-0.0194|-0.06%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|ecaresnet101d_Opset16_timm|PASS|compiled_inference|
|gernet_s_Opset18_timm|PASS|compiled_inference|
|migx_bench_bert-large-uncased_16_384|PASS|Numerics|
|migx_bench_bert-large-uncased_32_384|PASS|Numerics|
|mobilevitv2_150_384_in22ft1k_Opset16_timm|PASS|compilation|
|mobilevitv2_175_384_in22ft1k_Opset17_timm|PASS|compilation|
|mobilevitv2_200_384_in22ft1k_Opset18_timm|PASS|compilation|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convit_base|Numerics|PASS|
|ecaresnet50t_Opset16_timm|compiled_inference|PASS|
|fcn-resnet101-11|Numerics|PASS|
|m2m100_Opset18_transformers|Numerics|PASS|
|migraphx_mlperf__bert_large_mlperf|Numerics|PASS|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|Numerics|PASS|
|vit_base_patch8_224_Opset16_timm|Numerics|PASS|

