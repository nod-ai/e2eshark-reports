# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.9859|86.6691|-0.3169|-0.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|111.4118|89.3308|-22.081|-19.82%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|255.9107|258.2173|2.3065|0.9%|
|migraphx_ORT__distilgpt2_1|PASS|progression|39.784|37.036|-2.748|-6.91%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|88.9209|84.2745|-4.6464|-5.23%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|411.1309|243.9908|-167.1401|-40.65%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.2856|39.754|-3.5315|-8.16%|
|migraphx_bert__bert-large-uncased|PASS|progression|562.0908|376.8478|-185.243|-32.96%|
|migraphx_cadene__dpn92i1|PASS|regression|166.7437|176.5467|9.803|5.88%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5334.0722|5356.1951|22.1229|0.41%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|323.2283|354.9186|31.6903|9.8%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5172.0243|5103.4575|-68.5669|-1.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|375.708|374.7191|-0.989|-0.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|482.0326|418.6464|-63.3862|-13.15%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|93.2712|92.076|-1.1952|-1.28%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.2626|31.541|0.2784|0.89%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|195.6759|180.3011|-15.3748|-7.86%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|81.6861|90.0222|8.3361|10.21%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.7298|46.4135|-0.3164|-0.68%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1683.3049|1607.924|-75.3809|-4.48%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.9449|195.7959|0.851|0.44%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5420.4419|5354.3868|-66.055|-1.22%|
|migraphx_torchvision__resnet50i1|PASS|progression|90.4322|84.3468|-6.0854|-6.73%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5045.7177|5135.2955|89.5778|1.78%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2584.914|2663.2587|78.3447|3.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4292.3684|4207.4417|-84.9267|-1.98%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5773.9899|5847.4913|73.5014|1.27%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.6176|176.8082|20.1906|12.89%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.3612|265.1669|1.8056|0.69%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|380.8744|375.4081|-5.4663|-1.44%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|387.9495|380.6366|-7.3129|-1.89%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|583.6216|771.9817|188.3601|32.27%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|881.1548|842.1844|-38.9705|-4.42%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5095.3965|5439.4443|344.0477|6.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8071.408|7945.7688|-125.6392|-1.56%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11212.8186|11494.3695|281.5509|2.51%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|696.8227|706.6742|9.8515|1.41%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1073.9302|1081.146|7.2159|0.67%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1553.41|1539.7732|-13.6368|-0.88%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1303.8075|1331.5884|27.781|2.13%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2096.0584|2114.6363|18.5779|0.89%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2901.1065|2919.3322|18.2257|0.63%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|PASS|Numerics|
|xcit_nano_12_p8_224_dist|PASS|Numerics|

## No Progressions Found

