# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.632|89.2728|3.6408|4.25%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|95.5742|9.4218|10.94%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.9527|261.2976|0.3449|0.13%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.2671|32.318|1.0509|3.36%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.0977|96.4069|13.3092|16.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.0676|252.708|8.6404|3.54%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5572|42.8089|2.2516|5.55%|
|migraphx_bert__bert-large-uncased|PASS|within tol|410.0501|385.0398|-25.0103|-6.1%|
|migraphx_bert__bertsquad-12|PASS|within tol|95.476|86.9863|-8.4897|-8.89%|
|migraphx_cadene__dpn92i1|PASS|within tol|186.2736|177.0831|-9.1906|-4.93%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|7257.2016|6768.0777|-489.1239|-6.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.1171|328.2752|-1.8419|-0.56%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|420.8|412.386|-8.414|-2.0%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|456.7549|496.5831|39.8282|8.72%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.8666|99.3379|-1.5287|-1.52%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.8811|37.832|-3.0492|-7.46%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.9736|188.7855|5.8119|3.18%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|70.2852|88.1692|17.884|25.44%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|41.0543|41.6763|0.622|1.52%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1377.2882|1406.1937|28.9055|2.1%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|219.8629|-38.8796|-15.03%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6648.7116|6633.6207|-15.091|-0.23%|
|migraphx_torchvision__resnet50i1|PASS|within tol|99.4756|96.5473|-2.9284|-2.94%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6088.0794|6143.9335|55.8541|0.92%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2688.5782|2506.1017|-182.4765|-6.79%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4097.8175|4177.947|80.1295|1.96%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6359.273|5945.1986|-414.0745|-6.51%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|188.254|170.7411|-17.5128|-9.3%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|380.8856|348.2105|-32.6751|-8.58%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|392.6775|403.6409|10.9634|2.79%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|464.1775|511.3066|47.1291|10.15%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|646.0645|626.1882|-19.8763|-3.08%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|845.906|825.8407|-20.0653|-2.37%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5134.5125|5834.4772|699.9647|13.63%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8841.4288|8332.3192|-509.1096|-5.76%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11939.3575|12572.4161|633.0586|5.3%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|745.4025|772.197|26.7945|3.59%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1125.1086|1217.1607|92.052|8.18%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1749.2347|1734.514|-14.7207|-0.84%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1532.455|1495.3134|-37.1415|-2.42%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2403.9663|2401.7946|-2.1717|-0.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3127.1362|3223.6001|96.4638|3.08%|

## No Regressions Found

## No Progressions Found

