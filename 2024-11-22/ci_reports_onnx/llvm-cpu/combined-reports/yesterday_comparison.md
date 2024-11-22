# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.2489|90.3449|0.096|0.11%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|91.0516|86.8042|-4.2474|-4.66%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|283.1231|280.7138|-2.4092|-0.85%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.8056|33.9991|3.1934|10.37%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.0385|86.2848|2.2464|2.67%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|253.53|265.0549|11.525|4.55%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|58.0826|41.2926|-16.79|-28.91%|
|migraphx_bert__bert-large-uncased|PASS|within tol|384.3665|398.202|13.8355|3.6%|
|migraphx_bert__bertsquad-12|PASS|within tol|90.2893|86.8644|-3.4249|-3.79%|
|migraphx_cadene__dpn92i1|PASS|regression|179.5863|363.4492|183.8629|102.38%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6798.9804|6851.1933|52.2129|0.77%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|335.8106|316.3572|-19.4534|-5.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|447.327|424.9328|-22.3942|-5.01%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|484.5267|445.3302|-39.1965|-8.09%|
|migraphx_mlperf__resnet50_v1|PASS|regression|100.0333|111.3024|11.2691|11.27%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|34.6198|38.1558|3.536|10.21%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|182.9482|201.4482|18.5|10.11%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|73.7519|96.6838|22.932|31.09%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.59|46.1934|5.6034|13.8%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1326.3217|1312.1755|-14.1462|-1.07%|
|migraphx_torchvision__inceptioni1|PASS|within tol|236.1918|229.9945|-6.1973|-2.62%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6608.9371|6582.8115|-26.1256|-0.4%|
|migraphx_torchvision__resnet50i1|PASS|within tol|91.338|92.8842|1.5463|1.69%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6100.3103|6218.3269|118.0166|1.93%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2559.2035|2815.1919|255.9884|10.0%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4056.5432|4593.8239|537.2807|13.24%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6011.2467|5820.1679|-191.0788|-3.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|169.0536|167.3264|-1.7272|-1.02%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|274.272|259.6628|-14.6092|-5.33%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|394.738|403.5369|8.7989|2.23%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|395.0193|428.0262|33.007|8.36%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|649.3725|690.8333|41.4609|6.38%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|978.333|907.619|-70.714|-7.23%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5242.6663|5323.1451|80.4789|1.54%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8985.55|8096.2312|-889.3188|-9.9%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12320.3268|11143.7281|-1176.5988|-9.55%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|737.4806|788.5566|51.0761|6.93%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1198.6713|1229.2148|30.5435|2.55%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1770.8802|1824.5955|53.7153|3.03%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1779.0932|1349.8454|-429.2478|-24.13%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2325.7349|2145.8108|-179.9241|-7.74%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3034.2025|3020.5815|-13.621|-0.45%|

## 8 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|pytorch-3dunet_vaiq_int8|PASS|Numerics|
|resmlp_12_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_12_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|PASS|compilation|

## No Progressions Found

