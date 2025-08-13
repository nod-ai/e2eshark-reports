# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|198.1785|196.4141|-1.7643|-0.89%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|229.7131|1155.6163|925.9033|403.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|870.9975|601.0847|-269.9128|-30.99%|
|migraphx_ORT__distilgpt2_1|PASS|regression|86.2689|869.2971|783.0282|907.66%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|222.764|189.2694|-33.4946|-15.04%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|545.9456|555.5934|9.6479|1.77%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|97.4694|89.0442|-8.4252|-8.64%|
|migraphx_bert__bert-large-uncased|PASS|progression|608.5696|377.6139|-230.9557|-37.95%|
|migraphx_cadene__dpn92i1|PASS|regression|176.9603|208.4578|31.4975|17.8%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5384.065|5393.2714|9.2064|0.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|356.0632|314.0393|-42.024|-11.8%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|424.501|426.5687|2.0678|0.49%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|504.0913|495.6641|-8.4272|-1.67%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|97.0975|98.3768|1.2793|1.32%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|60.5098|62.4791|1.9693|3.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|285.6606|238.6565|-47.0041|-16.45%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|68.076|67.7521|-0.3239|-0.48%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|20.1656|21.8949|1.7293|8.58%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1528.7416|1576.2841|47.5424|3.11%|
|migraphx_torchvision__inceptioni1|PASS|within tol|224.8065|214.1716|-10.6349|-4.73%|
|migraphx_torchvision__resnet50i1|PASS|progression|108.1932|94.5762|-13.617|-12.59%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1749.4488|1604.4931|-144.9557|-8.29%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5448.2172|5498.6971|50.48|0.93%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9749.0323|9633.3401|-115.6922|-1.19%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|152.2083|152.6721|0.4637|0.3%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|305.6092|269.879|-35.7302|-11.69%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|440.8253|368.5045|-72.3209|-16.41%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|246.6156|243.6301|-2.9855|-1.21%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|430.9781|453.8752|22.8971|5.31%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|728.1221|655.5958|-72.5263|-9.96%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5217.4438|5181.7731|-35.6707|-0.68%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14053.9814|13647.9039|-406.0775|-2.89%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22783.0191|23623.5409|840.5218|3.69%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|403.8377|455.547|51.7092|12.8%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|781.9456|790.9881|9.0425|1.16%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1233.1389|1251.8018|18.663|1.51%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|806.1525|735.2489|-70.9036|-8.8%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1688.966|1686.9258|-2.0402|-0.12%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3513.6938|3446.1106|-67.5832|-1.92%|

## No Regressions Found

## No Progressions Found

