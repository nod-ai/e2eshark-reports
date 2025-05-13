# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|368.8301|552.9318|184.1016|49.92%|
|migraphx_cadene__dpn92i1|PASS|regression|168.283|185.8459|17.5629|10.44%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5823.8636|6155.06|331.1964|5.69%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|318.0199|395.167|77.1471|24.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|456.0039|430.4875|-25.5164|-5.6%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|423.6294|431.5371|7.9077|1.87%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|86.1665|85.6596|-0.5069|-0.59%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|59.1215|57.8582|-1.2633|-2.14%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|207.9037|208.9423|1.0386|0.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|67.61|62.1864|-5.4236|-8.02%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.9261|20.7031|-0.223|-1.07%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1451.5379|1494.2119|42.674|2.94%|
|migraphx_torchvision__inceptioni1|PASS|within tol|200.7099|197.7097|-3.0001|-1.49%|
|migraphx_torchvision__resnet50i1|PASS|within tol|88.1221|89.6652|1.5431|1.75%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1581.1822|1615.865|34.6828|2.19%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5368.9476|5516.2178|147.2702|2.74%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9398.3004|9440.7319|42.4315|0.45%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.5268|147.1568|-3.37|-2.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|252.2242|254.6074|2.3832|0.94%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|361.2365|357.3122|-3.9244|-1.09%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|240.4515|240.3789|-0.0726|-0.03%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|682.9624|430.4742|-252.4882|-36.97%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|705.83|662.3074|-43.5225|-6.17%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|4947.2205|5225.1237|277.9031|5.62%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13994.7636|13736.3256|-258.4379|-1.85%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|24361.0068|22647.0243|-1713.9825|-7.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|402.3782|407.6725|5.2943|1.32%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|795.6835|788.4119|-7.2716|-0.91%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1238.5217|1217.722|-20.7997|-1.68%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|756.7171|744.0802|-12.6369|-1.67%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1909.744|1764.5278|-145.2161|-7.6%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3497.8481|3539.3932|41.5451|1.19%|

## No Regressions Found

## No Progressions Found

