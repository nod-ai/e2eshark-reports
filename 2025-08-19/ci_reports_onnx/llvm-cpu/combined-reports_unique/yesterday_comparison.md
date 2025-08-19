# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|199.7333|212.1763|12.443|6.23%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|225.1835|211.3736|-13.8099|-6.13%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|569.81|567.8197|-1.9904|-0.35%|
|migraphx_ORT__distilgpt2_1|PASS|regression|78.5083|91.3527|12.8444|16.36%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|191.8665|191.4847|-0.3819|-0.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|549.4933|546.1564|-3.3369|-0.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|89.0059|89.6808|0.675|0.76%|
|migraphx_bert__bert-large-uncased|PASS|within tol|379.9584|367.6256|-12.3328|-3.25%|
|migraphx_cadene__dpn92i1|PASS|progression|204.3531|163.9522|-40.4008|-19.77%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5340.4988|5285.5077|-54.991|-1.03%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|314.1293|334.1015|19.9722|6.36%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|424.4994|636.9219|212.4225|50.04%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|440.7021|488.7145|48.0124|10.89%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|90.7429|94.8176|4.0747|4.49%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|65.7288|60.7116|-5.0173|-7.63%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|217.3382|245.3173|27.9792|12.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.7912|65.3325|-7.4587|-10.25%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.1384|20.4886|2.3502|12.96%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1525.6899|1595.1944|69.5045|4.56%|
|migraphx_torchvision__inceptioni1|PASS|regression|201.7146|215.4435|13.7289|6.81%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.2083|83.36|0.1517|0.18%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1546.6812|1518.1866|-28.4947|-1.84%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5285.635|5377.5119|91.8769|1.74%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9385.5723|9399.7699|14.1976|0.15%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|143.5081|156.9142|13.4061|9.34%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|340.266|247.8261|-92.4399|-27.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|366.3532|367.2593|0.9061|0.25%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.5408|239.1082|0.5675|0.24%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|430.3426|428.2201|-2.1225|-0.49%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|659.9314|921.2489|261.3175|39.6%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5324.3796|5062.101|-262.2786|-4.93%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14460.8592|13757.0591|-703.8001|-4.87%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|24022.2315|22021.7273|-2000.5042|-8.33%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|415.2394|403.9292|-11.3102|-2.72%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|796.2124|793.9007|-2.3117|-0.29%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1232.6343|1279.3982|46.7639|3.79%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|736.8246|735.4244|-1.4001|-0.19%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1614.9935|1640.5843|25.5908|1.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3376.3363|3423.9681|47.6318|1.41%|

## No Regressions Found

## No Progressions Found

