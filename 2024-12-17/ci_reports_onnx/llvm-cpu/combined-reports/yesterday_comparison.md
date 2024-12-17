# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|87.5157|97.5123|9.9966|11.42%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|85.0333|111.0636|26.0303|30.61%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|258.0792|311.9866|53.9074|20.89%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7278|31.0586|0.3308|1.08%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|88.9658|85.5953|-3.3705|-3.79%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|248.6222|253.7612|5.139|2.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|52.3164|39.1763|-13.1401|-25.12%|
|migraphx_bert__bert-large-uncased|PASS|regression|375.3887|915.7402|540.3514|143.94%|
|migraphx_bert__bertsquad-12|PASS|regression|89.3944|149.4601|60.0656|67.19%|
|migraphx_cadene__dpn92i1|PASS|within tol|175.2435|178.612|3.3685|1.92%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5794.5377|5896.2644|101.7267|1.76%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|337.6519|325.2238|-12.4281|-3.68%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5474.2719|5178.9491|-295.3228|-5.39%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|380.7048|430.3492|49.6444|13.04%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|433.5501|576.2465|142.6964|32.91%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|90.8172|89.3371|-1.48|-1.63%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.6425|32.1121|-0.5304|-1.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|278.0565|181.4787|-96.5778|-34.73%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|83.3182|100.2215|16.9033|20.29%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|46.9026|57.0627|10.1601|21.66%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1624.4999|1655.065|30.5651|1.88%|
|migraphx_torchvision__inceptioni1|PASS|within tol|203.0027|201.3802|-1.6225|-0.8%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5926.675|5844.9753|-81.6997|-1.38%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.126|86.2895|-0.8365|-0.96%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5970.224|5886.5782|-83.6458|-1.4%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2518.0225|2497.9823|-20.0402|-0.8%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4173.4586|4165.8412|-7.6174|-0.18%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5724.1341|5687.7121|-36.422|-0.64%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|161.467|156.292|-5.175|-3.2%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|289.7519|265.4975|-24.2544|-8.37%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|373.8116|421.4732|47.6616|12.75%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|429.3175|382.9409|-46.3766|-10.8%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|633.9986|587.8745|-46.1242|-7.28%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|800.8108|804.2592|3.4484|0.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5109.2564|5117.9919|8.7355|0.17%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8099.4264|8145.2506|45.8242|0.57%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11364.87|11434.7609|69.8909|0.61%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|701.7126|716.5291|14.8165|2.11%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1075.3553|1104.5579|29.2026|2.72%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1516.4968|1517.9009|1.4041|0.09%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1475.9714|1299.2821|-176.6893|-11.97%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2277.293|2352.8348|75.5418|3.32%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2835.9332|2929.231|93.2978|3.29%|

## No Regressions Found

## No Progressions Found

