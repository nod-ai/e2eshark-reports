# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|86.6691|99.5859|12.9168|14.9%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|89.3308|94.4151|5.0844|5.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|258.2173|289.0242|30.8069|11.93%|
|migraphx_ORT__distilgpt2_1|PASS|progression|37.036|32.9903|-4.0458|-10.92%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.2745|82.7608|-1.5137|-1.8%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|243.9908|242.2416|-1.7492|-0.72%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.754|42.6612|2.9071|7.31%|
|migraphx_bert__bert-large-uncased|PASS|within tol|376.8478|381.6518|4.804|1.27%|
|migraphx_cadene__dpn92i1|PASS|within tol|176.5467|174.2721|-2.2747|-1.29%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5356.1951|5283.6271|-72.5679|-1.35%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|354.9186|346.5701|-8.3485|-2.35%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5103.4575|5084.2861|-19.1714|-0.38%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|374.7191|376.229|1.5099|0.4%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|418.6464|427.0422|8.3958|2.01%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.076|96.5149|4.439|4.82%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.541|31.9823|0.4414|1.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.3011|180.4075|0.1065|0.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|90.0222|82.365|-7.6572|-8.51%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|46.4135|52.5211|6.1076|13.16%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1607.924|1577.2036|-30.7205|-1.91%|
|migraphx_torchvision__inceptioni1|PASS|within tol|195.7959|195.0211|-0.7748|-0.4%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5354.3868|5423.6835|69.2966|1.29%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.3468|96.6659|12.319|14.61%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5135.2955|5036.6752|-98.6202|-1.92%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2663.2587|2508.3561|-154.9027|-5.82%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4207.4417|4171.5284|-35.9134|-0.85%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5847.4913|5748.4966|-98.9948|-1.69%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|176.8082|151.1181|-25.6901|-14.53%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.1669|260.5098|-4.6571|-1.76%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|375.4081|381.3087|5.9006|1.57%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|380.6366|387.8872|7.2505|1.9%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|771.9817|660.4135|-111.5681|-14.45%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|842.1844|854.0566|11.8722|1.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5439.4443|5224.268|-215.1763|-3.96%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7945.7688|8060.1037|114.3348|1.44%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11494.3695|12034.9478|540.5783|4.7%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|706.6742|708.5993|1.9251|0.27%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1081.146|1151.9038|70.7578|6.54%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1539.7732|1622.0537|82.2805|5.34%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1331.5884|1303.2081|-28.3804|-2.13%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2114.6363|2061.5355|-53.1008|-2.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2919.3322|2908.0851|-11.2471|-0.39%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|
|xcit_nano_12_p8_224_dist|Numerics|PASS|

