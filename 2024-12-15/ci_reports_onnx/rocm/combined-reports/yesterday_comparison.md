# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|97.8961|99.5488|1.6528|1.69%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|98.3238|100.835|2.5112|2.55%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|494.0389|501.2898|7.2509|1.47%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.9888|53.1382|-0.8506|-1.58%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.5802|61.1852|-0.395|-0.64%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|263.8973|290.3049|26.4076|10.01%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|30.9226|31.2732|0.3505|1.13%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4997|19.5107|0.011|0.06%|
|migraphx_bert__bertsquad-12|PASS|progression|8.1289|7.3401|-0.7888|-9.7%|
|migraphx_cadene__inceptionv4i16|PASS|progression|159.522|149.2941|-10.2279|-6.41%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|185.2716|188.1831|2.9115|1.57%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.23|7.2246|-0.0054|-0.07%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.1157|24.0751|-0.0406|-0.17%|
|migraphx_mlperf__resnet50_v1|Numerics|progression|6.1402|5.7029|-0.4373|-7.12%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.0611|32.9534|-7.1078|-17.74%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.7876|46.6996|-0.0879|-0.19%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|14.5687|16.3788|1.8101|12.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.0145|6.0543|0.0398|0.66%|
|migraphx_torchvision__densenet121i32|PASS|regression|71.7279|84.4943|12.7664|17.8%|
|migraphx_torchvision__inceptioni1|PASS|progression|18.9451|15.9434|-3.0017|-15.84%|
|migraphx_torchvision__inceptioni32|PASS|regression|136.8613|145.1263|8.265|6.04%|
|migraphx_torchvision__resnet50i64|PASS|within tol|166.1349|167.9269|1.792|1.08%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.7763|35.3231|1.5468|4.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.9717|58.308|-0.6637|-1.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|74.9692|79.1748|4.2056|5.61%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.1136|13.0723|-0.0413|-0.31%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3151|13.1987|-0.1165|-0.87%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4343|19.468|0.0337|0.17%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8969|12.6486|-0.2483|-1.93%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.5101|27.4485|13.9385|103.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.359|21.6867|0.3277|1.53%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.5895|70.735|0.1455|0.21%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|106.9894|110.8995|3.9101|3.65%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|149.1144|159.178|10.0636|6.75%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4903|14.2342|-0.2561|-1.77%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2734|17.6876|0.4143|2.4%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6831|26.6257|-0.0574|-0.22%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.8649|28.3296|8.4647|42.61%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|28.2009|29.6832|1.4822|5.26%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.8477|43.442|1.5944|3.81%|

## No Regressions Found

## No Progressions Found

