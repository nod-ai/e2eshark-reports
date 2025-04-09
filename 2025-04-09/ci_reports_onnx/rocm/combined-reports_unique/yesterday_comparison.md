# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.2618|115.9398|-1.322|-1.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.4542|116.7004|-0.7538|-0.64%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|519.1235|541.232|22.1085|4.26%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.6178|68.5415|-1.0764|-1.55%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.9523|62.4454|-1.5068|-2.36%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|332.0091|328.5723|-3.4368|-1.04%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.1259|34.1807|-0.9452|-2.69%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4296|19.2933|-0.1364|-0.7%|
|migraphx_cadene__dpn92i1|PASS|regression|5.024|5.4325|0.4085|8.13%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.4433|27.3161|-0.1272|-0.46%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.882|5.96|0.078|1.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5254|7.3321|-0.1933|-2.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.9912|30.079|3.0878|11.44%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.777|4.8464|0.0694|1.45%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.5975|38.4077|-2.1898|-5.39%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.9481|45.848|-1.1001|-2.34%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.6097|18.1873|-0.4223|-2.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.9945|9.4108|1.4164|17.72%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.4895|17.2485|-0.2409|-1.38%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.756|4.786|0.0301|0.63%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1664|3.1597|-0.0067|-0.21%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.6334|26.9936|-0.6398|-2.32%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.341|38.3317|-1.0093|-2.57%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.7793|58.5685|-1.2109|-2.03%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.945|12.1925|0.2475|2.07%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4728|12.5247|0.052|0.42%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4206|19.4395|0.0189|0.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5826|12.7061|0.1235|0.98%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5321|19.5607|0.0286|0.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.5364|20.2964|-0.24|-1.17%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.9484|36.8817|-1.0667|-2.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.588|77.7589|-1.8291|-2.3%|
|migx_bench_bert-large-uncased_32_384|PASS|progression|272.7281|119.5519|-153.1762|-56.16%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4808|19.6758|0.1951|1.0%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.0359|20.7921|-0.2438|-1.16%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.6164|24.3419|-0.2745|-1.11%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.1081|20.7825|-0.3255|-1.54%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.268|27.3696|-0.8984|-3.18%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.6605|34.7673|-0.8932|-2.5%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_base_patch16_224_Opset16_timm|Numerics|PASS|
|rain-princess-8|compilation|PASS|
|squeezenet1.0-13-qdq|compilation|PASS|

