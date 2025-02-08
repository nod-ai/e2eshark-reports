# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|110.9448|87.7625|-23.1822|-20.9%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|92.7516|86.9703|-5.7813|-6.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|370.6139|250.4738|-120.14|-32.42%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.7858|30.4123|-3.3735|-9.98%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|86.2211|89.8928|3.6717|4.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|263.805|245.0376|-18.7674|-7.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|42.1297|42.2527|0.1231|0.29%|
|migraphx_bert__bert-large-uncased|PASS|regression|371.2289|396.1561|24.9272|6.71%|
|migraphx_cadene__dpn92i1|PASS|regression|168.4904|207.7728|39.2823|23.31%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5614.2399|5677.5063|63.2663|1.13%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|320.3225|354.6986|34.3761|10.73%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5809.4752|5446.0553|-363.4198|-6.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|474.8266|373.6685|-101.1581|-21.3%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|414.889|421.0027|6.1137|1.47%|
|migraphx_mlperf__resnet50_v1|PASS|progression|320.6454|99.8621|-220.7832|-68.86%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.0478|35.661|3.6132|11.27%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|189.8398|181.4037|-8.4361|-4.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|96.8032|74.8404|-21.9628|-22.69%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.169|44.7992|-1.3698|-2.97%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1468.6411|1440.4675|-28.1736|-1.92%|
|migraphx_torchvision__inceptioni1|PASS|progression|218.0747|198.9366|-19.1381|-8.78%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5772.3415|5771.2524|-1.0891|-0.02%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.9301|86.9394|-2.9907|-3.33%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5412.2094|5515.9567|103.7474|1.92%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2537.0999|2628.0296|90.9297|3.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4135.0989|4008.7258|-126.3731|-3.06%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5810.2428|5738.4714|-71.7714|-1.24%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.9746|165.269|4.2944|2.67%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|260.2316|268.9503|8.7187|3.35%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|411.8472|374.0527|-37.7944|-9.18%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|402.5475|415.3649|12.8174|3.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|654.0368|627.6831|-26.3536|-4.03%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|809.1087|920.6776|111.5689|13.79%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5655.0263|5757.5129|102.4866|1.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8369.744|8126.8714|-242.8727|-2.9%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11325.4803|11802.3664|476.8861|4.21%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|720.8713|1100.3276|379.4564|52.64%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1079.816|1215.4583|135.6423|12.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1499.6333|1514.7914|15.1582|1.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1286.6066|1258.6034|-28.0032|-2.18%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2088.3022|2166.2491|77.947|3.73%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2885.1793|2935.9786|50.7993|1.76%|

## No Regressions Found

## No Progressions Found

