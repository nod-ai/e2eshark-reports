# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|93.3336|91.7547|-1.5789|-1.69%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.9984|86.5356|-2.4628|-2.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|291.3236|541.6491|250.3255|85.93%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.1494|30.705|-0.4444|-1.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.8279|83.624|-0.204|-0.24%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|246.9072|264.1709|17.2637|6.99%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.4913|40.3178|-3.1735|-7.3%|
|migraphx_bert__bert-large-uncased|PASS|regression|376.454|444.8301|68.3761|18.16%|
|migraphx_cadene__dpn92i1|PASS|regression|165.698|174.9191|9.2211|5.56%|
|migraphx_cadene__inceptionv4i16|PASS|progression|5666.2991|5345.1252|-321.1739|-5.67%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.535|328.6785|5.1434|1.59%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5200.4277|5004.5062|-195.9214|-3.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.5535|398.3325|17.779|4.67%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|481.6418|424.9254|-56.7164|-11.78%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.901|95.7298|-1.1712|-1.21%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|33.3583|31.199|-2.1593|-6.47%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|188.0154|180.9015|-7.1139|-3.78%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.3414|80.3945|1.053|1.33%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|56.7535|64.3721|7.6186|13.42%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1564.0841|1578.332|14.2479|0.91%|
|migraphx_torchvision__inceptioni1|PASS|within tol|196.5311|194.1241|-2.407|-1.22%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5356.6416|5329.4263|-27.2153|-0.51%|
|migraphx_torchvision__resnet50i1|PASS|within tol|88.103|88.2643|0.1613|0.18%|
|migraphx_torchvision__resnet50i64|PASS|regression|5115.083|6081.8676|966.7846|18.9%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2681.0138|2614.7611|-66.2527|-2.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4150.9647|3959.449|-191.5156|-4.61%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5740.9671|5776.5579|35.5908|0.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|158.3407|160.0401|1.6994|1.07%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|262.686|273.9423|11.2562|4.29%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|394.6316|370.0822|-24.5494|-6.22%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|387.8425|390.5834|2.7409|0.71%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|594.5215|586.8237|-7.6979|-1.29%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|806.9501|808.8921|1.942|0.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5099.1888|4929.883|-169.3058|-3.32%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8042.652|8027.867|-14.785|-0.18%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11296.0864|11108.0077|-188.0787|-1.66%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|699.2795|705.1562|5.8767|0.84%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1086.5237|1072.6122|-13.9115|-1.28%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1509.2568|1594.9906|85.7339|5.68%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1271.6509|1344.3944|72.7434|5.72%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2050.4361|2092.3495|41.9134|2.04%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2909.943|3023.8316|113.8886|3.91%|

## No Regressions Found

## No Progressions Found

