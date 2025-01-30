# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|92.6903|120.9299|28.2396|30.47%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.0811|88.4861|0.4051|0.46%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|258.8427|255.797|-3.0457|-1.18%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7|29.955|-0.7449|-2.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.9892|95.5575|11.5682|13.77%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.4984|249.9069|-0.5915|-0.24%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|38.8855|45.6843|6.7988|17.48%|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.2558|370.5307|1.2749|0.35%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.6184|164.3352|-1.2831|-0.77%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5496.4292|5602.3825|105.9533|1.93%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.7181|319.8749|-3.8432|-1.19%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5027.7424|5080.6141|52.8718|1.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|381.2928|372.9824|-8.3105|-2.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|440.6069|424.0605|-16.5464|-3.76%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|98.5138|100.8105|2.2967|2.33%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|32.8999|30.9567|-1.9432|-5.91%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|188.6865|179.9147|-8.7718|-4.65%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|384.9049|91.7118|-293.1932|-76.17%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|46.1209|39.805|-6.3159|-13.69%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1541.2639|1492.9308|-48.3331|-3.14%|
|migraphx_torchvision__inceptioni1|PASS|within tol|207.1809|203.0548|-4.1261|-1.99%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5811.3481|5776.5917|-34.7564|-0.6%|
|migraphx_torchvision__resnet50i1|PASS|progression|89.1548|83.5608|-5.594|-6.27%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5275.4261|5426.43|151.0039|2.86%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2697.3993|2611.5524|-85.8469|-3.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4240.8947|4077.2371|-163.6576|-3.86%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5709.6744|5815.3013|105.6269|1.85%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|159.9755|160.0547|0.0792|0.05%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.1344|263.0947|-0.0398|-0.02%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|368.6564|388.8945|20.2381|5.49%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|433.7444|452.7449|19.0005|4.38%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|587.0961|581.1372|-5.9589|-1.01%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|835.1329|843.2373|8.1044|0.97%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5645.3074|5027.396|-617.9114|-10.95%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8111.7315|8816.0027|704.2712|8.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11258.8638|11271.7559|12.8922|0.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|722.4526|737.3061|14.8536|2.06%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1088.9231|1076.4619|-12.4612|-1.14%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1538.5037|1552.408|13.9044|0.9%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1443.5904|1305.3583|-138.2322|-9.58%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2150.6105|2062.4858|-88.1247|-4.1%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2873.6365|2887.2919|13.6554|0.48%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|PASS|Numerics|

## No Progressions Found

