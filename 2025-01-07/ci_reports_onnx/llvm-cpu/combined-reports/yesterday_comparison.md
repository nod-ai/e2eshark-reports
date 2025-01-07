# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|91.9672|88.5288|-3.4384|-3.74%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|87.1762|104.2575|17.0813|19.59%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|541.0773|305.2926|-235.7847|-43.58%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.3333|31.0769|0.7436|2.45%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|959.1258|93.9791|-865.1466|-90.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.4315|246.8237|-3.6079|-1.44%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.8866|40.2615|0.3749|0.94%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.6078|389.766|18.1582|4.89%|
|migraphx_cadene__dpn92i1|PASS|within tol|171.0548|176.0171|4.9623|2.9%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6087.5121|5288.8137|-798.6983|-13.12%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.83|337.467|13.637|4.21%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5111.673|5103.5174|-8.1556|-0.16%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|379.6692|378.8184|-0.8508|-0.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|417.6888|1287.0542|869.3654|208.14%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|90.765|89.4428|-1.3221|-1.46%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.9087|34.6667|2.758|8.64%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.7218|198.0847|18.363|10.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.8773|84.2434|2.3661|2.89%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|38.6591|40.7148|2.0557|5.32%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1571.7705|1610.8466|39.0761|2.49%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.6044|197.3297|2.7252|1.4%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5307.9437|5402.6857|94.742|1.78%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.6763|89.0594|4.3831|5.18%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5018.2133|5103.7119|85.4986|1.7%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2578.3211|2792.067|213.7459|8.29%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4177.3741|4117.6671|-59.707|-1.43%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5781.9092|5809.6243|27.7151|0.48%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|157.997|167.0051|9.0081|5.7%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|267.6755|285.5363|17.8608|6.67%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.0154|373.7518|-4.2636|-1.13%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|397.9221|386.8539|-11.0681|-2.78%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|581.773|578.7387|-3.0342|-0.52%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|863.6119|833.8288|-29.7831|-3.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5077.4302|5037.4221|-40.008|-0.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7882.1856|7938.7413|56.5557|0.72%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11402.9321|11271.6194|-131.3127|-1.15%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|722.458|710.5995|-11.8585|-1.64%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1107.7837|1081.5039|-26.2799|-2.37%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1547.69|1524.8563|-22.8337|-1.48%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1288.2528|1304.3957|16.1429|1.25%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2137.6659|2081.485|-56.1809|-2.63%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2889.9112|2907.1098|17.1986|0.6%|

## No Regressions Found

## No Progressions Found

