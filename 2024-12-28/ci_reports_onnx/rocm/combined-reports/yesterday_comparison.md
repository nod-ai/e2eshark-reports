# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|111.5105|99.3119|-12.1986|-10.94%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|100.8908|99.9642|-0.9266|-0.92%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|500.4231|501.7044|1.2813|0.26%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|54.0124|53.472|-0.5404|-1.0%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.3239|61.2068|-2.1172|-3.34%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|296.7436|290.7721|-5.9716|-2.01%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.2091|31.3403|-0.8688|-2.7%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4052|19.2599|-0.1453|-0.75%|
|migraphx_cadene__dpn92i1|Numerics|regression|42.4594|71.2668|28.8074|67.85%|
|migraphx_cadene__inceptionv4i16|PASS|regression|149.3453|230.8369|81.4916|54.57%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.1818|114.3557|0.1738|0.15%|
|migraphx_cadene__resnext101_64x4di16|Numerics|regression|370.2828|1366.2479|995.965|268.97%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3801|7.4496|0.0695|0.94%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|23.4891|24.5581|1.069|4.55%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.6995|32.8804|-1.8191|-5.24%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|145.8738|144.0104|-1.8635|-1.28%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.0733|14.7629|-1.3105|-8.15%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.0951|6.8096|0.7145|11.72%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.6063|75.318|-1.2883|-1.68%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.6974|39.709|0.0116|0.03%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.2415|98.8669|-1.3745|-1.37%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3212|11.3536|0.0324|0.29%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|193.8748|194.4151|0.5403|0.28%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|38.4031|35.4348|-2.9682|-7.73%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|60.2861|508.2203|447.9342|743.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|82.2096|220.3279|138.1183|168.01%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0464|13.2162|0.1698|1.3%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3409|13.263|-0.0779|-0.58%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.5084|29.45|9.9416|50.96%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6017|12.7517|0.1501|1.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2779|13.2221|-0.0559|-0.42%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.9592|73.7851|51.826|236.01%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.5083|70.8999|-2.6084|-3.55%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|115.763|111.132|-4.631|-4.0%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|165.1401|159.4444|-5.6957|-3.45%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.4657|240.8744|226.4086|1565.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.2864|17.7399|-0.5465|-2.99%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|27.4489|40.3225|12.8736|46.9%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8119|20.2269|-0.5849|-2.81%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.7624|29.7273|-1.0352|-3.37%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|45.0643|72.1944|27.1301|60.2%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_atto_ols.a2_in1k|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|regnety_640.seer|Numerics|PASS|

