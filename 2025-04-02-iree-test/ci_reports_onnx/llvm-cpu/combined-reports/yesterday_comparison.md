# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|93.9684|97.6081|3.6397|3.87%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|92.764|89.8265|-2.9375|-3.17%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|252.3977|249.4042|-2.9935|-1.19%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7497|30.6138|-0.1359|-0.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|91.318|87.6817|-3.6363|-3.98%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|251.3207|270.3193|18.9986|7.56%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|63.3148|45.4527|-17.8621|-28.21%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.7704|385.3826|16.6121|4.5%|
|migraphx_cadene__dpn92i1|PASS|progression|196.7094|174.2885|-22.4209|-11.4%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6261.0407|5663.7369|-597.3038|-9.54%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|417.9848|318.1429|-99.8419|-23.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|600.3358|414.1117|-186.2242|-31.02%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|447.6904|1670.546|1222.8556|273.15%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.7543|97.5611|2.8068|2.96%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|939.2312|45.5658|-893.6654|-95.15%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|178.4386|276.1502|97.7116|54.76%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|59.9646|57.71|-2.2546|-3.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|17.4722|21.9283|4.456|25.5%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1582.2464|1597.6272|15.3808|0.97%|
|migraphx_torchvision__inceptioni1|PASS|progression|208.0923|191.212|-16.8803|-8.11%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.9623|85.9882|0.0259|0.03%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1460.3615|1431.8893|-28.4722|-1.95%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|3275.5178|3038.7611|-236.7568|-7.23%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4695.6866|4714.3901|18.7035|0.4%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|161.4012|152.243|-9.1582|-5.67%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|274.4397|280.1404|5.7007|2.08%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|365.5608|366.5184|0.9577|0.26%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|357.9796|242.4401|-115.5395|-32.28%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|476.0503|445.6566|-30.3937|-6.38%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|665.2509|683.9103|18.6594|2.8%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2788.5094|2907.4826|118.9732|4.27%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5664.446|5770.9913|106.5453|1.88%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9063.2488|9402.4699|339.2211|3.74%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|544.8052|416.3671|-128.4381|-23.58%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|799.7359|1108.1081|308.3722|38.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1297.1455|1274.5918|-22.5538|-1.74%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|760.8807|783.5749|22.6942|2.98%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1502.2214|1500.913|-1.3084|-0.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2400.7283|2412.7105|11.9822|0.5%|

## No Regressions Found

## No Progressions Found

