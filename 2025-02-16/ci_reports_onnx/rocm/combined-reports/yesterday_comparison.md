# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.496|109.4413|-2.0548|-1.84%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.1232|111.7713|-1.3519|-1.2%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|472.3042|475.3079|3.0037|0.64%|
|migraphx_ORT__distilgpt2_1|Numerics|within tol|61.9906|62.3902|0.3996|0.64%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.7032|61.8804|-1.8228|-2.86%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|271.3102|267.2496|-4.0606|-1.5%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.6067|34.012|-0.5947|-1.72%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.8197|2.0147|0.1949|10.71%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.912|18.8949|-0.017|-0.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1524|7.1048|-0.0475|-0.66%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.3869|26.9793|0.5924|2.25%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.3531|4.9334|-0.4197|-7.84%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.7184|43.7894|0.0711|0.16%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|48.202|45.256|-2.946|-6.11%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.801|17.0955|-0.7055|-3.96%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.5003|8.2495|-0.2509|-2.95%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8897|4.9497|0.0599|1.23%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.6651|32.0611|-0.604|-1.85%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.8144|53.4481|-1.3663|-2.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.2432|70.7879|-1.4552|-2.01%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0043|12.0914|0.0871|0.73%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4318|12.7014|0.2696|2.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3728|19.4101|0.0374|0.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9852|13.1048|0.1196|0.92%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3771|13.4419|0.0648|0.48%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0326|20.7365|-0.2961|-1.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.7778|65.8711|-1.9067|-2.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|101.3853|99.2366|-2.1487|-2.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|143.2587|140.4951|-2.7636|-1.93%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5902|14.3499|-0.2403|-1.65%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.8728|16.7805|-0.0923|-0.55%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.4432|25.9288|-0.5144|-1.95%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.7336|19.087|-0.6466|-3.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.1239|26.4147|-0.7092|-2.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.367|39.2503|-1.1167|-2.77%|

## No Regressions Found

## No Progressions Found

