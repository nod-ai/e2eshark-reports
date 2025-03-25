# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|87.6777|104.1231|16.4454|18.76%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.8532|88.6753|2.8221|3.29%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|255.0395|252.1336|-2.9059|-1.14%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.6885|33.0538|1.3652|4.31%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.3273|85.9437|0.6164|0.72%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|248.9968|251.9738|2.9769|1.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|48.0003|46.1294|-1.8709|-3.9%|
|migraphx_agentmodel__AgentModel|Numerics|regression|0.9701|1.1487|0.1785|18.4%|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.9674|372.1181|-9.8493|-2.58%|
|migraphx_cadene__dpn92i1|PASS|regression|173.0045|247.0732|74.0686|42.81%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5319.0566|5446.646|127.5894|2.4%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.0149|318.9504|2.9355|0.93%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|6495.7889|5118.2368|-1377.5521|-21.21%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|401.0919|406.5078|5.4159|1.35%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|430.3567|440.6401|10.2834|2.39%|
|migraphx_mlperf__resnet50_v1|PASS|progression|337.2449|95.1312|-242.1136|-71.79%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.7093|37.0447|5.3354|16.83%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.1977|179.4689|-2.7289|-1.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.5217|78.5607|-2.9611|-3.63%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|52.4198|45.3408|-7.079|-13.5%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1468.548|1473.7316|5.1836|0.35%|
|migraphx_torchvision__inceptioni1|PASS|progression|208.9001|197.5902|-11.3099|-5.41%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5753.0271|5792.5512|39.5241|0.69%|
|migraphx_torchvision__resnet50i1|PASS|progression|92.8046|83.8205|-8.9841|-9.68%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5454.3616|5437.1747|-17.1868|-0.32%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1410.0979|1414.1369|4.039|0.29%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|3151.9905|2946.7691|-205.2215|-6.51%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4746.7293|4873.0199|126.2906|2.66%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|163.058|162.8237|-0.2344|-0.14%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|256.4731|257.6866|1.2135|0.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|361.2156|360.0636|-1.152|-0.32%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|241.0937|239.2839|-1.8097|-0.75%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|493.3147|477.3336|-15.9811|-3.24%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|686.7582|675.119|-11.6392|-1.69%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2776.856|2785.9693|9.1133|0.33%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5932.5605|5827.351|-105.2095|-1.77%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9241.2565|9095.5214|-145.7351|-1.58%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|403.1391|417.3494|14.2103|3.52%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|796.9323|796.5356|-0.3967|-0.05%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1252.391|1233.2514|-19.1397|-1.53%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|753.1917|753.2772|0.0855|0.01%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1530.0204|1511.1661|-18.8543|-1.23%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2402.8|2401.1254|-1.6747|-0.07%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|

