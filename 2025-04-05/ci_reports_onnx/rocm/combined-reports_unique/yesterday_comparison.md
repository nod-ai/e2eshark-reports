# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.2449|118.509|1.264|1.08%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|121.744|116.7271|-5.0169|-4.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.2172|523.4958|2.2786|0.44%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.1914|68.7579|-0.4336|-0.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.8082|63.7176|0.9094|1.45%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|327.3533|331.714|4.3607|1.33%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.3015|35.4703|1.1688|3.41%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3646|19.5364|0.1718|0.89%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.1403|5.052|-0.0883|-1.72%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.524|29.3024|-0.2217|-0.75%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.0913|6.3234|0.2321|3.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1724|7.0222|-0.1502|-2.09%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.4873|26.8791|-0.6082|-2.21%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.787|4.8858|0.0988|2.06%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.0734|40.02|-0.0534|-0.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.5686|46.7611|0.1925|0.41%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.5977|19.3678|-0.2298|-1.17%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.8417|9.1377|0.2961|3.35%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8763|17.8358|-0.0405|-0.23%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9036|4.854|-0.0497|-1.01%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1997|3.1597|-0.0401|-1.25%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.0147|27.6045|0.5898|2.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.0808|39.6169|1.5361|4.03%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.0715|59.8041|1.7326|2.98%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1768|12.1061|-0.0708|-0.58%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6671|12.5129|-0.1542|-1.22%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4005|19.5486|0.148|0.76%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8105|12.5314|-0.2791|-2.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5883|19.4651|-0.1232|-0.63%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3184|20.6336|0.3152|1.55%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.7232|38.0864|1.3632|3.71%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.1613|79.913|2.7517|3.57%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.3362|120.2724|1.9362|1.64%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6439|19.5519|-0.092|-0.47%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8453|20.9942|0.1489|0.71%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1636|24.6771|0.5135|2.13%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8497|21.2771|0.4274|2.05%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.4282|28.2766|0.8483|3.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7818|35.6931|0.9113|2.62%|

## No Regressions Found

## No Progressions Found

