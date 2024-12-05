# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|92.7036|89.9553|-2.7483|-2.96%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|96.4144|101.7187|5.3043|5.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|262.2843|258.0722|-4.2121|-1.61%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|32.8369|33.4439|0.607|1.85%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|91.3002|87.7487|-3.5515|-3.89%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.9003|244.4379|-5.4624|-2.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|56.407|39.687|-16.7199|-29.64%|
|migraphx_bert__bert-large-uncased|PASS|within tol|378.1737|389.0389|10.8652|2.87%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.4657|88.7979|2.3322|2.7%|
|migraphx_cadene__dpn92i1|PASS|progression|184.2872|174.9801|-9.3071|-5.05%|
|migraphx_cadene__inceptionv4i16|PASS|regression|6869.9957|7828.9648|958.9691|13.96%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|332.4776|350.9676|18.49|5.56%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|382.4245|387.2265|4.8019|1.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|427.2924|414.3159|-12.9765|-3.04%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|105.0448|106.5427|1.4978|1.43%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.2832|34.7316|2.4484|7.58%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.1821|179.7603|-3.4218|-1.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|80.4412|86.3791|5.9379|7.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|39.7|43.9069|4.2069|10.6%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1315.4477|1310.5764|-4.8713|-0.37%|
|migraphx_torchvision__inceptioni1|PASS|progression|236.5522|223.8032|-12.749|-5.39%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6657.9597|6708.9602|51.0004|0.77%|
|migraphx_torchvision__resnet50i1|PASS|regression|91.8871|104.7142|12.8272|13.96%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6062.5376|6026.0617|-36.4759|-0.6%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2636.2585|2686.1519|49.8935|1.89%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4129.4664|4276.3227|146.8563|3.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6001.8395|5811.6341|-190.2053|-3.17%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|179.9845|156.4234|-23.5611|-13.09%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|332.5121|268.9253|-63.5867|-19.12%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|377.8597|375.3273|-2.5325|-0.67%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|389.9801|386.3643|-3.6158|-0.93%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|732.6959|1500.7312|768.0352|104.82%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|860.5274|811.8544|-48.673|-5.66%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5041.6983|5306.8885|265.1902|5.26%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7946.3034|7914.2638|-32.0396|-0.4%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11352.8778|12104.8066|751.9288|6.62%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1151.868|729.0317|-422.8363|-36.71%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1160.2764|1761.8937|601.6173|51.85%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1559.5715|1672.9186|113.3471|7.27%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1309.0689|1304.0507|-5.0182|-0.38%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2756.8392|3491.82|734.9808|26.66%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3217.2869|2919.7168|-297.5701|-9.25%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|bat_resnext26ts.ch_in1k|compilation|PASS|

