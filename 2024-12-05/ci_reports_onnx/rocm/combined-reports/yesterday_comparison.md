# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.3595|113.2258|-0.1337|-0.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.3021|115.7081|2.406|2.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|366.0371|371.3716|5.3344|1.46%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.032|61.3225|1.2905|2.15%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.3106|74.1073|1.7967|2.48%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|275.249|283.2091|7.9601|2.89%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.0849|39.4479|1.363|3.58%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0712|20.0841|0.0129|0.06%|
|migraphx_bert__bertsquad-12|PASS|progression|18.5795|17.4473|-1.1323|-6.09%|
|migraphx_cadene__inceptionv4i16|PASS|regression|142.3107|159.567|17.2563|12.13%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.5404|223.1858|4.6453|2.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5386|7.6981|0.1596|2.12%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.113|45.0225|0.9095|2.06%|
|migraphx_mlperf__resnet50_v1|PASS|regression|6.0581|6.5557|0.4976|8.21%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.5742|32.6182|1.0439|3.31%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.7387|52.6244|-1.1143|-2.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|22.6239|22.7731|0.1492|0.66%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|12.8122|13.0419|0.2298|1.79%|
|migraphx_torchvision__densenet121i32|PASS|within tol|70.1093|73.481|3.3717|4.81%|
|migraphx_torchvision__inceptioni1|PASS|regression|10.2174|15.9724|5.755|56.33%|
|migraphx_torchvision__inceptioni32|PASS|within tol|148.6838|149.2457|0.5619|0.38%|
|migraphx_torchvision__resnet50i64|PASS|regression|182.6131|196.5968|13.9836|7.66%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.9566|35.7737|0.8171|2.34%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|57.4876|61.4143|3.9267|6.83%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|77.685|78.0441|0.3592|0.46%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.4772|13.5234|0.0462|0.34%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8475|13.7485|-0.099|-0.71%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0771|19.9294|-0.1478|-0.74%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3099|13.4728|0.1629|1.22%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.7728|30.0416|16.2688|118.12%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.2438|22.196|-0.0477|-0.21%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|69.7871|73.7824|3.9953|5.72%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.2762|110.8835|2.6074|2.41%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|155.1891|154.6473|-0.5418|-0.35%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.785|15.1504|0.3654|2.47%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.8057|18.3377|0.532|2.99%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.8443|27.8934|1.0491|3.91%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.386|20.9676|0.5816|2.85%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.5755|29.6247|0.0492|0.17%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.8952|43.9135|1.0182|2.37%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|compiled_inference|PASS|
|model--qa_tquad_convbert-base-turkish--Izzet|compiled_inference|PASS|
|model--qa_ytu_convbert-base-turkish--Izzet|compiled_inference|PASS|

