# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.3694|107.1599|0.7905|0.74%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.9545|106.7762|-0.1782|-0.17%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|476.4884|472.1002|-4.3882|-0.92%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.156|61.2858|1.1299|1.88%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.8058|64.7885|-0.0173|-0.03%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.713|272.4453|-0.2677|-0.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.4594|32.2578|-0.2017|-0.62%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5748|19.38|-0.1949|-1.0%|
|migraphx_cadene__dpn92i1|Numerics|within tol|64.4245|64.4705|0.046|0.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.1959|149.2934|0.0976|0.07%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|172.8135|173.418|0.6045|0.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2022|7.0392|-0.1629|-2.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|25.6237|24.8535|-0.7702|-3.01%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.3581|42.3836|0.0255|0.06%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.1467|142.5567|-1.59|-1.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.4849|17.291|0.8061|4.89%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.3942|6.7988|-0.5954|-8.05%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|64.938|64.8904|-0.0476|-0.07%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.2555|61.212|-0.0435|-0.07%|
|migraphx_torchvision__inceptioni32|PASS|within tol|101.075|100.986|-0.089|-0.09%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|15.8315|15.8955|0.064|0.4%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|145.6363|145.4885|-0.1479|-0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.7273|32.6538|-1.0735|-3.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.5098|54.9235|-2.5863|-4.5%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|76.973|73.996|-2.977|-3.87%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1771|11.9303|-0.2468|-2.03%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7834|12.5681|-0.2153|-1.68%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.7095|19.5376|-0.1719|-0.87%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9453|12.7675|-0.1779|-1.37%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4223|13.2494|-0.1729|-1.29%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6423|21.2021|-0.4402|-2.03%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.5475|67.3805|-2.1669|-3.12%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|106.2159|101.6408|-4.575|-4.31%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|156.0975|149.9855|-6.112|-3.92%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5018|14.3724|-0.1295|-0.89%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.1001|16.7087|-0.3914|-2.29%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.9864|26.0894|-0.897|-3.32%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.6325|19.0635|-0.5691|-2.9%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.3513|27.2436|-1.1076|-3.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.3142|40.6415|-1.6726|-3.95%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_cadene__resnext101_64x4di16|Numerics|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|tf_mixnet_s.in1k|compilation|PASS|

