# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.935|116.2429|0.3078|0.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.7581|115.1194|-0.6387|-0.55%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|527.3701|524.8082|-2.5618|-0.49%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.2807|69.2271|-0.0536|-0.08%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.0759|61.9814|-0.0945|-0.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|327.1802|329.535|2.3548|0.72%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.6285|34.258|-0.3705|-1.07%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4133|19.4275|0.0142|0.07%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0758|5.0747|-0.0012|-0.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.7649|30.9249|1.16|3.9%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.1173|5.8892|-0.2281|-3.73%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9303|7.2158|0.2855|4.12%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.2923|27.4883|-0.804|-2.84%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.79|4.8573|0.0672|1.4%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.7306|38.5424|-2.1882|-5.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.1873|47.1137|-0.0736|-0.16%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.4965|19.6148|-0.8817|-4.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.7972|7.2868|-2.5104|-25.62%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1178|17.9364|-0.1815|-1.0%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8971|4.8748|-0.0223|-0.46%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1576|3.1599|0.0023|0.07%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.8659|27.0654|0.1996|0.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.5459|38.4016|-0.1443|-0.37%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.1266|58.6533|0.5267|0.91%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0014|12.0086|0.0073|0.06%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6508|12.4365|-0.2143|-1.69%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5943|19.3909|-0.2035|-1.04%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7118|12.5969|-0.1149|-0.9%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5426|19.4199|-0.1227|-0.63%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.305|20.4512|0.1462|0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.9061|37.0441|0.138|0.37%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.7051|78.1184|0.4133|0.53%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|119.0591|119.1853|0.1263|0.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4979|19.5343|0.0365|0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8429|20.7306|-0.1124|-0.54%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0717|24.2653|0.1936|0.8%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8784|20.7976|-0.0808|-0.39%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5248|27.4868|-0.038|-0.14%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.0575|34.9442|-0.1132|-0.32%|

## No Regressions Found

## No Progressions Found

