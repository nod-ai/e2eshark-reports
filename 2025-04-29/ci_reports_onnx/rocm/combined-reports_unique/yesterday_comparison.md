# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|154.4606|117.0098|-37.4508|-24.25%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.002|115.7228|-0.2792|-0.24%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|523.6869|524.3276|0.6407|0.12%|
|migraphx_ORT__distilgpt2_1|PASS|regression|68.3499|73.7563|5.4064|7.91%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|74.5586|62.1017|-12.4569|-16.71%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|296.7889|297.0059|0.217|0.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1373|33.7643|-0.373|-1.09%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.2261|26.1077|6.8817|35.79%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.7192|3.7091|-0.0101|-0.27%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.0259|27.222|0.1961|0.73%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.3717|4.3636|-0.0081|-0.18%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.213|6.8423|-0.3707|-5.14%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.0376|26.8523|-0.1854|-0.69%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9234|14.1254|0.202|1.45%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.6717|40.7857|1.1141|2.81%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|125.2476|123.887|-1.3607|-1.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.6688|18.3347|-1.3341|-6.78%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.8334|8.9936|2.1602|31.61%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.6542|17.559|-0.0951|-0.54%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.3522|4.3209|-0.0313|-0.72%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.133|3.1337|0.0007|0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|52.4505|26.8969|-25.5536|-48.72%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.9442|39.3037|0.3595|0.92%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.7998|57.8757|0.0759|0.13%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2621|12.242|-0.0201|-0.16%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5849|12.4993|-0.0856|-0.68%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.231|19.2835|0.0525|0.27%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|28.5024|12.5455|-15.9569|-55.98%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4064|19.2344|-0.172|-0.89%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.9382|20.0202|0.082|0.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.5972|37.5816|-0.0156|-0.04%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|73.3054|67.9162|-5.3893|-7.35%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|109.9883|113.1303|3.142|2.86%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4131|19.3411|-0.072|-0.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.4953|20.3029|-0.1923|-0.94%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0852|23.9677|-0.1175|-0.49%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.804|20.5281|-0.2759|-1.33%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.4935|27.3477|-0.1458|-0.53%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.3388|34.4338|0.0951|0.28%|

## 12 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset17_transformers|PASS|Numerics|
|edgenext_x_small|PASS|compilation|
|longt5_Opset17_transformers|PASS|Numerics|
|model--EstBERT128_sentiment--tartuNLP|PASS|Numerics|
|model--Translation--shed-e|PASS|Numerics|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|PASS|Numerics|
|prophetnet_Opset18_transformers|PASS|Numerics|
|repvgg_b3_Opset17_timm|PASS|Numerics|
|robertaprelayernorm_Opset16_transformers|PASS|Numerics|
|vgg16-7|PASS|Numerics|
|vit_l_16_Opset16_torch_hub|PASS|Numerics|
|yoso_Opset16_transformers|PASS|Numerics|

## 21 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large.fb_in1k|Numerics|PASS|
|cs3edgenet_x_Opset18_timm|Numerics|PASS|
|dm_nfnet_f3.dm_in1k|Numerics|PASS|
|dpn92_Opset17_timm|Numerics|PASS|
|longt5encoder_Opset16_transformers|Numerics|PASS|
|maxvit_large_tf_224.in1k|Numerics|PASS|
|model--bert-finetuned-squad--Aaroosh|Numerics|PASS|
|nystromformer_Opset18_transformers|Numerics|PASS|
|openaigptlmhead_Opset17_transformers|Numerics|PASS|
|poolformer_m48_Opset18_timm|Numerics|PASS|
|rcnn-ilsvrc13-7|Numerics|PASS|
|resnet51q_Opset17_timm|Numerics|PASS|
|resnetv2_152x2_bitm_Opset16_timm|Numerics|PASS|
|switchtransformersencoder_Opset16_transformers|compilation|PASS|
|vit_b_16_Opset16_torch_hub|Numerics|PASS|
|vit_base_patch16_224_miil_Opset16_timm|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_relpos_base_patch16_clsgap_224_Opset17_timm|Numerics|PASS|
|xcit_medium_24_p8_224_Opset16_timm|Numerics|PASS|
|xcit_medium_24_p8_384_dist_Opset16_timm|Numerics|PASS|
|xcit_small_24_p8_384_dist_Opset16_timm|Numerics|PASS|

