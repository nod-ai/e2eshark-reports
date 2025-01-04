# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|91.76|91.9672|0.2072|0.23%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|91.5874|87.1762|-4.4112|-4.82%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|307.7636|541.0773|233.3137|75.81%|
|migraphx_ORT__distilgpt2_1|PASS|progression|32.4162|30.3333|-2.0829|-6.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|93.5309|959.1258|865.5949|925.46%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|275.6515|250.4315|-25.22|-9.15%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.7189|39.8866|0.1677|0.42%|
|migraphx_bert__bert-large-uncased|PASS|within tol|374.4007|371.6078|-2.7929|-0.75%|
|migraphx_cadene__dpn92i1|PASS|within tol|174.4035|171.0548|-3.3487|-1.92%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5313.6184|6087.5121|773.8937|14.56%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|322.8937|323.83|0.9364|0.29%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5191.3361|5111.673|-79.6631|-1.53%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|394.9629|379.6692|-15.2936|-3.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|421.0879|417.6888|-3.3991|-0.81%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|88.6614|90.765|2.1036|2.37%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.2299|31.9087|-1.3211|-3.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.5596|179.7218|-0.8379|-0.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|80.673|81.8773|1.2042|1.49%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|55.1017|38.6591|-16.4426|-29.84%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1620.3383|1571.7705|-48.5678|-3.0%|
|migraphx_torchvision__inceptioni1|PASS|progression|223.5933|194.6044|-28.9889|-12.96%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5326.2075|5307.9437|-18.2639|-0.34%|
|migraphx_torchvision__resnet50i1|PASS|progression|91.1933|84.6763|-6.517|-7.15%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5046.2209|5018.2133|-28.0076|-0.56%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2608.2757|2578.3211|-29.9546|-1.15%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4163.8061|4177.3741|13.5681|0.33%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5818.0453|5781.9092|-36.1361|-0.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|161.0659|157.997|-3.0688|-1.91%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|293.3393|267.6755|-25.6638|-8.75%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|374.479|378.0154|3.5364|0.94%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|391.3239|397.9221|6.5982|1.69%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|580.1326|581.773|1.6404|0.28%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|812.8515|863.6119|50.7604|6.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5102.0631|5077.4302|-24.6329|-0.48%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8111.5947|7882.1856|-229.4091|-2.83%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11092.1829|11402.9321|310.7492|2.8%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|703.6385|722.458|18.8195|2.67%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1079.2303|1107.7837|28.5534|2.65%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1525.3681|1547.69|22.3219|1.46%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1334.4668|1288.2528|-46.214|-3.46%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2058.3183|2137.6659|79.3477|3.85%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2957.1137|2889.9112|-67.2025|-2.27%|

## No Regressions Found

## No Progressions Found

