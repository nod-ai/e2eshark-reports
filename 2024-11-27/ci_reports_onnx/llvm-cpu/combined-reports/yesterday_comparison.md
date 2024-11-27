# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|97.0104|90.7649|-6.2455|-6.44%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.6564|122.5892|33.9328|38.27%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|267.9819|280.9099|12.9279|4.82%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.7572|32.5339|0.7767|2.45%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.2966|85.1283|-0.1684|-0.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|255.9586|248.303|-7.6555|-2.99%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.1689|39.1168|-2.0522|-4.98%|
|migraphx_bert__bert-large-uncased|PASS|within tol|383.8607|371.907|-11.9537|-3.11%|
|migraphx_bert__bertsquad-12|PASS|progression|106.5644|86.1339|-20.4305|-19.17%|
|migraphx_cadene__dpn92i1|PASS|progression|200.2046|180.7464|-19.4583|-9.72%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6805.5641|6701.4802|-104.0839|-1.53%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|333.1547|332.6039|-0.5508|-0.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.4035|384.2881|3.8847|1.02%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|497.5433|445.2474|-52.2959|-10.51%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.9538|100.169|-0.7848|-0.78%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.4394|32.1294|-3.31|-9.34%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|191.6728|183.3109|-8.3619|-4.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.5074|84.1869|2.6795|3.29%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.534|55.3045|12.7704|30.02%|
|migraphx_torchvision__densenet121i32|PASS|regression|1343.1806|1630.4017|287.2211|21.38%|
|migraphx_torchvision__inceptioni1|PASS|regression|233.0985|246.4476|13.3491|5.73%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6581.7695|6719.806|138.0366|2.1%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.5124|92.2682|2.7557|3.08%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6112.4826|6004.586|-107.8966|-1.77%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|3074.6249|2919.5237|-155.1012|-5.04%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4154.7231|4450.2131|295.4899|7.11%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|5645.488|6245.8297|600.3418|10.63%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|153.5714|175.6768|22.1054|14.39%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|264.9155|275.802|10.8865|4.11%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|384.8431|381.9974|-2.8457|-0.74%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|523.564|421.089|-102.475|-19.57%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|715.4069|668.3821|-47.0248|-6.57%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|819.9747|833.1787|13.204|1.61%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5494.0886|5695.5263|201.4378|3.67%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8236.9395|8552.6904|315.7509|3.83%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11361.5392|11761.3705|399.8313|3.52%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|729.7492|1059.5387|329.7895|45.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1133.1388|1138.017|4.8782|0.43%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1507.3179|1661.6247|154.3068|10.24%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1330.6263|1451.2537|120.6274|9.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2098.5529|2066.0848|-32.4682|-1.55%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2927.9945|3133.6533|205.6588|7.02%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|pytorch-3dunet_vaiq_int8|Numerics|PASS|

