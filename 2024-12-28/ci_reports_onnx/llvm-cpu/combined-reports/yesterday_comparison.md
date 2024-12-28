# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.706|89.0286|2.3226|2.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.8195|84.6989|-1.1206|-1.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|253.9362|371.017|117.0808|46.11%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.0815|31.5088|1.4273|4.74%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.4986|593.9447|510.4461|611.32%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|245.369|243.4091|-1.9598|-0.8%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.2478|39.4749|0.2271|0.58%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.6305|371.4778|2.8473|0.77%|
|migraphx_cadene__dpn92i1|PASS|within tol|177.3081|176.4123|-0.8958|-0.51%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5521.26|6427.8697|906.6097|16.42%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|568.528|321.3879|-247.1401|-43.47%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5170.7261|5094.6673|-76.0588|-1.47%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.7214|379.8834|0.162|0.04%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|415.4226|421.1245|5.702|1.37%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|88.6373|88.5886|-0.0487|-0.05%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.2568|31.4784|0.2216|0.71%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|201.6067|180.4375|-21.1692|-10.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|86.3362|94.0069|7.6707|8.88%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|44.0261|52.888|8.8619|20.13%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1533.7311|1513.8501|-19.881|-1.3%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.1552|208.2676|0.1124|0.05%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5820.2699|5714.9541|-105.3158|-1.81%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.76|86.4142|-1.3457|-1.53%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5948.9898|5925.0029|-23.9869|-0.4%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2489.1768|2577.3894|88.2126|3.54%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4102.5185|4020.445|-82.0736|-2.0%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5839.8456|5784.1793|-55.6663|-0.95%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|152.7456|183.6832|30.9376|20.25%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|260.8511|258.1265|-2.7247|-1.04%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|403.2749|390.8887|-12.3862|-3.07%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|400.1148|387.3598|-12.755|-3.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|602.7569|611.8855|9.1286|1.51%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|806.2335|808.7103|2.4768|0.31%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5110.6044|5076.105|-34.4994|-0.68%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7962.2744|7911.2058|-51.0686|-0.64%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11268.8557|11357.7932|88.9375|0.79%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|694.1704|714.7674|20.597|2.97%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1137.2265|1135.7713|-1.4552|-0.13%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1529.1398|1513.0009|-16.1389|-1.06%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1346.1327|1295.1677|-50.965|-3.79%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2088.8535|2049.0088|-39.8448|-1.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2900.3512|2895.1625|-5.1887|-0.18%|

## No Regressions Found

## No Progressions Found

