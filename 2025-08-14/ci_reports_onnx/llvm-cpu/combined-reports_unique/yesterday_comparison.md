# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|196.4141|200.4168|4.0027|2.04%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|1155.6163|322.8737|-832.7426|-72.06%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|601.0847|569.8044|-31.2803|-5.2%|
|migraphx_ORT__distilgpt2_1|PASS|progression|869.2971|84.6311|-784.666|-90.26%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|189.2694|220.7269|31.4575|16.62%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|555.5934|594.8127|39.2193|7.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|89.0442|102.455|13.4108|15.06%|
|migraphx_bert__bert-large-uncased|PASS|within tol|377.6139|368.3641|-9.2498|-2.45%|
|migraphx_cadene__dpn92i1|PASS|progression|208.4578|165.0387|-43.419|-20.83%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5393.2714|5449.8141|56.5427|1.05%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|314.0393|316.4651|2.4259|0.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|426.5687|433.5702|7.0014|1.64%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|495.6641|448.0608|-47.6033|-9.6%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|98.3768|94.585|-3.7917|-3.85%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|62.4791|62.624|0.1449|0.23%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|238.6565|221.0923|-17.5642|-7.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|67.7521|65.2236|-2.5285|-3.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|21.8949|19.1781|-2.7169|-12.41%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1576.2841|1553.7536|-22.5304|-1.43%|
|migraphx_torchvision__inceptioni1|PASS|within tol|214.1716|224.1622|9.9906|4.66%|
|migraphx_torchvision__resnet50i1|PASS|regression|94.5762|100.7179|6.1417|6.49%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1604.4931|1537.2544|-67.2388|-4.19%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5498.6971|5461.5213|-37.1758|-0.68%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9633.3401|9690.5377|57.1975|0.59%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|152.6721|160.0932|7.4211|4.86%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|269.879|251.8758|-18.0032|-6.67%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|368.5045|360.0536|-8.4509|-2.29%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|243.6301|246.0566|2.4265|1.0%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|453.8752|443.879|-9.9962|-2.2%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|655.5958|774.9699|119.3741|18.21%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5181.7731|5072.219|-109.5541|-2.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13647.9039|13744.1183|96.2144|0.7%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23623.5409|23942.0808|318.5399|1.35%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|455.547|423.9108|-31.6361|-6.94%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|790.9881|902.0544|111.0663|14.04%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1251.8018|1676.5212|424.7194|33.93%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|735.2489|868.1581|132.9092|18.08%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1686.9258|1631.1537|-55.7721|-3.31%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3446.1106|3536.1691|90.0585|2.61%|

## No Regressions Found

## No Progressions Found

