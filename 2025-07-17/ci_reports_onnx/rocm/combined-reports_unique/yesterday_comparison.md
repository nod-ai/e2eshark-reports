# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|122.8057|110.1246|-12.6811|-10.33%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|125.1002|111.5835|-13.5167|-10.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|536.8284|509.4631|-27.3653|-5.1%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.9809|66.5679|-3.4131|-4.88%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|67.0389|62.3773|-4.6616|-6.95%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|341.5466|269.9363|-71.6103|-20.97%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.4746|36.2745|0.7999|2.25%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3827|19.2794|-0.1033|-0.53%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4556|3.5637|0.1081|3.13%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.5902|20.1443|-0.4459|-2.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1896|4.1885|-0.0012|-0.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.1544|11.5772|4.4228|61.82%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.289|26.1284|-0.1606|-0.61%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0347|14.0334|-0.0013|-0.01%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.7016|42.6867|-0.0149|-0.03%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|104.1339|112.5356|8.4017|8.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.944|18.2453|-1.6987|-8.52%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.6147|6.9947|-2.62|-27.25%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.8154|13.853|0.0376|0.27%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1123|3.0459|-0.0664|-2.13%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0608|2.0181|-0.0427|-2.07%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.1235|26.2842|0.1608|0.62%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|40.7009|38.4665|-2.2345|-5.49%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9456|57.2038|-0.7418|-1.28%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5265|12.6865|0.1599|1.28%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8751|12.8638|-0.0113|-0.09%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|37.3737|19.2797|-18.094|-48.41%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.782|12.9678|0.1858|1.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|20.1297|19.2488|-0.8809|-4.38%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8578|19.8564|-0.0014|-0.01%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.3663|37.0367|-0.3296|-0.88%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|135.6144|70.657|-64.9575|-47.9%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|114.65|113.0397|-1.6103|-1.4%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4536|19.1874|-0.2662|-1.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2321|20.159|-0.0731|-0.36%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4336|23.5067|0.0731|0.31%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3615|21.0031|0.6416|3.15%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.6047|26.596|-0.0087|-0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.6473|33.7848|0.1375|0.41%|

## 12 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_384_Opset16_timm|PASS|Numerics|
|coatnet_3_rw_224.sw_in12k|PASS|Numerics|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|maxvit_large_tf_512.in1k|PASS|Numerics|
|regnet_x_16gf_Opset18_torch_hub|PASS|compilation|
|regnetx_160_Opset16_timm|PASS|compilation|
|resnest14d_Opset17_timm|PASS|compilation|
|resnest200e|PASS|compilation|
|resnest200e_Opset17_timm|PASS|compilation|
|resnest26d_Opset17_timm|PASS|compilation|
|resnest50d_Opset17_timm|PASS|compilation|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|PASS|Numerics|

## 38 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnext_nano_rw_224.sw_in1k|compilation|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|dla46x_c_Opset18_timm|Numerics|PASS|
|dla60x_c_Opset17_timm|Numerics|PASS|
|dpn92_Opset17_timm|Numerics|PASS|
|feastconv_Opset17_graph_convolutions|compilation|PASS|
|gpt2doubleheads_Opset16_transformers|compilation|PASS|
|gpt2doubleheads_Opset17_transformers|compilation|PASS|
|hrnet_w44_Opset18_timm|Numerics|PASS|
|maxxvit_rmlp_nano_rw_256.sw_in1k|compilation|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|compilation|PASS|
|maxxvitv2_nano_rw_256.sw_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|PASS|
|model--roberta-base-ca-cased-ner--projecte-aina|Numerics|PASS|
|nf_regnet_b1_Opset16_timm|compilation|Numerics|
|openaigptdoubleheads_Opset16_transformers|compilation|PASS|
|openaigptdoubleheads_Opset17_transformers|compilation|PASS|
|pit_b_224|compilation|PASS|
|pit_b_224_Opset16_timm|compilation|PASS|
|pit_b_224_Opset17_timm|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_b_distilled_224_Opset16_timm|compilation|PASS|
|pit_b_distilled_224_Opset18_timm|compilation|PASS|
|repvgg_b1g4_Opset17_timm|compilation|PASS|
|repvgg_b2g4_Opset16_timm|compilation|Numerics|
|repvgg_b3g4_Opset16_timm|compilation|Numerics|
|res2net50_26w_8s_Opset16_timm|Numerics|PASS|
|resnest50d_4s2x40d_Opset16_timm|compilation|Numerics|
|resnetrs350|Numerics|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|Numerics|PASS|
|vgg19_bn_vaiq|Numerics|PASS|
|vit_base_patch32_224_in21k_Opset17_timm|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch16_384_Opset17_timm|Numerics|PASS|
|xcit_medium_24_p16_384_dist_Opset17_timm|Numerics|PASS|

