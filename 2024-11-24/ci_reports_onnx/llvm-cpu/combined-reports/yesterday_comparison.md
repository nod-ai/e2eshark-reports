# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|91.3681|85.3789|-5.9892|-6.56%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|101.0944|95.2549|-5.8395|-5.78%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|291.1345|251.7842|-39.3503|-13.52%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.9644|31.561|0.5966|1.93%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|94.6335|88.824|-5.8094|-6.14%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|261.8163|281.2738|19.4575|7.43%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.5591|42.7679|3.2088|8.11%|
|migraphx_bert__bert-large-uncased|PASS|progression|405.363|371.8883|-33.4747|-8.26%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.6443|82.5882|-4.056|-4.68%|
|migraphx_cadene__dpn92i1|PASS|progression|409.6754|184.6085|-225.067|-54.94%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6807.4223|6769.6225|-37.7997|-0.56%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|328.8083|329.8314|1.0231|0.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|586.2923|404.6856|-181.6067|-30.98%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|455.7345|446.566|-9.1685|-2.01%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|103.7069|99.2952|-4.4117|-4.25%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.3991|32.8038|-1.5953|-4.64%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|227.3899|196.3116|-31.0784|-13.67%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|88.7316|83.5107|-5.2209|-5.88%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|45.763|42.4459|-3.3172|-7.25%|
|migraphx_torchvision__densenet121i32|PASS|progression|1454.3972|1330.6446|-123.7526|-8.51%|
|migraphx_torchvision__inceptioni1|PASS|regression|217.2708|242.3683|25.0975|11.55%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6571.4364|6562.1364|-9.3|-0.14%|
|migraphx_torchvision__resnet50i1|PASS|regression|93.0314|102.6328|9.6014|10.32%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6043.8751|6052.1633|8.2881|0.14%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2800.963|2718.2718|-82.6912|-2.95%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4456.8927|4241.1567|-215.736|-4.84%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5659.9175|5850.6686|190.7511|3.37%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|162.4657|173.0572|10.5915|6.52%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|265.4944|294.8772|29.3828|11.07%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|380.1578|377.7398|-2.418|-0.64%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|382.2558|421.7127|39.457|10.32%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|590.1653|598.7313|8.566|1.45%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|967.6964|805.3156|-162.3809|-16.78%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5089.8199|5091.0538|1.2339|0.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8291.8839|7884.0768|-407.8071|-4.92%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11517.8016|11302.7939|-215.0077|-1.87%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|900.2144|715.121|-185.0933|-20.56%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1139.6666|1158.2945|18.6279|1.63%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|2581.4483|1537.9552|-1043.493|-40.42%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|2598.1307|1296.8385|-1301.2922|-50.09%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2582.9622|2318.5807|-264.3815|-10.24%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3529.0726|2946.3141|-582.7585|-16.51%|

## No Regressions Found

## No Progressions Found

