# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|199.5497|200.843|1.2933|0.65%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|195.784|250.2817|54.4977|27.84%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|559.6408|623.7096|64.0688|11.45%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|78.6985|80.2443|1.5457|1.96%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|191.8899|190.0751|-1.8148|-0.95%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|546.2256|638.8274|92.6018|16.95%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|100.1207|162.5123|62.3915|62.32%|
|migraphx_bert__bert-large-uncased|PASS|regression|370.9923|392.2565|21.2642|5.73%|
|migraphx_cadene__dpn92i1|PASS|within tol|180.6562|175.5888|-5.0674|-2.8%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5336.4382|5446.2811|109.843|2.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|328.8302|315.1416|-13.6886|-4.16%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|420.1606|454.1197|33.959|8.08%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|563.8923|524.75|-39.1423|-6.94%|
|migraphx_mlperf__resnet50_v1|PASS|regression|94.5376|106.0373|11.4997|12.16%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|62.7|74.5283|11.8283|18.86%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|212.9795|238.1319|25.1524|11.81%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|65.3549|64.3436|-1.0113|-1.55%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|20.738|18.7677|-1.9703|-9.5%|
|migraphx_torchvision__densenet121i32|PASS|regression|1432.953|1594.9815|162.0285|11.31%|
|migraphx_torchvision__inceptioni1|PASS|regression|202.2308|226.7697|24.5389|12.13%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.386|94.1006|10.7146|12.85%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1548.6553|1696.1598|147.5045|9.52%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|5311.2397|6140.1864|828.9467|15.61%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9707.3202|9781.1656|73.8454|0.76%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|199.3471|146.1726|-53.1745|-26.67%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|290.9419|256.3406|-34.6013|-11.89%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|440.0205|367.3203|-72.7002|-16.52%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|293.166|238.051|-55.115|-18.8%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|424.2699|624.2998|200.0299|47.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|774.7084|756.0361|-18.6724|-2.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5056.6193|5073.3825|16.7631|0.33%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13985.7947|14547.4859|561.6913|4.02%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24014.3654|23356.479|-657.8864|-2.74%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|649.1701|460.7043|-188.4658|-29.03%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|852.5437|874.8393|22.2957|2.62%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1242.1063|1234.3864|-7.7199|-0.62%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1760.0685|789.3919|-970.6766|-55.15%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1643.8856|1721.2937|77.4081|4.71%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3421.7528|3640.0676|218.3148|6.38%|

## No Regressions Found

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|inception-v1-12|compilation|PASS|
|inception-v1-12-qdq|compilation|PASS|
|inception-v1-7|compilation|PASS|
|resnet10t_Opset17_timm|Numerics|PASS|
|resnet14t_Opset18_timm|Numerics|PASS|

