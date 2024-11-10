# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.7154|111.9343|-0.7811|-0.69%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.1791|110.8113|-0.3678|-0.33%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|362.841|360.5406|-2.3004|-0.63%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.378|61.3184|-0.0596|-0.1%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0808|72.0945|0.0136|0.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.9309|273.0165|-0.9143|-0.33%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.6826|36.9475|0.265|0.72%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.9534|19.9268|-0.0266|-0.13%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.0894|151.2295|-0.8599|-0.57%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.1574|218.0442|-0.1132|-0.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.52|7.3701|-0.1499|-1.99%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|36.3787|40.7443|4.3655|12.0%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4515|6.4262|-0.0253|-0.39%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|27.886|28.8711|0.9851|3.53%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.4604|54.4802|2.0198|3.85%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.4213|19.9347|-0.4866|-2.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|14.9433|13.151|-1.7924|-11.99%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.4808|50.4203|-0.0605|-0.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.7467|15.7987|0.052|0.33%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.8999|137.4956|-0.4042|-0.29%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.7896|181.9723|-0.8173|-0.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.462|32.9673|-0.4948|-1.48%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.8547|56.9445|-0.9102|-1.57%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.633|72.8465|-0.7866|-1.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5023|13.4681|-0.0342|-0.25%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8002|13.8717|0.0716|0.52%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0147|19.9133|-0.1015|-0.51%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4097|13.2796|-0.1301|-0.97%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.858|14.0023|0.1443|1.04%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.57|21.4947|-0.0753|-0.35%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.4212|68.3715|-1.0497|-1.51%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|104.7267|136.3935|31.6668|30.24%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.172|144.0269|-1.1451|-0.79%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0849|15.0634|-0.0215|-0.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.3973|17.2758|-0.1214|-0.7%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.5924|26.472|-0.1205|-0.45%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0738|19.9966|-0.0772|-0.38%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1557|27.6692|-0.4864|-1.73%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.348|40.9502|-0.3978|-0.96%|

## No Regressions Found

## No Progressions Found

