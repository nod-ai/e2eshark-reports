# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.632|90.3449|4.7128|5.5%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.1524|86.8042|0.6518|0.76%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.9527|280.7138|19.7611|7.57%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.2671|33.9991|2.732|8.74%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.0977|86.2848|3.1871|3.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.0676|265.0549|20.9874|8.6%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5572|41.2926|0.7354|1.81%|
|migraphx_bert__bert-large-uncased|PASS|within tol|410.0501|398.202|-11.8481|-2.89%|
|migraphx_bert__bertsquad-12|PASS|within tol|95.476|86.8644|-8.6116|-9.02%|
|migraphx_cadene__dpn92i1|PASS|regression|186.2736|363.4492|177.1756|95.12%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|7257.2016|6851.1933|-406.0083|-5.59%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.1171|316.3572|-13.7599|-4.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|420.8|424.9328|4.1328|0.98%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|456.7549|445.3302|-11.4247|-2.5%|
|migraphx_mlperf__resnet50_v1|PASS|regression|100.8666|111.3024|10.4358|10.35%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.8811|38.1558|-2.7253|-6.67%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|182.9736|201.4482|18.4746|10.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|70.2852|96.6838|26.3986|37.56%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|41.0543|46.1934|5.1391|12.52%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1377.2882|1312.1755|-65.1126|-4.73%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|229.9945|-28.748|-11.11%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6648.7116|6582.8115|-65.9001|-0.99%|
|migraphx_torchvision__resnet50i1|PASS|within tol|99.4756|92.8842|-6.5914|-6.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6088.0794|6218.3269|130.2475|2.14%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2688.5782|2815.1919|126.6137|4.71%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4097.8175|4593.8239|496.0064|12.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6359.273|5820.1679|-539.1052|-8.48%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|167.3264|-20.9275|-11.12%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|259.6628|-121.2228|-31.83%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|392.6775|403.5369|10.8594|2.77%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|464.1775|428.0262|-36.1513|-7.79%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|646.0645|690.8333|44.7688|6.93%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|845.906|907.619|61.713|7.3%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5134.5125|5323.1451|188.6326|3.67%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8841.4288|8096.2312|-745.1976|-8.43%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11939.3575|11143.7281|-795.6294|-6.66%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|745.4025|788.5566|43.1542|5.79%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1125.1086|1229.2148|104.1062|9.25%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1749.2347|1824.5955|75.3608|4.31%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|1349.8454|-182.6096|-11.92%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|2145.8108|-258.1555|-10.74%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3127.1362|3020.5815|-106.5547|-3.41%|

## 8 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|pytorch-3dunet_vaiq_int8|PASS|Numerics|
|resmlp_12_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_12_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|PASS|compilation|

## No Progressions Found

