# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|122.8649|110.8055|-12.0594|-9.82%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|128.6964|110.4396|-18.2568|-14.19%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|510.3024|475.9645|-34.338|-6.73%|
|migraphx_ORT__distilgpt2_1|PASS|progression|70.5943|59.7175|-10.8768|-15.41%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.456|65.1242|0.6682|1.04%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.408|273.3051|-1.103|-0.4%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.5926|34.1093|-8.4832|-19.92%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2314|19.0136|-0.2179|-1.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.6946|7.2484|-0.4462|-5.8%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|30.4512|26.2489|-4.2024|-13.8%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.0985|5.2237|0.1251|2.45%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|51.2647|43.7191|-7.5456|-14.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|50.5936|46.9665|-3.6271|-7.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|23.0726|18.5505|-4.5221|-19.6%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.73|9.3029|0.5729|6.56%|
|migraphx_torchvision__inceptioni1|PASS|progression|5.2795|4.8899|-0.3896|-7.38%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.3543|32.8203|-0.534|-1.6%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|56.5011|57.8731|1.372|2.43%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.3718|72.5504|0.1786|0.25%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|13.1609|12.0646|-1.0963|-8.33%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7487|12.4202|-0.3285|-2.58%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|21.1727|19.1856|-1.9871|-9.39%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3623|12.7913|-0.571|-4.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.1212|13.4941|-0.6271|-4.44%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|22.7432|21.0018|-1.7414|-7.66%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|71.8364|68.1018|-3.7346|-5.2%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|103.1141|101.5628|-1.5513|-1.5%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.527|143.2972|-1.2298|-0.85%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|15.3473|14.3931|-0.9542|-6.22%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.724|17.4591|-0.2648|-1.49%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.4437|26.3859|-1.0578|-3.85%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3367|20.1202|-0.2165|-1.06%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1971|27.1946|-1.0025|-3.56%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.3973|40.3803|-1.017|-2.46%|

## No Regressions Found

## No Progressions Found

