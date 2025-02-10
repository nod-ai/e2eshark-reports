# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.2505|100.6|1.3495|1.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|92.1827|85.5152|-6.6675|-7.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|253.4134|255.7613|2.3479|0.93%|
|migraphx_ORT__distilgpt2_1|PASS|regression|32.1137|34.7577|2.644|8.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|793.7538|95.6288|-698.125|-87.95%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|458.12|256.1606|-201.9594|-44.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|41.6994|39.5567|-2.1426|-5.14%|
|migraphx_bert__bert-large-uncased|PASS|regression|369.5454|622.3634|252.818|68.41%|
|migraphx_cadene__dpn92i1|PASS|regression|164.1962|175.8097|11.6135|7.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5573.3526|5533.3048|-40.0478|-0.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|347.415|315.8371|-31.5779|-9.09%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5723.4888|5960.7187|237.2299|4.14%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.355|374.3014|-6.0536|-1.59%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|813.8067|418.6483|-395.1584|-48.56%|
|migraphx_mlperf__resnet50_v1|PASS|regression|99.0715|305.2791|206.2076|208.14%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.0883|32.8668|-0.2215|-0.67%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.4806|183.8216|4.341|2.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|83.6619|82.865|-0.7969|-0.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.4243|45.0617|0.6373|1.43%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1475.8679|1486.4277|10.5598|0.72%|
|migraphx_torchvision__inceptioni1|PASS|within tol|205.5093|207.2307|1.7214|0.84%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5820.7935|5823.7291|2.9356|0.05%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.4208|86.0518|-0.369|-0.43%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5329.1854|5513.1507|183.9653|3.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2750.2393|2624.4753|-125.7639|-4.57%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4223.3939|4218.6725|-4.7214|-0.11%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5716.8672|5649.0951|-67.7721|-1.19%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|157.4994|163.9152|6.4158|4.07%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|277.5263|282.3755|4.8492|1.75%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|390.844|369.5251|-21.3189|-5.45%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|392.5664|417.2535|24.6871|6.29%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|584.1115|578.7403|-5.3712|-0.92%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.1511|810.2086|0.0576|0.01%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5397.8693|5752.0361|354.1668|6.56%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8131.5695|7876.0438|-255.5257|-3.14%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11252.257|11519.1179|266.8609|2.37%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|715.7722|1081.1374|365.3652|51.04%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1094.0522|1212.111|118.0588|10.79%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1626.331|1721.9153|95.5844|5.88%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1313.3499|2631.4614|1318.1115|100.36%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2102.22|2108.4654|6.2454|0.3%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2970.9374|2963.7493|-7.188|-0.24%|

## No Regressions Found

## No Progressions Found

