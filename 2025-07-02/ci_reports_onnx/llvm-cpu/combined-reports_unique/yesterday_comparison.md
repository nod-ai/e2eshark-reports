# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|387.6909|371.3831|-16.3078|-4.21%|
|migraphx_cadene__dpn92i1|PASS|progression|704.7615|163.8095|-540.952|-76.76%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5338.5751|6271.4528|932.8777|17.47%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|313.0168|367.1598|54.143|17.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|407.8609|682.5319|274.6711|67.34%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.836|434.0889|9.2529|2.18%|
|migraphx_mlperf__resnet50_v1|PASS|regression|90.0365|105.8073|15.7708|17.52%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.4851|58.2708|-0.2143|-0.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|207.2135|273.3459|66.1323|31.92%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|62.8109|57.2531|-5.5578|-8.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|22.0049|18.2563|-3.7486|-17.04%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1536.7633|1568.2771|31.5138|2.05%|
|migraphx_torchvision__inceptioni1|PASS|progression|251.938|219.0242|-32.9138|-13.06%|
|migraphx_torchvision__resnet50i1|PASS|within tol|82.6031|82.9492|0.346|0.42%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1595.8228|1559.7128|-36.11|-2.26%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5325.6083|5160.355|-165.2533|-3.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9445.7777|9433.9747|-11.803|-0.12%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|147.9653|166.9145|18.9492|12.81%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|251.4864|345.2077|93.7213|37.27%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|363.1947|381.8995|18.7048|5.15%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|247.0404|256.5434|9.503|3.85%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|466.4974|429.8277|-36.6697|-7.86%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|1310.6646|674.8351|-635.8295|-48.51%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5201.0247|5238.9189|37.8943|0.73%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13986.7674|14081.7321|94.9646|0.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23963.5579|24184.3488|220.7909|0.92%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|418.1658|409.7059|-8.4599|-2.02%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|802.0844|791.8012|-10.2832|-1.28%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1225.276|1230.6828|5.4068|0.44%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|741.2209|755.9761|14.7552|1.99%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1696.9434|1669.0871|-27.8562|-1.64%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3389.3839|3553.7549|164.3711|4.85%|

## No Regressions Found

## No Progressions Found

