# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.4707|110.7888|0.3181|0.29%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.0295|110.8527|0.8232|0.75%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|512.8923|511.3361|-1.5561|-0.3%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.9069|68.792|-0.1149|-0.17%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.1541|62.2051|0.051|0.08%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|269.4493|269.6178|0.1685|0.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.1033|37.6721|1.5688|4.35%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1954|19.4176|0.2223|1.16%|
|migraphx_cadene__dpn92i1|PASS|progression|3.6788|3.4809|-0.1979|-5.38%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.3977|20.0688|-0.329|-1.61%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|4.2746|4.5856|0.3109|7.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1248|7.1028|-0.022|-0.31%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.7974|27.7088|0.9113|3.4%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.2388|14.1289|-0.11|-0.77%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|43.4775|46.9013|3.4238|7.87%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|113.5062|110.8017|-2.7045|-2.38%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.9073|18.4284|-1.4789|-7.43%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.3152|8.3645|-0.9507|-10.21%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.5549|14.2397|-0.3152|-2.17%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0582|3.0883|0.03|0.98%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0506|2.045|-0.0056|-0.27%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7124|25.7282|0.0158|0.06%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.4313|37.4454|0.014|0.04%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.223|55.9528|-0.2703|-0.48%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5684|12.5515|-0.0169|-0.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6642|12.6224|-0.0418|-0.33%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2622|19.4274|0.1651|0.86%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.0332|12.9717|-0.0615|-0.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1344|19.2794|0.145|0.76%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.9483|19.6513|-0.297|-1.49%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.907|35.7345|-0.1724|-0.48%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.5553|69.279|-0.2763|-0.4%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|111.0359|110.745|-0.2909|-0.26%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.2146|19.4557|0.2411|1.25%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1284|20.2065|0.0781|0.39%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3372|23.3269|-0.0103|-0.04%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1942|20.2192|0.025|0.12%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2334|26.2263|-0.0071|-0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.7491|32.595|-0.1541|-0.47%|

## 26 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_rmlp_1_rw2_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|PASS|compilation|
|gcvit_small|PASS|Numerics|
|swinv2_base_window12_192_22k_Opset16_timm|PASS|compilation|
|swinv2_base_window12_192_22k_Opset17_timm|PASS|compilation|
|swinv2_base_window12to16_192to256_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_base_window12to16_192to256_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_base_window12to24_192to384_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_base_window12to24_192to384_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_large_window12_192_22k_Opset16_timm|PASS|compilation|
|swinv2_large_window12_192_22k_Opset17_timm|PASS|compilation|
|swinv2_large_window12to16_192to256_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_small_window16_256_Opset16_timm|PASS|compilation|
|swinv2_small_window16_256_Opset17_timm|PASS|compilation|
|swinv2_tiny_window16_256_Opset16_timm|PASS|compilation|
|swinv2_tiny_window16_256_Opset17_timm|PASS|compilation|
|vit_srelpos_medium_patch16_224_Opset16_timm|PASS|compilation|
|vit_srelpos_medium_patch16_224_Opset17_timm|PASS|compilation|
|vit_srelpos_small_patch16_224_Opset17_timm|PASS|compilation|

## No Progressions Found

