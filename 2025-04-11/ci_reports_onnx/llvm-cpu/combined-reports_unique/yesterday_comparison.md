# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|198.333|196.8534|-1.4796|-0.75%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|219.1964|199.6074|-19.589|-8.94%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|906.8217|812.6561|-94.1656|-10.38%|
|migraphx_ORT__distilgpt2_1|PASS|regression|78.0636|92.9584|14.8948|19.08%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|189.1175|191.2581|2.1407|1.13%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|542.844|661.5367|118.6927|21.86%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|89.4388|101.9138|12.4751|13.95%|
|migraphx_bert__bert-large-uncased|PASS|within tol|374.4301|379.8137|5.3836|1.44%|
|migraphx_cadene__dpn92i1|PASS|within tol|166.3398|163.5116|-2.8282|-1.7%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5510.0282|5497.3955|-12.6327|-0.23%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.3957|317.0837|-6.312|-1.95%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|1181.1437|423.3469|-757.7968|-64.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|470.8776|466.8703|-4.0072|-0.85%|
|migraphx_mlperf__resnet50_v1|PASS|progression|103.5922|97.5261|-6.0661|-5.86%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|57.6426|58.1519|0.5093|0.88%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|993.3223|235.8728|-757.4495|-76.25%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|58.5954|61.8857|3.2903|5.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|21.139|21.3836|0.2446|1.16%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1523.4136|1491.3067|-32.1069|-2.11%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.7223|198.9616|0.2394|0.12%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.6334|83.6203|-0.0132|-0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1567.7768|1559.4576|-8.3192|-0.53%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5488.5402|5377.7884|-110.7519|-2.02%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9680.9487|9708.5894|27.6407|0.29%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.5526|149.7534|-1.7992|-1.19%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|259.7859|283.7824|23.9965|9.24%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|738.5777|360.981|-377.5967|-51.12%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|257.5849|243.5625|-14.0224|-5.44%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|445.7015|453.544|7.8424|1.76%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|656.4262|744.6898|88.2636|13.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5122.6527|4990.6867|-131.966|-2.58%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14155.0114|14416.2138|261.2024|1.85%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|23595.8928|24780.3475|1184.4548|5.02%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|431.8543|438.9796|7.1253|1.65%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|884.6091|839.3946|-45.2145|-5.11%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1238.1712|1268.9544|30.7833|2.49%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|827.2495|756.138|-71.1115|-8.6%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1685.5392|1712.5621|27.0228|1.6%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3406.5113|3467.6612|61.1499|1.8%|

## No Regressions Found

## No Progressions Found

