# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|140.5231|122.8057|-17.7175|-12.61%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|131.6439|125.1002|-6.5437|-4.97%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|1742.2668|536.8284|-1205.4384|-69.19%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.7813|69.9809|0.1996|0.29%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.6484|67.0389|0.3906|0.59%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|341.1445|341.5466|0.4021|0.12%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.6445|35.4746|0.8301|2.4%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3619|19.3827|0.0208|0.11%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4758|3.4556|-0.0202|-0.58%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.6587|20.5902|0.9315|4.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1904|4.1896|-0.0008|-0.02%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.982|7.1544|0.1723|2.47%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.9268|26.289|0.3622|1.4%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.2203|14.0347|-0.1856|-1.31%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.5297|42.7016|0.172|0.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.2264|104.1339|0.9075|0.88%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.9342|19.944|2.0098|11.21%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.0408|9.6147|1.5739|19.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.7536|13.8154|0.0618|0.45%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0809|3.1123|0.0314|1.02%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0441|2.0608|0.0166|0.81%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.5381|26.1235|0.5854|2.29%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|36.7688|40.7009|3.9322|10.69%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.5804|57.9456|2.3652|4.26%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6545|12.5265|-0.1279|-1.01%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.0029|12.8751|-0.1278|-0.98%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.2794|37.3737|18.0943|93.85%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9598|12.782|-0.1779|-1.37%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|20.1633|20.1297|-0.0336|-0.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6878|19.8578|0.17|0.86%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|35.576|37.3663|1.7904|5.03%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|68.8411|135.6144|66.7733|97.0%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|109.7393|114.65|4.9107|4.47%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5613|19.4536|-0.1077|-0.55%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0778|20.2321|0.1543|0.77%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.1289|23.4336|0.3047|1.32%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0928|20.3615|0.2687|1.34%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.02|26.6047|0.5847|2.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.2546|33.6473|1.3928|4.32%|

## 12 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge.fb_in22k_ft_in1k|PASS|Numerics|
|dpn92_Opset17_timm|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|PASS|Numerics|
|model--roberta-base-ca-cased-ner--projecte-aina|PASS|Numerics|
|res2net50_26w_8s_Opset16_timm|PASS|Numerics|
|resnetrs350|PASS|Numerics|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|PASS|Numerics|
|vgg19_bn_vaiq|PASS|Numerics|
|vit_base_patch32_224_in21k_Opset17_timm|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch16_384_Opset17_timm|PASS|Numerics|
|xcit_medium_24_p16_384_dist_Opset17_timm|PASS|Numerics|

## 12 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|bert_Opset16_transformers|Numerics|PASS|
|blenderbotsmall_Opset16_transformers|Numerics|PASS|
|cait_s24_384_Opset16_timm|Numerics|PASS|
|model--bart-CaPE-xsum--praf-choub|Numerics|PASS|
|model--distilbart-xsum-12-1--sshleifer|Numerics|PASS|
|model--roberta-med-small_shared-finetuned-bbc_xsum-summarization--mrm8488|Numerics|PASS|
|splinter_Opset18_transformers|Numerics|PASS|
|swin_large_patch4_window12_384_Opset17_timm|Numerics|PASS|
|twins_svt_base_Opset17_timm|Numerics|PASS|
|vgg19_Opset16_torch_hub|Numerics|PASS|
|vit_base_patch16_rpn_224.in1k|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|

