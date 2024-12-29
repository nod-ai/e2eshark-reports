# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|89.0286|87.3601|-1.6685|-1.87%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|84.6989|86.5697|1.8708|2.21%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|371.017|283.8232|-87.1938|-23.5%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.5088|31.4465|-0.0623|-0.2%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|593.9447|83.7462|-510.1986|-85.9%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|243.4091|250.7931|7.384|3.03%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.4749|41.7647|2.2898|5.8%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.4778|370.8577|-0.6202|-0.17%|
|migraphx_cadene__dpn92i1|PASS|within tol|176.4123|175.393|-1.0193|-0.58%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6427.8697|5526.9511|-900.9186|-14.02%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|321.3879|324.646|3.258|1.01%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5094.6673|5147.9712|53.3039|1.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.8834|374.0734|-5.81|-1.53%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|421.1245|418.6286|-2.496|-0.59%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|88.5886|88.0216|-0.567|-0.64%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.4784|32.0663|0.5879|1.87%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.4375|179.1758|-1.2617|-0.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|94.0069|81.5066|-12.5002|-13.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|52.888|41.9623|-10.9258|-20.66%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1513.8501|1507.6316|-6.2185|-0.41%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.2676|208.6278|0.3602|0.17%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5714.9541|5741.2846|26.3305|0.46%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.4142|87.7254|1.3112|1.52%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5925.0029|5916.5359|-8.467|-0.14%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2577.3894|2635.2374|57.848|2.24%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4020.445|4166.5806|146.1356|3.63%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5784.1793|5892.4938|108.3146|1.87%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|183.6832|150.3619|-33.3213|-18.14%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|258.1265|260.9988|2.8723|1.11%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|390.8887|374.8113|-16.0775|-4.11%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|387.3598|380.9713|-6.3885|-1.65%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|611.8855|595.8973|-15.9882|-2.61%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|808.7103|810.9225|2.2122|0.27%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5076.105|4978.0283|-98.0766|-1.93%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7911.2058|7982.9904|71.7846|0.91%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11357.7932|11366.008|8.2148|0.07%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|714.7674|714.4058|-0.3617|-0.05%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1135.7713|1166.5726|30.8014|2.71%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1513.0009|1534.7671|21.7662|1.44%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1295.1677|1348.023|52.8552|4.08%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2049.0088|2113.101|64.0922|3.13%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2895.1625|3035.8959|140.7334|4.86%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_384_dist|PASS|Numerics|

## No Progressions Found

