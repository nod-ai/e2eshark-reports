# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|368.8301|576.2975|207.4673|56.25%|
|migraphx_cadene__dpn92i1|PASS|within tol|168.283|171.408|3.125|1.86%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5823.8636|6075.323|251.4593|4.32%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|318.0199|318.9551|0.9352|0.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|456.0039|587.8378|131.8338|28.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|423.6294|1437.6258|1013.9964|239.36%|
|migraphx_mlperf__resnet50_v1|PASS|regression|86.1665|312.2767|226.1102|262.41%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|59.1215|58.117|-1.0046|-1.7%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|207.9037|208.6807|0.777|0.37%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|67.61|65.5234|-2.0866|-3.09%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|20.9261|18.672|-2.2541|-10.77%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1451.5379|1472.1142|20.5763|1.42%|
|migraphx_torchvision__inceptioni1|PASS|regression|200.7099|370.7087|169.9989|84.7%|
|migraphx_torchvision__resnet50i1|PASS|regression|88.1221|116.4899|28.3677|32.19%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1581.1822|1556.2288|-24.9534|-1.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5368.9476|5479.3048|110.3572|2.06%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9398.3004|9459.8348|61.5344|0.65%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.5268|151.2567|0.7299|0.48%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|252.2242|432.0295|179.8053|71.29%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|361.2365|421.2096|59.973|16.6%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|240.4515|247.6048|7.1533|2.97%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|682.9624|500.7896|-182.1728|-26.67%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|705.83|650.6256|-55.2044|-7.82%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4947.2205|5129.9348|182.7143|3.69%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13994.7636|13373.2578|-621.5057|-4.44%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24361.0068|23926.5574|-434.4494|-1.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|402.3782|412.6365|10.2583|2.55%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|795.6835|788.0905|-7.593|-0.95%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1238.5217|1304.578|66.0563|5.33%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|756.7171|742.0399|-14.6772|-1.94%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1909.744|1792.7861|-116.9579|-6.12%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3497.8481|3530.0368|32.1887|0.92%|

## No Regressions Found

## No Progressions Found

