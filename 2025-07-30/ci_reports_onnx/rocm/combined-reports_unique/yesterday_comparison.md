# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.5328|111.0699|-1.4629|-1.3%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.1975|110.2612|-0.9362|-0.84%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|508.4894|522.1604|13.671|2.69%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.9671|68.7825|0.8154|1.2%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.612|62.2971|-0.3149|-0.5%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|271.4497|271.9157|0.466|0.17%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.0113|36.551|0.5397|1.5%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2126|19.2468|0.0342|0.18%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.6683|3.5073|-0.161|-4.39%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.1174|20.0337|-0.0838|-0.42%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.3001|4.226|-0.0742|-1.72%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.4991|7.1076|-0.3916|-5.22%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.7848|26.9753|0.1905|0.71%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1952|14.18|-0.0152|-0.11%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.091|43.181|-1.91|-4.24%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|114.0075|110.6089|-3.3986|-2.98%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|19.6811|21.4814|1.8003|9.15%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.8617|9.7698|-0.0919|-0.93%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.2463|14.1497|-0.0966|-0.68%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0498|3.1018|0.052|1.7%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0729|2.0311|-0.0418|-2.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8209|25.7722|-0.0487|-0.19%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.6626|37.1959|-0.4667|-1.24%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.7779|55.9819|-0.796|-1.4%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5635|12.542|-0.0214|-0.17%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.908|12.7|-0.208|-1.61%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4897|19.2953|-0.1943|-1.0%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9487|12.9665|0.0177|0.14%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2134|19.2974|0.084|0.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.7632|19.6662|-0.0969|-0.49%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.1394|35.6249|-0.5145|-1.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|70.2206|69.4462|-0.7744|-1.1%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|112.3743|110.521|-1.8533|-1.65%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5873|19.5643|-0.023|-0.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1386|20.1453|0.0067|0.03%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4849|23.4141|-0.0708|-0.3%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3324|20.2698|-0.0627|-0.31%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2722|26.2281|-0.0441|-0.17%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.0225|32.7393|-0.2832|-0.86%|

## No Regressions Found

## 12 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|gcvit_small|Numerics|PASS|
|swinv2_base_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_base_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_small_window16_256_Opset16_timm|compilation|PASS|
|swinv2_small_window16_256_Opset17_timm|compilation|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset16_timm|compilation|PASS|

