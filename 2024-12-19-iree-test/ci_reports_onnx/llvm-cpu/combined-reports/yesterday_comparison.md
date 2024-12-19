# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.0233|88.087|2.0637|2.4%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|87.8858|505.1564|417.2706|474.79%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|259.2561|256.5549|-2.7012|-1.04%|
|migraphx_ORT__distilgpt2_1|PASS|regression|29.9149|31.454|1.5391|5.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|93.0326|87.8854|-5.1472|-5.53%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|294.6202|253.5776|-41.0426|-13.93%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.2245|39.4531|-1.7714|-4.3%|
|migraphx_bert__bert-large-uncased|PASS|within tol|393.7123|376.0012|-17.7111|-4.5%|
|migraphx_bert__bertsquad-12|PASS|within tol|85.3792|82.809|-2.5702|-3.01%|
|migraphx_cadene__dpn92i1|PASS|regression|170.2512|180.2003|9.9491|5.84%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5928.8039|5837.5916|-91.2123|-1.54%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|354.3592|321.188|-33.1713|-9.36%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5121.2677|5125.3037|4.036|0.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|416.5622|406.5148|-10.0474|-2.41%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|935.4361|423.9318|-511.5042|-54.68%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|88.9748|88.9033|-0.0715|-0.08%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|70.8941|35.9733|-34.9208|-49.26%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.4778|184.0885|1.6107|0.88%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|94.1519|85.1504|-9.0014|-9.56%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|45.3205|38.4396|-6.8809|-15.18%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1578.0515|1629.9234|51.8719|3.29%|
|migraphx_torchvision__inceptioni1|PASS|regression|205.5362|216.086|10.5498|5.13%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6141.1661|6137.5565|-3.6096|-0.06%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.6586|87.4172|0.7586|0.88%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5919.8881|5831.5557|-88.3324|-1.49%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2663.2785|2672.6654|9.387|0.35%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4023.0625|3977.4402|-45.6223|-1.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5804.7327|5740.5547|-64.1779|-1.11%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.1311|166.9079|10.7767|6.9%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.8263|262.0426|0.2163|0.08%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|377.9521|404.4827|26.5306|7.02%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|434.681|380.2946|-54.3864|-12.51%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|655.122|592.8476|-62.2744|-9.51%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|829.395|824.0995|-5.2956|-0.64%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5165.4088|5054.4083|-111.0005|-2.15%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8075.9279|7938.8043|-137.1237|-1.7%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11376.1604|12504.3777|1128.2172|9.92%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|898.041|696.9993|-201.0417|-22.39%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1080.2887|1123.814|43.5253|4.03%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1511.3237|1546.0585|34.7349|2.3%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1283.0452|1473.2999|190.2547|14.83%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2213.8235|2130.1025|-83.721|-3.78%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2915.6189|2946.2481|30.6292|1.05%|

## No Regressions Found

## No Progressions Found

