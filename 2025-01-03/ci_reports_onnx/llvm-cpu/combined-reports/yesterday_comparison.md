# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.5911|91.76|4.1689|4.76%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.6881|91.5874|4.8993|5.65%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|276.9994|307.7636|30.7642|11.11%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.4011|32.4162|2.0151|6.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|92.1112|93.5309|1.4197|1.54%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|242.3886|275.6515|33.263|13.72%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|41.9818|39.7189|-2.2629|-5.39%|
|migraphx_bert__bert-large-uncased|PASS|within tol|373.7697|374.4007|0.631|0.17%|
|migraphx_cadene__dpn92i1|PASS|within tol|169.3403|174.4035|5.0632|2.99%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5346.4808|5313.6184|-32.8624|-0.61%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|324.3817|322.8937|-1.488|-0.46%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5127.0395|5191.3361|64.2966|1.25%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.2964|394.9629|14.6665|3.86%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|417.8207|421.0879|3.2672|0.78%|
|migraphx_mlperf__resnet50_v1|PASS|progression|109.4143|88.6614|-20.753|-18.97%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.345|33.2299|0.8849|2.74%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.5458|180.5596|1.0139|0.56%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.1834|80.673|2.4897|3.18%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|46.203|55.1017|8.8987|19.26%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1634.9357|1620.3383|-14.5974|-0.89%|
|migraphx_torchvision__inceptioni1|PASS|within tol|213.4192|223.5933|10.1741|4.77%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5381.1677|5326.2075|-54.9601|-1.02%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.7897|91.1933|6.4036|7.55%|
|migraphx_torchvision__resnet50i64|PASS|progression|5452.8202|5046.2209|-406.5993|-7.46%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2643.3794|2608.2757|-35.1036|-1.33%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4121.6132|4163.8061|42.1928|1.02%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5770.3073|5818.0453|47.738|0.83%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|162.6092|161.0659|-1.5433|-0.95%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|261.742|293.3393|31.5973|12.07%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|382.4774|374.479|-7.9983|-2.09%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|392.0816|391.3239|-0.7577|-0.19%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|612.1139|580.1326|-31.9812|-5.22%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|898.6521|812.8515|-85.8006|-9.55%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5149.3818|5102.0631|-47.3187|-0.92%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8160.4954|8111.5947|-48.9007|-0.6%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11249.11|11092.1829|-156.9272|-1.4%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|790.0152|703.6385|-86.3767|-10.93%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1117.862|1079.2303|-38.6317|-3.46%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1538.9166|1525.3681|-13.5485|-0.88%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1361.7134|1334.4668|-27.2466|-2.0%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2039.7029|2058.3183|18.6153|0.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2923.1843|2957.1137|33.9294|1.16%|

## No Regressions Found

## No Progressions Found

