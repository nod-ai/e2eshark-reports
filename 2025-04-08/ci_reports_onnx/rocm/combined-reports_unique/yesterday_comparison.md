# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|118.677|117.2618|-1.4152|-1.19%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.2809|117.4542|1.1734|1.01%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|528.8602|519.1235|-9.7368|-1.84%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.5547|69.6178|0.0631|0.09%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.6545|63.9523|0.2977|0.47%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|332.5904|332.0091|-0.5813|-0.17%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1705|35.1259|0.9554|2.8%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4065|19.4296|0.0231|0.12%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.1763|5.024|-0.1523|-2.94%|
|migraphx_cadene__inceptionv4i16|PASS|progression|29.3208|27.4433|-1.8775|-6.4%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.9227|5.882|-0.0406|-0.69%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.1367|7.5254|0.3887|5.45%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.2094|26.9912|-1.2182|-4.32%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7672|4.777|0.0097|0.2%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.9493|40.5975|0.6482|1.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.502|46.9481|-0.5539|-1.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.8134|18.6097|-0.2037|-1.08%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.4516|7.9945|-1.4572|-15.42%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8797|17.4895|-0.3902|-2.18%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9262|4.756|-0.1702|-3.46%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1631|3.1664|0.0033|0.11%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.5952|27.6334|0.0383|0.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.22|39.341|0.1211|0.31%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.3844|59.7793|0.3949|0.67%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.027|11.945|-0.082|-0.68%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7738|12.4728|-0.3011|-2.36%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3913|19.4206|0.0294|0.15%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5508|12.5826|0.0318|0.25%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5648|19.5321|-0.0326|-0.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7131|20.5364|-0.1767|-0.85%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8465|37.9484|0.1019|0.27%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.4977|79.588|0.0903|0.11%|
|migx_bench_bert-large-uncased_32_384|PASS|regression|122.4057|272.7281|150.3223|122.81%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4545|19.4808|0.0263|0.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.0791|21.0359|-0.0432|-0.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.5186|24.6164|0.0978|0.4%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.1079|21.1081|0.0001|0.0%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.3798|28.268|-0.1118|-0.39%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.7907|35.6605|-0.1302|-0.36%|

## 4 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_base_patch16_224_Opset16_timm|PASS|Numerics|
|repvgg_b1g4_Opset17_timm|PASS|compilation|
|repvgg_b2g4_Opset16_timm|PASS|compilation|
|repvgg_b3g4_Opset16_timm|PASS|compilation|

## No Progressions Found

