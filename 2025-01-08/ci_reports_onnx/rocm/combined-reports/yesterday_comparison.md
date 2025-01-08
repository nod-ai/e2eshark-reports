# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|101.4484|116.6166|15.1681|14.95%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|101.0804|100.3452|-0.7352|-0.73%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|501.1806|606.248|105.0674|20.96%|
|migraphx_ORT__distilgpt2_1|PASS|progression|54.2669|51.4155|-2.8514|-5.25%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1394|61.3485|-1.7909|-2.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|296.1129|293.3281|-2.7848|-0.94%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.7342|31.2204|-1.5138|-4.62%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.24|19.2855|0.0455|0.24%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4469|42.4672|0.0203|0.05%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.2952|148.7871|-0.5081|-0.34%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3818|114.4535|0.0716|0.06%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|369.9719|364.1279|-5.8441|-1.58%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3784|7.3184|-0.0601|-0.81%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.3864|24.4349|0.0485|0.2%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.3327|33.1765|-1.1562|-3.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|172.0769|146.1137|-25.9633|-15.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.8733|15.4091|-0.4642|-2.92%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|5.9096|6.0661|0.1565|2.65%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.4054|75.4634|-0.942|-1.23%|
|migraphx_torchvision__inceptioni1|PASS|progression|47.4254|39.7271|-7.6983|-16.23%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.1275|98.9029|-1.2246|-1.22%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3327|11.3329|0.0001|0.0%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|193.8942|189.122|-4.7722|-2.46%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.5457|35.4241|-1.1216|-3.07%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|60.1779|103.4747|43.2968|71.95%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|81.9546|79.3456|-2.609|-3.18%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|13.0337|62.7278|49.6941|381.27%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.281|13.3227|0.0417|0.31%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|35.7285|19.4263|-16.3022|-45.63%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6216|12.6109|-0.0107|-0.08%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2617|13.2304|-0.0313|-0.24%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.913|21.724|-0.1889|-0.86%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|74.3035|71.0102|-3.2933|-4.43%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|114.9871|111.2463|-3.7408|-3.25%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|203.1121|159.6861|-43.426|-21.38%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5084|14.2643|-0.2442|-1.68%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.1961|17.7479|-0.4481|-2.46%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.3758|27.1191|-0.2567|-0.94%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8351|20.2811|-0.554|-2.66%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.627|29.8099|-0.817|-2.67%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.9452|43.533|-1.4121|-3.14%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|Numerics|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_atto_ols.a2_in1k|Numerics|PASS|
|convnext_femto_ols.d1_in1k|Numerics|PASS|
|crossvit_base_240|Numerics|PASS|
|regnety_640.seer|Numerics|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|Numerics|PASS|

