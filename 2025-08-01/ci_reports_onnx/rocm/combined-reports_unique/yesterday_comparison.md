# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|109.7324|110.544|0.8116|0.74%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.2296|113.3277|2.0981|1.89%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|515.1525|510.0174|-5.1351|-1.0%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.2257|67.6242|-0.6015|-0.88%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.9392|61.7975|-0.1417|-0.23%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|269.1155|269.6144|0.4989|0.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.7564|36.0986|-0.6578|-1.79%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3509|19.1705|-0.1804|-0.93%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5295|3.5261|-0.0034|-0.1%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.2227|20.0981|-0.1247|-0.62%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2149|4.2105|-0.0043|-0.1%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1143|7.111|-0.0033|-0.05%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|28.2396|28.3735|0.1339|0.47%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0998|14.1362|0.0364|0.26%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.4544|43.0703|-1.384|-3.11%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|109.6613|109.6156|-0.0457|-0.04%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.7993|19.0953|0.296|1.57%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|10.1811|10.6015|0.4204|4.13%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.1268|14.1675|0.0407|0.29%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0912|3.0937|0.0025|0.08%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0575|2.0454|-0.0121|-0.59%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8318|25.8772|0.0454|0.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.2711|37.5834|0.3123|0.84%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.8462|56.5045|0.6583|1.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5485|12.7957|0.2472|1.97%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7108|12.7106|-0.0002|-0.0%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4549|19.3529|-0.102|-0.52%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.007|12.8608|-0.1462|-1.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1547|19.2887|0.134|0.7%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6716|19.671|-0.0006|-0.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.5487|35.916|0.3672|1.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|68.8975|69.7415|0.844|1.22%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|110.0469|111.2795|1.2325|1.12%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.434|19.3765|-0.0575|-0.3%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2582|20.2772|0.0191|0.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3727|23.4792|0.1065|0.46%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2844|20.2806|-0.0038|-0.02%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2237|26.2348|0.0111|0.04%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.6378|32.7936|0.1558|0.48%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|

