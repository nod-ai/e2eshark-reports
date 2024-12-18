# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|97.5123|86.0233|-11.4891|-11.78%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|111.0636|87.8858|-23.1777|-20.87%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|311.9866|259.2561|-52.7306|-16.9%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.0586|29.9149|-1.1437|-3.68%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.5953|93.0326|7.4374|8.69%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|253.7612|294.6202|40.859|16.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.1763|41.2245|2.0481|5.23%|
|migraphx_bert__bert-large-uncased|PASS|progression|915.7402|393.7123|-522.0279|-57.01%|
|migraphx_bert__bertsquad-12|PASS|progression|149.4601|85.3792|-64.0809|-42.87%|
|migraphx_cadene__dpn92i1|PASS|within tol|178.612|170.2512|-8.3608|-4.68%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5896.2644|5928.8039|32.5395|0.55%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|325.2238|354.3592|29.1354|8.96%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5178.9491|5121.2677|-57.6814|-1.11%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|430.3492|416.5622|-13.7869|-3.2%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|576.2465|935.4361|359.1895|62.33%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|89.3371|88.9748|-0.3624|-0.41%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.1121|70.8941|38.7821|120.77%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.4787|182.4778|0.9992|0.55%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|100.2215|94.1519|-6.0696|-6.06%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|57.0627|45.3205|-11.7422|-20.58%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1655.065|1578.0515|-77.0135|-4.65%|
|migraphx_torchvision__inceptioni1|PASS|within tol|201.3802|205.5362|4.1561|2.06%|
|migraphx_torchvision__inceptioni32|PASS|regression|5844.9753|6141.1661|296.1908|5.07%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.2895|86.6586|0.3691|0.43%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5886.5782|5919.8881|33.3098|0.57%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2497.9823|2663.2785|165.2962|6.62%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4165.8412|4023.0625|-142.7787|-3.43%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5687.7121|5804.7327|117.0206|2.06%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.292|156.1311|-0.1609|-0.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.4975|261.8263|-3.6712|-1.38%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|421.4732|377.9521|-43.5211|-10.33%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|382.9409|434.681|51.7401|13.51%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|587.8745|655.122|67.2475|11.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|804.2592|829.395|25.1358|3.13%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5117.9919|5165.4088|47.4169|0.93%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8145.2506|8075.9279|-69.3226|-0.85%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11434.7609|11376.1604|-58.6005|-0.51%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|716.5291|898.041|181.5119|25.33%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1104.5579|1080.2887|-24.2692|-2.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1517.9009|1511.3237|-6.5772|-0.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1299.2821|1283.0452|-16.2369|-1.25%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2352.8348|2213.8235|-139.0114|-5.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2929.231|2915.6189|-13.6122|-0.46%|

## No Regressions Found

## No Progressions Found

