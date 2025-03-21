# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|100.785|91.8498|-8.9352|-8.87%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|85.0499|103.8118|18.762|22.06%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|246.5933|257.0861|10.4928|4.26%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.6078|32.7725|2.1647|7.07%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.8612|85.5537|0.6925|0.82%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|252.2701|260.5854|8.3153|3.3%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|45.0255|43.3885|-1.6369|-3.64%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.0906|1.344|0.2534|23.23%|
|migraphx_bert__bert-large-uncased|PASS|progression|439.6818|385.6681|-54.0137|-12.28%|
|migraphx_cadene__dpn92i1|PASS|regression|205.3725|219.3155|13.943|6.79%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5419.35|5418.9938|-0.3562|-0.01%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|325.8326|326.0242|0.1916|0.06%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5076.0981|5192.0728|115.9747|2.28%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|402.217|401.4459|-0.7711|-0.19%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|441.1857|421.4613|-19.7244|-4.47%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|93.9293|95.3181|1.3888|1.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.2984|34.0664|0.768|2.31%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|177.8853|189.3703|11.485|6.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.6279|80.3825|1.7546|2.23%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|45.0989|43.2576|-1.8413|-4.08%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1444.2201|1439.1858|-5.0343|-0.35%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.3474|198.0967|-0.2507|-0.13%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5796.6015|5706.3755|-90.2261|-1.56%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.4775|94.6686|11.1911|13.41%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5404.2102|5439.7977|35.5875|0.66%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1506.2077|1521.6218|15.414|1.02%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3005.7288|2960.7283|-45.0005|-1.5%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4806.1681|4694.1204|-112.0477|-2.33%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|177.9419|149.5207|-28.4211|-15.97%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|279.4549|297.3271|17.8723|6.4%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|360.2051|361.8664|1.6613|0.46%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.4198|239.9282|1.5083|0.63%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|448.6378|457.7505|9.1127|2.03%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|664.3087|1118.8348|454.5262|68.42%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2800.7484|2856.1157|55.3673|1.98%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5763.7617|5866.7522|102.9906|1.79%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9146.9901|9060.007|-86.9831|-0.95%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|412.897|422.4337|9.5367|2.31%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|796.6873|819.3767|22.6895|2.85%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1406.0666|1228.3063|-177.7603|-12.64%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|745.8391|739.9245|-5.9145|-0.79%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1571.1137|1517.9188|-53.1949|-3.39%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|2628.6689|2461.0138|-167.6551|-6.38%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|

