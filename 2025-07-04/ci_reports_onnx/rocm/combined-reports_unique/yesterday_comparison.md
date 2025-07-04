# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.8692|121.9358|0.0666|0.05%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|121.7383|125.5324|3.7942|3.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|536.7106|537.7661|1.0555|0.2%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.7221|68.7667|-0.9553|-1.37%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.0277|66.2558|0.2281|0.35%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.6375|339.8115|-0.826|-0.24%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.5787|34.8631|-0.7156|-2.01%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4107|19.2441|-0.1665|-0.86%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4798|3.6151|0.1353|3.89%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.6348|19.6405|0.0056|0.03%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2438|4.1551|-0.0888|-2.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9779|7.0873|0.1094|1.57%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.9387|26.3917|0.453|1.75%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1096|14.0806|-0.029|-0.21%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.2186|41.4833|-0.7353|-1.74%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.717|104.7007|0.9838|0.95%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|20.989|17.6164|-3.3727|-16.07%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.3046|10.0818|1.7772|21.4%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.6598|13.643|-0.0168|-0.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.087|3.1174|0.0304|0.98%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0249|2.034|0.0091|0.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.4601|25.7004|0.2403|0.94%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|36.8451|37.2159|0.3708|1.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|55.2278|56.6562|1.4284|2.59%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5623|12.5743|0.012|0.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7653|12.787|0.0216|0.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2711|19.3881|0.1169|0.61%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8966|12.9486|0.052|0.4%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1904|19.3691|0.1788|0.93%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8775|19.8283|-0.0493|-0.25%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.4063|34.2984|-1.108|-3.13%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|68.3744|69.6235|1.2491|1.83%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.1266|111.0947|1.968|1.8%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.2585|19.3437|0.0852|0.44%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.953|20.0873|0.1343|0.67%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2052|23.2947|0.0895|0.39%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0995|20.6936|0.5941|2.96%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|27.4514|25.9635|-1.4879|-5.42%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.2155|32.8103|0.5948|1.85%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_base_patch16_384_in21ft1k_Opset16_timm|PASS|Numerics|
|encoderdecoder_Opset17_transformers|PASS|Numerics|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|PASS|Numerics|
|swin_s3_small_224.ms_in1k|PASS|Numerics|
|vit_b_32_Opset16_torch_hub|PASS|Numerics|
|vit_large_patch16_224_in21k_Opset18_timm|PASS|Numerics|

## 10 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|bigbird_Opset17_transformers|Numerics|PASS|
|convbert_Opset16_transformers|Numerics|PASS|
|dpn107_Opset18_timm|Numerics|PASS|
|maxvit_large_tf_384.in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_4_256|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|ssl_resnext101_32x16d_Opset18_timm|Numerics|PASS|
|swin_base_patch4_window7_224_in22k_Opset16_timm|Numerics|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|Numerics|PASS|
|vit_large_patch32_384_Opset16_timm|Numerics|PASS|

