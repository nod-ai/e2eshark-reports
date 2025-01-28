# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.7722|92.6903|6.9181|8.07%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|95.5347|88.0811|-7.4536|-7.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|278.8038|258.8427|-19.9611|-7.16%|
|migraphx_ORT__distilgpt2_1|PASS|progression|36.9123|30.7|-6.2124|-16.83%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.919|83.9892|-0.9297|-1.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|287.3984|250.4984|-36.9001|-12.84%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.7776|38.8855|-3.892|-9.1%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.9064|369.2558|-3.6506|-0.98%|
|migraphx_cadene__dpn92i1|PASS|within tol|166.6912|165.6184|-1.0728|-0.64%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5296.5328|5496.4292|199.8964|3.77%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|332.2958|323.7181|-8.5776|-2.58%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5839.0741|5027.7424|-811.3318|-13.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|706.5921|381.2928|-325.2993|-46.04%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|417.5092|440.6069|23.0977|5.53%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|98.9541|98.5138|-0.4403|-0.44%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.3843|32.8999|-0.4844|-1.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.6133|188.6865|8.0732|4.47%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|81.5956|384.9049|303.3093|371.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.0856|46.1209|6.0352|15.06%|
|migraphx_torchvision__densenet121i32|PASS|progression|1716.2118|1541.2639|-174.9479|-10.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.8268|207.1809|-1.6459|-0.79%|
|migraphx_torchvision__inceptioni32|PASS|regression|5346.5861|5811.3481|464.762|8.69%|
|migraphx_torchvision__resnet50i1|PASS|progression|94.6173|89.1548|-5.4625|-5.77%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5072.8071|5275.4261|202.619|3.99%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2611.641|2697.3993|85.7584|3.28%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4219.9915|4240.8947|20.9032|0.5%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5713.5716|5709.6744|-3.8972|-0.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|154.1061|159.9755|5.8694|3.81%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.4949|263.1344|-2.3605|-0.89%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|381.6854|368.6564|-13.0289|-3.41%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|376.9752|433.7444|56.7691|15.06%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|598.1153|587.0961|-11.0191|-1.84%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|848.0238|835.1329|-12.8909|-1.52%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5050.144|5645.3074|595.1634|11.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8122.3223|8111.7315|-10.5908|-0.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11156.3346|11258.8638|102.5291|0.92%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|716.118|722.4526|6.3346|0.88%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1119.7461|1088.9231|-30.823|-2.75%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1501.3578|1538.5037|37.1459|2.47%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1328.8238|1443.5904|114.7667|8.64%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2035.6659|2150.6105|114.9446|5.65%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2891.6607|2873.6365|-18.0242|-0.62%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224|Numerics|PASS|

