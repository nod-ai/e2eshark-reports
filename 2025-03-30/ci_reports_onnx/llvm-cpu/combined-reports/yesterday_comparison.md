# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.1189|87.4747|1.3557|1.57%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.0288|85.1584|-0.8704|-1.01%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|567.218|261.3018|-305.9161|-53.93%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.1476|33.1758|3.0282|10.04%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|94.1318|85.9911|-8.1407|-8.65%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|266.925|247.0515|-19.8735|-7.45%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|42.4039|44.9389|2.535|5.98%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.4594|1.2935|-0.1659|-11.37%|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.9226|371.227|-10.6956|-2.8%|
|migraphx_cadene__dpn92i1|PASS|progression|176.6392|163.6903|-12.9489|-7.33%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5377.4308|5416.656|39.2252|0.73%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.1264|327.8873|12.7609|4.05%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5087.3444|5031.0994|-56.2451|-1.11%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|402.6616|407.4029|4.7413|1.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|423.9435|469.8181|45.8746|10.82%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.5552|93.688|-1.8671|-1.95%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.5375|33.0793|-2.4582|-6.92%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|194.901|181.1255|-13.7755|-7.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|63.1035|62.7114|-0.3921|-0.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|19.8476|24.6423|4.7947|24.16%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1501.8313|1474.9533|-26.878|-1.79%|
|migraphx_torchvision__inceptioni1|PASS|progression|217.8638|199.0323|-18.8314|-8.64%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5838.1053|5907.0648|68.9594|1.18%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.2184|83.8224|-0.396|-0.47%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5462.7953|5434.4275|-28.3678|-0.52%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1468.6148|1478.1496|9.5348|0.65%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2926.5655|2998.9621|72.3967|2.47%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4743.2446|4796.066|52.8214|1.11%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|154.1302|164.521|10.3908|6.74%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|281.6143|282.0857|0.4715|0.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.1862|360.917|-11.2692|-3.03%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|255.683|244.7272|-10.9558|-4.28%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|436.7465|430.5295|-6.2171|-1.42%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|821.7461|660.7148|-161.0313|-19.6%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2890.0531|2868.2239|-21.8292|-0.76%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5842.9197|5992.4191|149.4994|2.56%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9071.227|9124.2066|52.9796|0.58%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|410.6696|555.7957|145.1261|35.34%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1157.9541|1076.5299|-81.4241|-7.03%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1667.9548|1273.4959|-394.4589|-23.65%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|744.0262|753.6252|9.599|1.29%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1520.2861|1547.7797|27.4936|1.81%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2347.8785|2468.1897|120.3113|5.12%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_384_dist|Numerics|PASS|

