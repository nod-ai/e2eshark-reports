# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|91.9651|85.6733|-6.2918|-6.84%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.8483|93.0272|3.1789|3.54%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.1904|258.431|-1.7594|-0.68%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.5065|31.0304|-0.4762|-1.51%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.9261|82.3073|-1.6187|-1.93%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|240.7538|274.8296|34.0758|14.15%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.3626|39.9241|-0.4386|-1.09%|
|migraphx_bert__bert-large-uncased|PASS|progression|404.0118|378.9233|-25.0885|-6.21%|
|migraphx_cadene__dpn92i1|PASS|regression|171.0632|433.3239|262.2607|153.31%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5674.2483|5595.699|-78.5493|-1.38%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|319.8017|350.8182|31.0165|9.7%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5188.7771|5166.5223|-22.2548|-0.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.8405|384.8007|4.9602|1.31%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|615.0845|502.3912|-112.6933|-18.32%|
|migraphx_mlperf__resnet50_v1|PASS|regression|87.5187|95.5354|8.0166|9.16%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|33.2301|31.3145|-1.9156|-5.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|197.0663|180.8036|-16.2628|-8.25%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|86.5258|77.139|-9.3868|-10.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|43.9293|40.1092|-3.8201|-8.7%|
|migraphx_torchvision__densenet121i32|PASS|regression|1481.0982|1664.518|183.4197|12.38%|
|migraphx_torchvision__inceptioni1|PASS|within tol|212.5907|210.5846|-2.0061|-0.94%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5786.9648|5818.3848|31.4199|0.54%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.8327|87.2771|-0.5556|-0.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5937.4086|5847.8817|-89.527|-1.51%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2741.5058|2542.6023|-198.9035|-7.26%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4038.2567|4104.9566|66.6999|1.65%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5797.9821|5920.4704|122.4883|2.11%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|320.2883|158.7854|-161.5029|-50.42%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|260.7635|268.5095|7.7459|2.97%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|368.0642|371.229|3.1648|0.86%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|400.246|410.9941|10.7481|2.69%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|596.3193|670.2538|73.9345|12.4%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|828.275|852.0254|23.7504|2.87%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5221.4575|5147.4086|-74.0489|-1.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8206.6131|8135.3355|-71.2775|-0.87%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11264.9895|11252.679|-12.3105|-0.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|719.082|710.8082|-8.2738|-1.15%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1126.6969|1084.5802|-42.1167|-3.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1579.0317|1534.4345|-44.5973|-2.82%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1283.7215|1403.7264|120.0049|9.35%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2104.2903|2140.1996|35.9093|1.71%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2988.8713|2990.1407|1.2693|0.04%|

## No Regressions Found

## No Progressions Found

