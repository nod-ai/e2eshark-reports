# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.9636|104.3115|-3.6521|-3.38%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|103.9341|105.2247|1.2907|1.24%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|469.7551|473.2369|3.4818|0.74%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.6987|57.2271|-1.4716|-2.51%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.5875|62.2461|-0.3414|-0.55%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.7337|270.5913|2.8577|1.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8181|34.113|-0.7051|-2.03%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8501|18.9137|0.0636|0.34%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.4027|6.9141|-0.4886|-6.6%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.2782|26.0708|-1.2073|-4.43%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.3665|6.3554|-0.0111|-0.17%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.5057|42.733|0.2273|0.53%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|141.6657|142.1062|0.4404|0.31%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.1567|17.9208|0.764|4.45%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.6247|8.0334|0.4087|5.36%|
|migraphx_torchvision__inceptioni1|PASS|progression|64.5512|60.7419|-3.8094|-5.9%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.8276|32.1655|0.3379|1.06%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.7511|53.8285|0.0774|0.14%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.356|71.466|1.11|1.58%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9318|11.9782|0.0464|0.39%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5868|12.487|-0.0999|-0.79%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0514|19.0597|0.0082|0.04%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6464|12.956|0.3096|2.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2565|13.3705|0.114|0.86%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7842|20.6259|-0.1583|-0.76%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.0406|66.3516|0.311|0.47%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|99.4073|100.1086|0.7013|0.71%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|139.7802|140.4156|0.6354|0.45%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2765|14.4571|0.1806|1.27%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.5458|16.4429|-0.1029|-0.62%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.6249|26.3738|0.7489|2.92%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.9731|19.1243|0.1512|0.8%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.4641|26.7159|0.2517|0.95%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.4846|40.1221|0.6375|1.61%|

## No Regressions Found

## No Progressions Found

