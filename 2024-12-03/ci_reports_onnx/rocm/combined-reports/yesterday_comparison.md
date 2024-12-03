# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.0589|113.3595|0.3007|0.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.6536|113.3021|-2.3515|-2.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|376.6519|366.0371|-10.6148|-2.82%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.369|60.032|-0.337|-0.56%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.3871|72.3106|-0.0765|-0.11%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.9541|275.249|1.295|0.47%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.8135|38.0849|-0.7286|-1.88%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0744|20.0712|-0.0032|-0.02%|
|migraphx_bert__bertsquad-12|PASS|within tol|17.7149|18.5795|0.8647|4.88%|
|migraphx_cadene__inceptionv4i16|PASS|progression|152.7746|142.3107|-10.4639|-6.85%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|215.0951|218.5404|3.4453|1.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5558|7.5386|-0.0172|-0.23%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|47.1162|44.113|-3.0032|-6.37%|
|migraphx_mlperf__resnet50_v1|PASS|progression|6.4526|6.0581|-0.3945|-6.11%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.3169|31.5742|1.2573|4.15%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.4109|53.7387|0.3278|0.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|20.8011|22.6239|1.8228|8.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|14.4153|12.8122|-1.6032|-11.12%|
|migraphx_torchvision__densenet121i32|PASS|within tol|71.8979|70.1093|-1.7886|-2.49%|
|migraphx_torchvision__inceptioni1|PASS|progression|15.9794|10.2174|-5.762|-36.06%|
|migraphx_torchvision__inceptioni32|PASS|within tol|143.2971|148.6838|5.3867|3.76%|
|migraphx_torchvision__resnet50i64|PASS|within tol|189.2231|182.6131|-6.6099|-3.49%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.5015|34.9566|1.4551|4.34%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.0559|57.4876|-0.5682|-0.98%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|73.3995|77.685|4.2855|5.84%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5126|13.4772|-0.0354|-0.26%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8364|13.8475|0.0111|0.08%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9968|20.0771|0.0803|0.4%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3347|13.3099|-0.0248|-0.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0465|13.7728|-0.2737|-1.95%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7594|22.2438|0.4844|2.23%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.265|69.7871|0.522|0.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.8016|108.2762|3.4746|3.32%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|145.1371|155.1891|10.052|6.93%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1049|14.785|-0.3199|-2.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.4898|17.8057|0.3159|1.81%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.8141|26.8443|0.0302|0.11%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0583|20.386|0.3277|1.63%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|27.9322|29.5755|1.6434|5.88%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.6116|42.8952|1.2837|3.08%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|PASS|compiled_inference|
|model--qa_tquad_convbert-base-turkish--Izzet|PASS|compiled_inference|
|model--qa_ytu_convbert-base-turkish--Izzet|PASS|compiled_inference|

## No Progressions Found

