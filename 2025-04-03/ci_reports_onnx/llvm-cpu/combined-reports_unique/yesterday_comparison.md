# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|93.9684|86.632|-7.3364|-7.81%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|92.764|99.8272|7.0632|7.61%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|252.3977|252.1671|-0.2306|-0.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7497|31.9732|1.2235|3.98%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|91.318|85.9341|-5.3839|-5.9%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|251.3207|249.2133|-2.1074|-0.84%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|63.3148|41.1307|-22.1842|-35.04%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.7704|369.839|1.0686|0.29%|
|migraphx_cadene__dpn92i1|PASS|progression|196.7094|163.54|-33.1695|-16.86%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6261.0407|6114.5434|-146.4973|-2.34%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|417.9848|316.4234|-101.5614|-24.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|600.3358|407.3703|-192.9656|-32.14%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|447.6904|1990.0463|1542.3559|344.51%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.7543|96.2793|1.525|1.61%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|939.2312|35.6901|-903.5411|-96.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.4386|179.6503|1.2118|0.68%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.9646|64.4247|4.4601|7.44%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|17.4722|20.7979|3.3256|19.03%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1582.2464|1619.8184|37.572|2.37%|
|migraphx_torchvision__inceptioni1|PASS|progression|208.0923|191.9055|-16.1868|-7.78%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.9623|84.1153|-1.847|-2.15%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1460.3615|1469.2087|8.8472|0.61%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|3275.5178|3046.0783|-229.4395|-7.0%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4695.6866|4766.4192|70.7326|1.51%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|161.4012|154.6693|-6.7319|-4.17%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|274.4397|283.1161|8.6764|3.16%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|365.5608|387.3786|21.8178|5.97%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|357.9796|256.0663|-101.9133|-28.47%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|476.0503|438.6156|-37.4346|-7.86%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|665.2509|718.9549|53.7039|8.07%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2788.5094|2809.0156|20.5062|0.74%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5664.446|5901.1465|236.7005|4.18%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9063.2488|8998.0246|-65.2243|-0.72%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|544.8052|421.4353|-123.3699|-22.64%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|799.7359|949.6117|149.8758|18.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1297.1455|1299.5245|2.379|0.18%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|760.8807|775.1829|14.3021|1.88%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1502.2214|1674.6553|172.4339|11.48%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2400.7283|2555.0399|154.3116|6.43%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|switchtransformersencoder_Opset16_transformers|compilation|PASS|
|xcit_nano_12_p16_384_dist_Opset16_timm|Numerics|PASS|

