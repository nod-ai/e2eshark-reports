# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|92.1952|89.9793|-2.2159|-2.4%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.6093|90.6642|4.0549|4.68%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|298.9161|255.2931|-43.623|-14.59%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|32.3616|33.3788|1.0172|3.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.0606|86.1499|-0.9107|-1.05%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|252.781|254.159|1.3779|0.55%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.5486|40.9683|1.4197|3.59%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.3415|0.9992|-0.3424|-25.52%|
|migraphx_bert__bert-large-uncased|PASS|within tol|366.8345|375.7765|8.942|2.44%|
|migraphx_cadene__dpn92i1|PASS|within tol|162.9489|164.2869|1.338|0.82%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5401.1662|5425.8134|24.6471|0.46%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.4618|315.8763|-14.5855|-4.41%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5032.5549|5041.3193|8.7644|0.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|421.2847|398.1225|-23.1622|-5.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|441.6672|434.8397|-6.8275|-1.55%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.535|96.9498|1.4148|1.48%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.2817|37.7305|4.4488|13.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|216.3624|179.4482|-36.9141|-17.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.6321|70.6601|11.0281|18.49%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|20.1063|24.1545|4.0483|20.13%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1445.1794|1495.6344|50.455|3.49%|
|migraphx_torchvision__inceptioni1|PASS|within tol|204.8921|203.9353|-0.9568|-0.47%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5840.4742|5725.2768|-115.1974|-1.97%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.164|86.1466|1.9825|2.36%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5392.8711|5465.5841|72.713|1.35%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1519.929|1417.8893|-102.0396|-6.71%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|3025.4459|3216.6718|191.226|6.32%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4610.8969|4749.1306|138.2338|3.0%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|152.2672|152.1147|-0.1525|-0.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|254.8041|252.0077|-2.7964|-1.1%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|383.7318|372.6653|-11.0665|-2.88%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|243.6882|243.3304|-0.3579|-0.15%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|447.3532|449.4961|2.1428|0.48%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|702.7478|663.0479|-39.6999|-5.65%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2806.688|2929.0085|122.3205|4.36%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5912.3637|5786.6509|-125.7128|-2.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9434.4129|9157.6528|-276.7601|-2.93%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|425.3968|408.4262|-16.9706|-3.99%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|832.6609|802.3531|-30.3078|-3.64%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1280.2208|1900.2161|619.9953|48.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|745.4395|737.4732|-7.9663|-1.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1527.0518|1518.2427|-8.8091|-0.58%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2433.2004|2634.8574|201.657|8.29%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|

