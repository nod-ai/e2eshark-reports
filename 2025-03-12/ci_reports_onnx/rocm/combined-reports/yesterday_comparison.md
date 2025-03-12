# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.0087|107.5913|1.5826|1.49%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.4098|107.5838|-0.826|-0.76%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|458.0777|457.1546|-0.9231|-0.2%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.8161|59.3318|0.5157|0.88%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|60.9848|61.56|0.5752|0.94%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|239.5074|241.4508|1.9434|0.81%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|33.8411|35.8544|2.0133|5.95%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.9756|1.6103|-0.3654|-18.49%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9934|19.1379|0.1446|0.76%|
|migraphx_cadene__dpn92i1|PASS|progression|5.4614|5.0561|-0.4053|-7.42%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2953|29.4275|0.1323|0.45%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2561|6.3157|0.0596|0.95%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.7133|30.1034|0.3901|1.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0832|7.0122|-0.071|-1.0%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.3609|27.3169|-0.044|-0.16%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7777|4.9836|0.2059|4.31%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.0056|43.9487|-0.0569|-0.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.7473|46.6868|-0.0605|-0.13%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.1575|18.071|-0.0865|-0.48%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.9532|8.9883|1.0351|13.01%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0167|18.0478|0.0311|0.17%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9063|5.0138|0.1074|2.19%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.1037|28.0516|-0.0521|-0.19%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.56|3.6417|0.0817|2.3%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.8095|20.8488|0.0393|0.19%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.6768|25.6112|-0.0656|-0.26%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.7962|38.3536|0.5574|1.47%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.8045|57.9143|0.1098|0.19%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1578|12.3128|0.1549|1.27%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3511|12.3376|-0.0135|-0.11%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0038|19.0099|0.006|0.03%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.3472|12.4917|0.1446|1.17%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.7221|18.9703|0.2482|1.33%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.503|19.5081|0.0051|0.03%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.1455|36.057|-0.0885|-0.24%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.1299|71.8865|-0.2434|-0.34%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|113.5034|112.8307|-0.6727|-0.59%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|19.1389|28.2794|9.1405|47.76%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.8388|19.905|0.0662|0.33%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.1695|23.3298|0.1603|0.69%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9976|19.9615|-0.0361|-0.18%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.0856|26.3194|0.2339|0.9%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.2494|33.2692|0.0198|0.06%|

## 12 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_rmlp_1_rw2_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|PASS|compilation|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|compilation|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|compilation|

## No Progressions Found

