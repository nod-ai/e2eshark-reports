# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.0699|109.7324|-1.3376|-1.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.2612|111.2296|0.9683|0.88%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|522.1604|515.1525|-7.008|-1.34%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.7825|68.2257|-0.5568|-0.81%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.2971|61.9392|-0.3578|-0.57%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|271.9157|269.1155|-2.8002|-1.03%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.551|36.7564|0.2054|0.56%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2468|19.3509|0.1041|0.54%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5073|3.5295|0.0222|0.63%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.0337|20.2227|0.189|0.94%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.226|4.2149|-0.0111|-0.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1076|7.1143|0.0067|0.09%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.9753|28.2396|1.2643|4.69%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.18|14.0998|-0.0802|-0.57%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.181|44.4544|1.2734|2.95%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|110.6089|109.6613|-0.9476|-0.86%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|21.4814|18.7993|-2.6821|-12.49%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.7698|10.1811|0.4113|4.21%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.1497|14.1268|-0.0229|-0.16%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1018|3.0912|-0.0106|-0.34%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0311|2.0575|0.0264|1.3%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7722|25.8318|0.0596|0.23%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.1959|37.2711|0.0753|0.2%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.9819|55.8462|-0.1357|-0.24%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.542|12.5485|0.0065|0.05%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7|12.7108|0.0108|0.08%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2953|19.4549|0.1596|0.83%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9665|13.007|0.0406|0.31%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2974|19.1547|-0.1426|-0.74%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6662|19.6716|0.0053|0.03%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.6249|35.5487|-0.0762|-0.21%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.4462|68.8975|-0.5487|-0.79%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|110.521|110.0469|-0.4741|-0.43%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5643|19.434|-0.1303|-0.67%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1453|20.2582|0.1128|0.56%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4141|23.3727|-0.0414|-0.18%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2698|20.2844|0.0146|0.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2281|26.2237|-0.0044|-0.02%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.7393|32.6378|-0.1015|-0.31%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|gcvit_small|PASS|Numerics|

## 21 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|U-2-Net_vaiq_int8|compilation|Numerics|
|coatnet_rmlp_1_rw2_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_1_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|Numerics|
|swinv2_base_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_large_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_large_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_tiny_window16_256_Opset16_timm|compilation|PASS|
|swinv2_tiny_window16_256_Opset17_timm|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset17_timm|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset17_timm|compilation|PASS|

