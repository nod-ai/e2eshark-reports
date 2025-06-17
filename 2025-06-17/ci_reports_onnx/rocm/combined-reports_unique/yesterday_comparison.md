# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|120.7249|121.5922|0.8673|0.72%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.0983|123.2129|0.1146|0.09%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|537.4153|546.8652|9.4499|1.76%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.889|69.8636|0.9746|1.41%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.6527|66.3782|-0.2745|-0.41%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.2515|340.7962|0.5447|0.16%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.5418|34.2834|-1.2584|-3.54%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4062|19.5795|0.1733|0.89%|
|migraphx_cadene__dpn92i1|Numerics|progression|3.9142|3.7098|-0.2043|-5.22%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.2169|19.6129|0.396|2.06%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.3946|4.3847|-0.0099|-0.22%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9448|7.0116|0.0669|0.96%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.2815|25.461|0.1795|0.71%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9874|13.9458|-0.0416|-0.3%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.855|41.674|-0.1811|-0.43%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|102.9942|102.9514|-0.0428|-0.04%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.0429|18.3356|0.2927|1.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.3249|8.6976|-0.6273|-6.73%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.8179|12.8614|0.0435|0.34%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.2776|3.252|-0.0256|-0.78%|
|migraphx_torchvision__resnet50i1|Numerics|progression|2.395|2.2534|-0.1416|-5.91%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.4792|27.519|0.0398|0.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.048|39.0608|0.0128|0.03%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.5757|56.497|-0.0787|-0.14%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3617|12.4145|0.0527|0.43%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6047|12.5191|-0.0855|-0.68%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3177|19.4015|0.0838|0.43%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7843|12.6853|-0.099|-0.77%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4784|19.6421|0.1637|0.84%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2581|20.3591|0.101|0.5%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.0279|37.8678|-0.1601|-0.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.8776|71.9349|0.0573|0.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|111.7073|110.7229|-0.9844|-0.88%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5925|19.5406|-0.052|-0.27%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8888|21.1842|0.2955|1.41%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.3277|24.3886|0.0609|0.25%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0421|21.0901|0.048|0.23%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0093|28.1743|0.165|0.59%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.6874|34.711|0.0236|0.07%|

## No Regressions Found

## 6 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|m2m100_Opset17_transformers|Numerics|PASS|
|migraphx_ORT__bert_large_uncased_1|Numerics|PASS|
|mvitv2_small|Numerics|PASS|
|swin_large_patch4_window12_384_Opset17_timm|Numerics|PASS|
|swinv2_base_window8_256_Opset16_timm|Numerics|PASS|
|vit_base_patch16_384_Opset16_timm|Numerics|PASS|

