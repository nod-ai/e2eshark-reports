# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.2805|119.4921|3.2116|2.76%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.2801|116.644|0.3639|0.31%|
|migraphx_ORT__distilgpt2_1|PASS|regression|70.562|74.1677|3.6057|5.11%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|75.1433|74.8445|-0.2988|-0.4%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|300.4348|302.2826|1.8478|0.62%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|43.6517|43.5394|-0.1124|-0.26%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1111|19.0853|-0.0258|-0.14%|
|migraphx_cadene__dpn92i1|PASS|progression|14.9004|13.0079|-1.8925|-12.7%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|22.362|22.0275|-0.3345|-1.5%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.7288|6.4678|-0.261|-3.88%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5379|7.2217|-0.3162|-4.19%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|29.0618|27.0973|-1.9645|-6.76%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.7237|14.7763|0.0526|0.36%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.8449|43.7939|-2.051|-4.47%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|112.3389|110.3253|-2.0136|-1.79%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.4634|20.7749|3.3115|18.96%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.1519|9.2327|-0.9192|-9.05%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.9587|14.8523|-0.1065|-0.71%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.0237|4.0354|0.0118|0.29%|
|migraphx_torchvision__resnet50i1|PASS|progression|3.223|2.1229|-1.1|-34.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8917|25.7703|-0.1214|-0.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.4655|37.4008|-0.0646|-0.17%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.6736|55.3639|-0.3096|-0.56%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6054|12.5002|-0.1053|-0.84%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.1588|12.675|-0.4838|-3.68%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2988|19.241|-0.0577|-0.3%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.003|13.0181|0.015|0.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2088|19.1946|-0.0142|-0.07%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6135|19.5817|-0.0318|-0.16%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.8455|35.6894|-0.1561|-0.44%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|68.6902|69.1593|0.4692|0.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|108.6648|109.9498|1.285|1.18%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|20.2769|19.558|-0.7189|-3.55%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0631|20.1814|0.1183|0.59%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2566|23.2233|-0.0333|-0.14%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1219|20.2669|0.1449|0.72%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2024|26.3161|0.1136|0.43%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.2372|32.5192|0.2819|0.87%|

## No Regressions Found

## 6 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|eva_large_patch14_196.in22k_ft_in1k|Numerics|PASS|
|mixer_b16_224.goog_in21k_ft_in1k|Numerics|PASS|
|model--biobert-base-cased-v1.2-bc2gm-ner--chintagunta85|Numerics|PASS|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|Numerics|PASS|
|vit_large_patch16_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_relpos_medium_patch16_224.sw_in1k|Numerics|PASS|

