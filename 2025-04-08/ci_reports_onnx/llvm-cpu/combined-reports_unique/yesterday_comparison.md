# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.4484|89.6266|-0.8218|-0.91%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.0098|87.8732|-1.1366|-1.28%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|249.2317|269.414|20.1823|8.1%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|37.0504|38.1673|1.1169|3.01%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.3311|95.4824|10.1513|11.9%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|258.9222|290.637|31.7148|12.25%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|95.7787|40.0937|-55.685|-58.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|476.0209|454.0518|-21.969|-4.62%|
|migraphx_cadene__dpn92i1|PASS|regression|165.2342|174.4034|9.1692|5.55%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5875.1969|5935.2292|60.0323|1.02%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|328.5535|323.961|-4.5926|-1.4%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|403.0438|811.8873|408.8435|101.44%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|426.3073|428.6127|2.3054|0.54%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|102.5867|100.6456|-1.9411|-1.89%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.0229|35.1011|3.0782|9.61%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.7173|182.0952|1.3779|0.76%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|81.2308|66.8025|-14.4283|-17.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|21.7795|17.6512|-4.1283|-18.96%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1597.9284|1622.008|24.0796|1.51%|
|migraphx_torchvision__inceptioni1|PASS|within tol|189.6611|190.5891|0.928|0.49%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.6373|87.0555|3.4182|4.09%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1535.189|1594.9716|59.7827|3.89%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3042.1697|3068.5955|26.4258|0.87%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4998.0147|4780.0587|-217.9561|-4.36%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|149.9556|214.9722|65.0166|43.36%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|343.0874|303.6901|-39.3973|-11.48%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|385.3376|364.2066|-21.131|-5.48%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|236.6365|234.1372|-2.4993|-1.06%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|447.4054|525.3074|77.902|17.41%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|663.1517|686.2236|23.0719|3.48%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|2953.6052|3146.5683|192.963|6.53%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5773.3755|5799.3292|25.9536|0.45%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|8987.5585|9136.4175|148.8591|1.66%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|434.4321|419.5926|-14.8395|-3.42%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|817.6933|887.5051|69.8118|8.54%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1238.8076|1236.3552|-2.4524|-0.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|736.9976|759.5424|22.5447|3.06%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1528.3497|1648.908|120.5582|7.89%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2467.0195|2372.1739|-94.8455|-3.84%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|resnest50d_1s4x24d_Opset17_timm|PASS|compilation|

## No Progressions Found

