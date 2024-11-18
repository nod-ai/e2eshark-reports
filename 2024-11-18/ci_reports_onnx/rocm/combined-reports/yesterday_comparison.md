# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.8946|112.8332|-2.0613|-1.79%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|114.7017|113.0051|-1.6966|-1.48%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|369.7793|368.5181|-1.2612|-0.34%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|63.0527|65.5955|2.5428|4.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.1546|72.0891|-0.0654|-0.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.5443|274.2828|-0.2615|-0.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.8575|39.2717|0.4142|1.07%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.1554|19.979|-0.1764|-0.88%|
|migraphx_bert__bertsquad-12|PASS|within tol|211.9121|211.0604|-0.8517|-0.4%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.1637|151.4539|-0.7098|-0.47%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|212.9788|212.6534|-0.3254|-0.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5527|7.5156|-0.0371|-0.49%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.069|43.7414|-0.3277|-0.74%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5736|6.5514|-0.0222|-0.34%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.2317|32.7043|-0.5274|-1.59%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.611|52.6103|-0.0007|-0.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|28.3214|24.5776|-3.7438|-13.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|18.1577|17.5411|-0.6165|-3.4%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.8828|50.8305|-0.0523|-0.1%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.8115|15.9441|0.1326|0.84%|
|migraphx_torchvision__inceptioni32|PASS|regression|138.5917|146.1326|7.5409|5.44%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.7947|182.561|-0.2337|-0.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.4548|32.9631|-0.4917|-1.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.7776|57.1158|-0.6618|-1.15%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.558|72.7739|-0.7841|-1.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5703|13.4779|-0.0923|-0.68%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8497|13.8527|0.003|0.02%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0889|19.7927|-0.2962|-1.47%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.334|13.3209|-0.0131|-0.1%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.8804|13.97|0.0897|0.65%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6231|21.5062|-0.1169|-0.54%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.5853|68.2538|-1.3315|-1.91%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.9378|103.8926|-1.0452|-1.0%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.4364|144.0693|-1.367|-0.94%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0161|15.0101|-0.0059|-0.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.4611|17.2649|-0.1962|-1.12%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.7998|26.6009|-0.1989|-0.74%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1483|19.9764|-0.1719|-0.85%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.9555|27.9102|-0.0453|-0.16%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.451|41.0297|-0.4212|-1.02%|

## No Regressions Found

## No Progressions Found

