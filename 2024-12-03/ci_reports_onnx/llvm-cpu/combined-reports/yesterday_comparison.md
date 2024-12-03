# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|91.3785|92.7036|1.3251|1.45%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|101.0774|96.4144|-4.663|-4.61%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|261.2205|262.2843|1.0638|0.41%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.9047|32.8369|0.9322|2.92%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.0307|91.3002|4.2694|4.91%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|263.4971|249.9003|-13.5968|-5.16%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|48.7253|56.407|7.6817|15.77%|
|migraphx_bert__bert-large-uncased|PASS|within tol|386.8243|378.1737|-8.6506|-2.24%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.8538|86.4657|-0.3882|-0.45%|
|migraphx_cadene__dpn92i1|PASS|progression|200.0648|184.2872|-15.7777|-7.89%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7494.0612|6869.9957|-624.0655|-8.33%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|404.8659|332.4776|-72.3883|-17.88%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|388.6776|382.4245|-6.2531|-1.61%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|423.5387|427.2924|3.7537|0.89%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|106.1749|105.0448|-1.1301|-1.06%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.131|32.2832|-1.8479|-5.41%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|185.9762|183.1821|-2.794|-1.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|84.1418|80.4412|-3.7006|-4.4%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|41.6054|39.7|-1.9054|-4.58%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1314.8345|1315.4477|0.6132|0.05%|
|migraphx_torchvision__inceptioni1|PASS|progression|292.7999|236.5522|-56.2477|-19.21%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6607.3015|6657.9597|50.6582|0.77%|
|migraphx_torchvision__resnet50i1|PASS|within tol|91.6088|91.8871|0.2782|0.3%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6060.911|6062.5376|1.6266|0.03%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2502.3809|2636.2585|133.8775|5.35%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3987.3457|4129.4664|142.1207|3.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5821.754|6001.8395|180.0854|3.09%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|165.072|179.9845|14.9125|9.03%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|261.3758|332.5121|71.1363|27.22%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|381.7877|377.8597|-3.928|-1.03%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|377.121|389.9801|12.8591|3.41%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|583.7016|732.6959|148.9944|25.53%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|832.3192|860.5274|28.2082|3.39%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5133.1254|5041.6983|-91.427|-1.78%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8104.116|7946.3034|-157.8126|-1.95%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11552.1363|11352.8778|-199.2584|-1.72%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|729.3572|1151.868|422.5108|57.93%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1100.9176|1160.2764|59.3588|5.39%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1678.47|1559.5715|-118.8985|-7.08%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1345.2374|1309.0689|-36.1684|-2.69%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2096.7915|2756.8392|660.0477|31.48%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3071.039|3217.2869|146.2479|4.76%|

## No Regressions Found

## No Progressions Found

