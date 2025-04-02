# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.9337|88.2694|0.3357|0.38%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.4826|94.0626|5.5799|6.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|249.3528|263.2771|13.9243|5.58%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.4996|39.8571|8.3574|26.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.4584|97.2644|11.806|13.81%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.8241|254.1808|3.3566|1.34%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|44.5704|39.5139|-5.0566|-11.35%|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.869|369.3119|-0.5571|-0.15%|
|migraphx_cadene__dpn92i1|PASS|regression|160.545|227.9192|67.3742|41.97%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5458.452|5638.9484|180.4964|3.31%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.8869|318.1927|1.3058|0.41%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|404.3841|444.0665|39.6824|9.81%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|448.9047|454.2786|5.374|1.2%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.9171|95.4136|0.4965|0.52%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.7629|31.3115|0.5486|1.78%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|177.1292|179.1391|2.0099|1.13%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|61.3385|70.363|9.0245|14.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.3579|21.1732|0.8154|4.01%|
|migraphx_torchvision__densenet121i32|PASS|regression|1551.5861|1633.9152|82.329|5.31%|
|migraphx_torchvision__inceptioni1|PASS|within tol|190.2132|190.4172|0.204|0.11%|
|migraphx_torchvision__resnet50i1|PASS|regression|88.5635|96.1715|7.6079|8.59%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1415.273|1456.6394|41.3664|2.92%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|2967.5434|3156.4832|188.9398|6.37%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4625.4001|4783.2873|157.8872|3.41%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|149.3784|151.0191|1.6407|1.1%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|251.1327|266.7246|15.5919|6.21%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|356.6167|361.9167|5.3001|1.49%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|242.1887|239.0098|-3.1789|-1.31%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|426.8844|426.9188|0.0345|0.01%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|669.0304|658.5835|-10.4469|-1.56%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2760.8474|2859.0176|98.1702|3.56%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5677.8681|5795.1755|117.3074|2.07%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9091.2521|9357.7917|266.5395|2.93%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|401.0472|411.8484|10.8012|2.69%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|799.0986|951.6162|152.5176|19.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1237.22|1254.6339|17.4139|1.41%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|745.276|767.2365|21.9605|2.95%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1502.2704|1549.1739|46.9035|3.12%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2379.9502|2431.1422|51.192|2.15%|

## No Regressions Found

## No Progressions Found

