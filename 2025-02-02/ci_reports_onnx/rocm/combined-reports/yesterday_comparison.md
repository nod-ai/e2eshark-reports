# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|105.6455|107.9636|2.3181|2.19%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.1247|103.9341|-4.1906|-3.88%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|472.9195|469.7551|-3.1643|-0.67%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.1616|58.6987|0.5371|0.92%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.5289|62.5875|0.0586|0.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.1097|267.7337|0.6239|0.23%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.055|34.8181|0.7631|2.24%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8658|18.8501|-0.0157|-0.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|6.9571|7.4027|0.4456|6.4%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.5997|27.2782|0.6784|2.55%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.3778|6.3665|-0.0113|-0.18%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.2944|42.5057|0.2113|0.5%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.6046|141.6657|-0.9389|-0.66%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.7531|17.1567|-0.5964|-3.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.2426|7.6247|0.3821|5.28%|
|migraphx_torchvision__inceptioni1|PASS|within tol|62.381|64.5512|2.1703|3.48%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.7788|31.8276|0.0488|0.15%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.4176|53.7511|0.3334|0.62%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.0736|70.356|0.2824|0.4%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1721|11.9318|-0.2403|-1.97%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.2548|12.5868|0.3321|2.71%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0976|19.0514|-0.0462|-0.24%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6604|12.6464|-0.014|-0.11%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2622|13.2565|-0.0056|-0.04%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.8612|20.7842|-0.077|-0.37%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.7987|66.0406|0.2419|0.37%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.1013|99.4073|1.306|1.33%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|138.8292|139.7802|0.9509|0.68%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3035|14.2765|-0.0269|-0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.4344|16.5458|0.1113|0.68%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.5827|25.6249|0.0422|0.17%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.957|18.9731|0.0161|0.09%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.55|26.4641|-0.0859|-0.32%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.2081|39.4846|0.2765|0.71%|

## No Regressions Found

## No Progressions Found

