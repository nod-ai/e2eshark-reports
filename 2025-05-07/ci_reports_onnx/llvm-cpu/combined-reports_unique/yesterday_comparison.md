# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|806.3366|370.1102|-436.2264|-54.1%|
|migraphx_cadene__dpn92i1|PASS|progression|228.0272|167.7351|-60.292|-26.44%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5658.31|5552.0132|-106.2968|-1.88%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.1154|319.8471|0.7317|0.23%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|456.2739|446.368|-9.9058|-2.17%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|427.6723|427.7162|0.0439|0.01%|
|migraphx_mlperf__resnet50_v1|PASS|progression|97.1404|87.606|-9.5344|-9.82%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|57.5249|65.8668|8.3419|14.5%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|233.7867|228.6677|-5.119|-2.19%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|58.8634|68.2013|9.338|15.86%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|20.7265|18.9593|-1.7672|-8.53%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1495.0815|1437.0102|-58.0713|-3.88%|
|migraphx_torchvision__inceptioni1|PASS|regression|201.6287|217.8575|16.2288|8.05%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.3044|84.3249|0.0205|0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1574.5622|1692.0887|117.5264|7.46%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5380.7343|5348.7693|-31.965|-0.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9305.6212|9619.6332|314.012|3.37%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|179.7589|149.1579|-30.601|-17.02%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.079|273.6381|8.5591|3.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|367.2539|377.5878|10.3339|2.81%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|242.348|247.2711|4.9231|2.03%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|431.5223|469.843|38.3207|8.88%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|667.9362|721.7453|53.8091|8.06%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5091.5415|5241.1779|149.6364|2.94%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14072.9163|13969.1677|-103.7486|-0.74%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22977.8865|23928.1815|950.2949|4.14%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|414.7023|428.4203|13.718|3.31%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|787.0337|893.2779|106.2442|13.5%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1231.3937|1234.1976|2.8039|0.23%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|752.2915|744.8371|-7.4544|-0.99%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1969.0253|1740.9222|-228.103|-11.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3606.7788|3517.8225|-88.9562|-2.47%|

## No Regressions Found

## No Progressions Found

