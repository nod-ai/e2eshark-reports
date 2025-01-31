# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.1075|105.3868|-0.7207|-0.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.8246|105.9748|0.1502|0.14%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|467.0218|478.1015|11.0798|2.37%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|57.1207|57.6547|0.534|0.93%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.7029|63.7114|1.0084|1.61%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|268.3473|272.1038|3.7565|1.4%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.7669|35.3939|1.627|4.82%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8607|19.0554|0.1947|1.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9446|7.0213|0.0767|1.1%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.0294|26.2554|-0.7739|-2.86%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.4138|6.4444|0.0305|0.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.6908|44.3264|1.6355|3.83%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|142.5906|150.161|7.5704|5.31%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.7569|16.806|-0.9509|-5.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.6451|8.2354|1.5903|23.93%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.0002|60.8293|-0.1709|-0.28%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.5563|32.5821|1.0257|3.25%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.3968|54.6984|1.3016|2.44%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|69.93|71.9615|2.0315|2.91%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9233|12.0815|0.1582|1.33%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.2179|12.3318|0.1139|0.93%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0708|19.0599|-0.011|-0.06%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8968|12.6368|-0.26|-2.02%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.5578|16.3|2.7423|20.23%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.745|20.9266|0.1816|0.88%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|65.6473|69.756|4.1087|6.26%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|98.0734|114.7212|16.6478|16.97%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|138.7628|142.771|4.0083|2.89%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2615|14.4388|0.1773|1.24%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.4909|29.8524|13.3615|81.02%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|25.9216|188.1292|162.2076|625.76%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.9072|19.3436|0.4364|2.31%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2691|27.0404|0.7713|2.94%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|39.1913|156.0215|116.8302|298.1%|

## No Regressions Found

## No Progressions Found

