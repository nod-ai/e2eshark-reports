# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.0834|115.2077|0.1243|0.11%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.8043|113.9467|0.1424|0.13%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|370.9278|369.5639|-1.3639|-0.37%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|65.3543|64.6469|-0.7074|-1.08%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|73.1399|72.5031|-0.6368|-0.87%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|280.0496|273.3616|-6.688|-2.39%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.8531|39.2036|-0.6495|-1.63%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.9868|20.0833|0.0965|0.48%|
|migraphx_bert__bertsquad-12|PASS|within tol|17.492|17.3004|-0.1916|-1.1%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|158.5605|155.5652|-2.9953|-1.89%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.4432|215.3143|-3.1289|-1.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|8.0117|7.5629|-0.4488|-5.6%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.0391|43.0461|-0.993|-2.25%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5038|6.7811|0.2773|4.26%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.119|31.9267|0.8077|2.6%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.1553|52.761|-0.3944|-0.74%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|22.0763|20.9018|-1.1745|-5.32%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|12.2222|14.9249|2.7027|22.11%|
|migraphx_torchvision__densenet121i32|PASS|within tol|53.3544|52.7186|-0.6358|-1.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9201|15.8452|-0.0749|-0.47%|
|migraphx_torchvision__inceptioni32|PASS|within tol|147.3437|144.1714|-3.1723|-2.15%|
|migraphx_torchvision__resnet50i64|PASS|within tol|194.2998|190.7822|-3.5176|-1.81%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.6309|33.5461|-1.0848|-3.13%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|59.4919|57.966|-1.5259|-2.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.6122|73.5668|-2.0454|-2.71%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5114|13.5601|0.0487|0.36%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.7415|13.8698|0.1282|0.93%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0045|20.1016|0.0971|0.49%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3949|13.4166|0.0216|0.16%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9571|14.1263|0.1692|1.21%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.8746|21.7805|-0.0941|-0.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.4641|69.3343|-2.1298|-2.98%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.2408|104.6799|-3.5609|-3.29%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|149.8323|145.096|-4.7364|-3.16%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1758|15.1866|0.0108|0.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.8141|17.5464|-0.2677|-1.5%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.2554|26.8922|-0.3631|-1.33%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6803|20.3256|-0.3547|-1.72%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.7962|28.106|-0.6902|-2.4%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.5842|41.4158|-1.1684|-2.74%|

## No Regressions Found

## No Progressions Found

