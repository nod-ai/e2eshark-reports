# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.7499|122.4525|0.7026|0.58%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|122.7348|123.323|0.5882|0.48%|
|migraphx_ORT__bert_large_uncased_1|Numerics|within tol|537.4298|536.9731|-0.4567|-0.08%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.8069|69.459|-0.3479|-0.5%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.193|66.5805|0.3874|0.59%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.0465|340.5566|0.5101|0.15%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2996|34.6983|0.3987|1.16%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4558|19.2787|-0.1771|-0.91%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4771|3.4929|0.0158|0.45%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.6653|19.6767|0.0113|0.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1836|4.1893|0.0057|0.14%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.967|7.0182|0.0512|0.73%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.5511|26.6192|0.0682|0.26%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.051|14.1499|0.0989|0.7%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|42.1544|45.4139|3.2595|7.73%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.4834|103.4624|-0.021|-0.02%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.4926|19.029|1.5364|8.78%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.064|9.0899|1.0259|12.72%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.732|13.695|-0.037|-0.27%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1146|3.1097|-0.0049|-0.16%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0272|2.0099|-0.0173|-0.85%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.5627|25.5441|-0.0186|-0.07%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.3141|37.1479|-0.1662|-0.45%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|55.2299|56.2926|1.0627|1.92%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5624|12.9872|0.4248|3.38%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.0651|12.8529|-0.2122|-1.62%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2756|19.306|0.0303|0.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.0558|12.9023|-0.1535|-1.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4546|19.4719|0.0172|0.09%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.74|19.794|0.0539|0.27%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.6724|35.7599|0.0875|0.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|70.3192|69.7452|-0.5741|-0.82%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.4238|110.6771|1.2533|1.15%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.7593|19.3003|-0.459|-2.32%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0925|20.3073|0.2148|1.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2206|23.3648|0.1441|0.62%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1647|20.2052|0.0405|0.2%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|25.895|26.0697|0.1747|0.67%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.2726|32.5525|0.2799|0.87%|

## 8 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|gcvit_small|PASS|Numerics|
|migraphx_ORT__bert_large_uncased_1|PASS|Numerics|
|model--bert-base-finetuned-nli--Jihyun22|PASS|Numerics|
|model--distilbart-xsum-12-1--sshleifer|PASS|Numerics|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|PASS|Numerics|
|resnetrs270_Opset17_timm|PASS|Numerics|
|xcit_large_24_p8_224_Opset17_timm|PASS|Numerics|

## 14 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|bigbird_Opset17_transformers|Numerics|PASS|
|deit_base_patch16_384_Opset17_timm|Numerics|PASS|
|ernie_Opset16_transformers|Numerics|PASS|
|maxvit_tiny_tf_384.in1k|Numerics|PASS|
|model--Electra-Large-SQUADV2--titanbot|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--mBERT-squad--intanm|Numerics|PASS|
|resnetrs350_Opset17_timm|Numerics|PASS|
|tf_efficientnet_b8.ap_in1k|Numerics|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|wide_resnet101_2_Opset17_torch_hub|Numerics|PASS|

