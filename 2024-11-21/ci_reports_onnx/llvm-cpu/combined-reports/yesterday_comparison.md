# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|89.2728|90.2489|0.9761|1.09%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|95.5742|91.0516|-4.5226|-4.73%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|261.2976|283.1231|21.8255|8.35%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|32.318|30.8056|-1.5123|-4.68%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|96.4069|84.0385|-12.3685|-12.83%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|252.708|253.53|0.822|0.33%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|42.8089|58.0826|15.2738|35.68%|
|migraphx_bert__bert-large-uncased|PASS|within tol|385.0398|384.3665|-0.6733|-0.17%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.9863|90.2893|3.3029|3.8%|
|migraphx_cadene__dpn92i1|PASS|within tol|177.0831|179.5863|2.5032|1.41%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6768.0777|6798.9804|30.9027|0.46%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|328.2752|335.8106|7.5354|2.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|412.386|447.327|34.941|8.47%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|496.5831|484.5267|-12.0564|-2.43%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.3379|100.0333|0.6953|0.7%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.832|34.6198|-3.2121|-8.49%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|188.7855|182.9482|-5.8373|-3.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|88.1692|73.7519|-14.4173|-16.35%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|41.6763|40.59|-1.0863|-2.61%|
|migraphx_torchvision__densenet121i32|PASS|progression|1406.1937|1326.3217|-79.872|-5.68%|
|migraphx_torchvision__inceptioni1|PASS|regression|219.8629|236.1918|16.3289|7.43%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6633.6207|6608.9371|-24.6836|-0.37%|
|migraphx_torchvision__resnet50i1|PASS|progression|96.5473|91.338|-5.2093|-5.4%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6143.9335|6100.3103|-43.6232|-0.71%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2506.1017|2559.2035|53.1018|2.12%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4177.947|4056.5432|-121.4038|-2.91%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5945.1986|6011.2467|66.0481|1.11%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|170.7411|169.0536|-1.6875|-0.99%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|348.2105|274.272|-73.9385|-21.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|403.6409|394.738|-8.9029|-2.21%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|511.3066|395.0193|-116.2873|-22.74%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|626.1882|649.3725|23.1843|3.7%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|825.8407|978.333|152.4924|18.47%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5834.4772|5242.6663|-591.8109|-10.14%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8332.3192|8985.55|653.2308|7.84%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|12572.4161|12320.3268|-252.0893|-2.01%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|772.197|737.4806|-34.7164|-4.5%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1217.1607|1198.6713|-18.4894|-1.52%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1734.514|1770.8802|36.3661|2.1%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1495.3134|1779.0932|283.7798|18.98%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2401.7946|2325.7349|-76.0597|-3.17%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3223.6001|3034.2025|-189.3976|-5.88%|

## No Regressions Found

## No Progressions Found

