# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.5255|114.8799|0.3544|0.31%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|114.3224|116.851|2.5287|2.21%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|371.7598|367.7064|-4.0534|-1.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|64.0134|64.9945|0.9811|1.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.5579|72.6419|0.084|0.12%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.8235|276.0634|2.2398|0.82%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3714|39.5441|0.1728|0.44%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.128|20.029|-0.099|-0.49%|
|migraphx_bert__bertsquad-12|PASS|progression|21.7759|19.6251|-2.1509|-9.88%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|151.4621|152.8793|1.4172|0.94%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|213.1833|213.8599|0.6766|0.32%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6246|7.6624|0.0378|0.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|42.6138|41.549|-1.0647|-2.5%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4909|6.5787|0.0878|1.35%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.787|33.2349|1.4478|4.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.7776|53.9223|1.1446|2.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|24.5236|27.1833|2.6597|10.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.8113|18.2108|-1.6004|-8.08%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.6251|50.9606|0.3355|0.66%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9358|15.9105|-0.0254|-0.16%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.9547|138.8278|0.8731|0.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.6456|183.8847|1.2392|0.68%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.1974|33.72|0.5227|1.57%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.3239|58.1637|0.8398|1.47%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.2726|73.6778|0.4053|0.55%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5243|13.6637|0.1394|1.03%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8211|13.9351|0.114|0.82%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9659|20.001|0.0352|0.18%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4956|13.5735|0.0778|0.58%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.1004|14.1946|0.0943|0.67%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5256|21.8064|0.2808|1.3%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.9306|69.6517|0.7211|1.05%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.1563|105.0618|0.9055|0.87%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.2173|145.7997|1.5824|1.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.2479|15.2031|-0.0447|-0.29%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.492|17.6341|0.1421|0.81%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.531|26.8061|0.275|1.04%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0177|20.3098|0.292|1.46%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.7952|28.2334|0.4382|1.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.0898|41.5894|0.4996|1.22%|

## No Regressions Found

## No Progressions Found

