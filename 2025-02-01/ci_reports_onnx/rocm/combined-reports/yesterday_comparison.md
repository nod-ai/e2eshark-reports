# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|105.3868|105.6455|0.2587|0.25%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.9748|108.1247|2.1499|2.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|478.1015|472.9195|-5.1821|-1.08%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|57.6547|58.1616|0.507|0.88%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.7114|62.5289|-1.1825|-1.86%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.1038|267.1097|-4.9941|-1.84%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.3939|34.055|-1.3389|-3.78%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0554|18.8658|-0.1896|-1.0%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0213|6.9571|-0.0642|-0.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.2554|26.5997|0.3443|1.31%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.4444|6.3778|-0.0665|-1.03%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.3264|42.2944|-2.032|-4.58%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|150.161|142.6046|-7.5564|-5.03%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.806|17.7531|0.9471|5.64%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.2354|7.2426|-0.9928|-12.06%|
|migraphx_torchvision__inceptioni1|PASS|within tol|60.8293|62.381|1.5517|2.55%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.5821|31.7788|-0.8032|-2.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.6984|53.4176|-1.2808|-2.34%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|71.9615|70.0736|-1.888|-2.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0815|12.1721|0.0905|0.75%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3318|12.2548|-0.0771|-0.62%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0599|19.0976|0.0377|0.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6368|12.6604|0.0237|0.19%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|16.3|13.2622|-3.0379|-18.64%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.9266|20.8612|-0.0654|-0.31%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|69.756|65.7987|-3.9573|-5.67%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|114.7212|98.1013|-16.6199|-14.49%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|142.771|138.8292|-3.9418|-2.76%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4388|14.3035|-0.1353|-0.94%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|29.8524|16.4344|-13.418|-44.95%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|188.1292|25.5827|-162.5465|-86.4%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.3436|18.957|-0.3866|-2.0%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.0404|26.55|-0.4905|-1.81%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|156.0215|39.2081|-116.8134|-74.87%|

## No Regressions Found

## No Progressions Found

