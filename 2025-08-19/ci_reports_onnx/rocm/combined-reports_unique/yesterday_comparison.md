# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|119.0487|116.6087|-2.44|-2.05%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|118.8979|117.1995|-1.6983|-1.43%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|527.6002|526.6781|-0.922|-0.17%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|79.0924|75.6185|-3.4738|-4.39%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|73.1534|70.0939|-3.0596|-4.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|294.6545|288.2818|-6.3727|-2.16%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|41.941|39.12|-2.821|-6.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5678|19.0736|-0.4941|-2.53%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5344|3.6181|0.0837|2.37%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.3227|20.4186|0.0959|0.47%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2855|4.2034|-0.0822|-1.92%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3409|7.1214|-0.2195|-2.99%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|27.7603|29.4636|1.7034|6.14%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.6845|14.767|0.0825|0.56%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|46.8432|46.9236|0.0803|0.17%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|122.7721|111.0532|-11.7189|-9.55%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.285|20.7288|0.4437|2.19%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.8994|9.5488|-1.3506|-12.39%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.5738|14.1188|-0.4551|-3.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0545|3.0764|0.0219|0.72%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0266|2.041|0.0144|0.71%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.2495|25.7051|-0.5444|-2.07%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.3897|37.3548|-1.0349|-2.7%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.5269|55.6147|-1.9122|-3.32%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6394|12.7167|0.0772|0.61%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.9111|12.7686|-0.1425|-1.1%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3091|19.2408|-0.0682|-0.35%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7998|12.7422|-0.0576|-0.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2961|19.1367|-0.1593|-0.83%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.9863|19.525|-0.4613|-2.31%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.1783|35.7782|-1.4001|-3.77%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.0767|69.3189|-1.7579|-2.47%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|113.6938|109.9513|-3.7425|-3.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6411|19.4676|-0.1735|-0.88%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2885|20.1354|-0.1531|-0.75%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.6309|24.1502|0.5193|2.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.1092|20.2076|-0.9017|-4.27%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.9079|26.1055|-0.8024|-2.98%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.4214|32.5758|-0.8457|-2.53%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|gpt2lmhead_Opset16_transformers|Numerics|PASS|
|model--Jasmine-350M--UBC-NLP|Numerics|PASS|
|model--microsoft_deberta-base_squad--Palak|Numerics|PASS|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|Numerics|PASS|

