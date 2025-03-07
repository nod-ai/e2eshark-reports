# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|90.1856|103.2997|13.1141|14.54%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|84.9361|88.5885|3.6524|4.3%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|253.31|437.8921|184.5822|72.87%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.1427|36.273|6.1302|20.34%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|102.1145|85.515|-16.5994|-16.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|260.3314|262.8737|2.5423|0.98%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.0253|41.4548|1.4295|3.57%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.3832|1.1335|-0.2496|-18.05%|
|migraphx_bert__bert-large-uncased|PASS|within tol|373.994|385.0846|11.0907|2.97%|
|migraphx_cadene__dpn92i1|PASS|progression|189.7961|168.6049|-21.1911|-11.17%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5671.2524|5512.2636|-158.9888|-2.8%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|321.1199|319.1209|-1.999|-0.62%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5072.3284|5019.0306|-53.2979|-1.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|405.6158|408.8359|3.2201|0.79%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|471.574|424.3165|-47.2575|-10.02%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.1596|95.6426|0.483|0.51%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.9992|30.9707|-4.0286|-11.51%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.0843|179.6917|0.6074|0.34%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|90.1732|88.8424|-1.3308|-1.48%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.2759|44.1178|3.8419|9.54%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1482.2269|1493.5831|11.3563|0.77%|
|migraphx_torchvision__inceptioni1|PASS|progression|212.4865|200.0485|-12.438|-5.85%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5805.5929|5766.6281|-38.9648|-0.67%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.5969|90.8226|7.2257|8.64%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5312.9507|5428.3199|115.3692|2.17%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2684.0088|2650.3482|-33.6606|-1.25%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4274.6135|4087.5658|-187.0477|-4.38%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5898.8534|5843.0735|-55.7799|-0.95%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|181.9144|168.0857|-13.8286|-7.6%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|270.376|268.3661|-2.0099|-0.74%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|391.4844|379.1812|-12.3032|-3.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|386.7687|382.5437|-4.225|-1.09%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|620.735|582.2661|-38.469|-6.2%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|824.3037|820.371|-3.9327|-0.48%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5332.2296|5081.4056|-250.824|-4.7%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8009.4005|8551.9135|542.5129|6.77%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11036.6395|11253.5777|216.9382|1.97%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|758.1494|744.6127|-13.5367|-1.79%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1087.8522|1101.108|13.2557|1.22%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1581.2082|1564.2564|-16.9518|-1.07%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1340.8765|1305.01|-35.8665|-2.67%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2074.1152|2099.0933|24.9781|1.2%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2905.0536|3088.0083|182.9547|6.3%|

## No Regressions Found

## No Progressions Found

