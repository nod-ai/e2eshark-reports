# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|125.8213|121.8692|-3.9521|-3.14%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|124.6706|121.7383|-2.9323|-2.35%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|542.8825|536.7106|-6.1719|-1.14%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.5253|69.7221|0.1968|0.28%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|67.6149|66.0277|-1.5872|-2.35%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|344.4653|340.6375|-3.8278|-1.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|38.8519|35.5787|-3.2732|-8.42%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5029|19.4107|-0.0923|-0.47%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5416|3.4798|-0.0618|-1.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.0865|19.6348|-0.4517|-2.25%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2178|4.2438|0.026|0.62%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0691|6.9779|-0.0912|-1.29%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.4651|25.9387|0.4736|1.86%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0063|14.1096|0.1033|0.74%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|46.4399|42.2186|-4.2213|-9.09%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|105.8206|103.717|-2.1037|-1.99%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.8393|20.989|0.1498|0.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.6037|8.3046|-1.2991|-13.53%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.7817|13.6598|-0.1219|-0.88%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1616|3.087|-0.0746|-2.36%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0446|2.0249|-0.0197|-0.96%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|26.9873|25.4601|-1.5272|-5.66%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.1846|36.8451|-1.3395|-3.51%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|57.7212|55.2278|-2.4934|-4.32%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5949|12.5623|-0.0326|-0.26%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8956|12.7653|-0.1303|-1.01%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3997|19.2711|-0.1285|-0.66%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9381|12.8966|-0.0415|-0.32%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3636|19.1904|-0.1732|-0.89%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.9243|19.8775|-0.0468|-0.23%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.1543|35.4063|-1.7479|-4.7%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.7507|68.3744|-3.3763|-4.71%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|113.3468|109.1266|-4.2202|-3.72%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|31.6204|19.2585|-12.3619|-39.09%|
|migx_bench_bert-large-uncased_4_256|Numerics|within tol|20.328|19.953|-0.375|-1.84%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.7885|23.2052|-0.5833|-2.45%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.5039|20.0995|-0.4044|-1.97%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.6969|27.4514|0.7545|2.83%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.6673|32.2155|-1.4518|-4.31%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|bigbird_Opset17_transformers|PASS|Numerics|
|convbert_Opset16_transformers|PASS|Numerics|
|deit3_large_patch16_224_Opset18_timm|PASS|Numerics|
|dpn107_Opset18_timm|PASS|Numerics|
|maxvit_large_tf_384.in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_4_256|PASS|Numerics|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|PASS|Numerics|
|ssl_resnext101_32x16d_Opset18_timm|PASS|Numerics|
|swin_base_patch4_window7_224_in22k_Opset16_timm|PASS|Numerics|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|PASS|Numerics|
|vit_large_patch32_384_Opset16_timm|PASS|Numerics|

## 6 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-ner--dbsamu|Numerics|PASS|
|model--gpt2-alpaca-gpt4--vicgalle|Numerics|PASS|
|model--pegasus-large-booksum--cnicu|Numerics|PASS|
|vgg13_Opset18_torch_hub|Numerics|PASS|
|vit_large_patch16_384_Opset16_timm|Numerics|PASS|

