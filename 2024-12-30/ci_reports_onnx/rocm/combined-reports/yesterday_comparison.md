# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.7387|99.643|-0.0956|-0.1%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|100.187|99.6125|-0.5745|-0.57%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|499.6106|502.19|2.5794|0.52%|
|migraphx_ORT__distilgpt2_1|PASS|regression|53.7545|103.5463|49.7918|92.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|61.2683|118.2462|56.9779|93.0%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|791.1572|292.5433|-498.6139|-63.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|48.1604|50.2019|2.0414|4.24%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2686|19.2848|0.0162|0.08%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4487|42.4138|-0.0349|-0.08%|
|migraphx_cadene__inceptionv4i16|PASS|regression|148.4118|244.144|95.7322|64.5%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.448|114.2628|-0.1851|-0.16%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|364.4445|363.9049|-0.5396|-0.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2654|7.611|0.3455|4.76%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|23.5379|24.8711|1.3332|5.66%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.3352|33.6606|0.3253|0.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|142.4815|167.3374|24.8559|17.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.9618|15.9355|-0.0264|-0.17%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.0939|5.7053|-3.3885|-37.26%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.336|75.2678|-0.0682|-0.09%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7386|39.9944|0.2557|0.64%|
|migraphx_torchvision__inceptioni32|PASS|progression|169.91|127.2838|-42.6263|-25.09%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3541|11.3291|-0.025|-0.22%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|189.3546|188.7122|-0.6424|-0.34%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.5198|35.4095|-0.1103|-0.31%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.5625|58.4043|-0.1582|-0.27%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|79.5359|85.322|5.7861|7.27%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0282|13.0792|0.051|0.39%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|18.0292|13.3365|-4.6927|-26.03%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4733|19.4048|-0.0685|-0.35%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6587|12.6166|-0.0421|-0.33%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2371|13.2225|-0.0146|-0.11%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7669|21.6712|-0.0956|-0.44%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|102.1765|70.8529|-31.3236|-30.66%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.4759|111.0345|-0.4415|-0.4%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|632.2253|159.1778|-473.0475|-74.82%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.2996|17.9815|3.6818|25.75%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|29.485|17.699|-11.786|-39.97%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.7553|26.702|-0.0532|-0.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3175|20.2105|-0.107|-0.53%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|45.596|29.7208|-15.8751|-34.82%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|99.9323|43.4407|-56.4916|-56.53%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|levit_192.fb_dist_in1k|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_atto_ols.a2_in1k|Numerics|PASS|

