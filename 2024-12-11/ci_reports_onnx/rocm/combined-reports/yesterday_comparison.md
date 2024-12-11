# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.3448|111.3363|3.9915|3.72%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.4635|111.4028|3.9393|3.67%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|523.9252|521.8733|-2.0519|-0.39%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|57.7844|59.863|2.0786|3.6%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.3544|64.2229|1.8685|3.0%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|265.2503|271.4076|6.1572|2.32%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.9672|35.4331|1.4659|4.32%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.9987|20.2935|0.2947|1.47%|
|migraphx_bert__bertsquad-12|PASS|regression|19.2922|21.0515|1.7593|9.12%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|160.3905|159.7881|-0.6024|-0.38%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|185.9643|222.8037|36.8394|19.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.7956|7.7391|-0.0565|-0.72%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|45.5974|44.5565|-1.0409|-2.28%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.5437|6.4654|-0.0782|-1.2%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|46.448|48.2369|1.7889|3.85%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.9288|55.0135|1.0847|2.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|22.5499|20.9742|-1.5757|-6.99%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|14.1268|13.358|-0.7688|-5.44%|
|migraphx_torchvision__densenet121i32|PASS|within tol|72.6822|73.6844|1.0022|1.38%|
|migraphx_torchvision__inceptioni1|PASS|progression|19.4165|16.9452|-2.4713|-12.73%|
|migraphx_torchvision__inceptioni32|PASS|regression|137.6956|149.3517|11.6561|8.47%|
|migraphx_torchvision__resnet50i64|PASS|regression|167.0906|196.7706|29.68|17.76%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.2854|35.6159|1.3305|3.88%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|60.041|61.4829|1.4418|2.4%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.7915|78.8686|3.0771|4.06%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5504|13.6263|0.0759|0.56%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.7545|13.824|0.0696|0.51%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.803|20.4582|-0.3448|-1.66%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.2767|13.4355|0.1588|1.2%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9192|13.9779|0.0587|0.42%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.898|22.1402|0.2422|1.11%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.4084|73.9608|2.5524|3.57%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.0706|111.7631|3.6925|3.42%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.121|156.1963|6.0753|4.05%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.099|15.2916|0.1926|1.28%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.8281|18.4407|0.6126|3.44%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.1919|27.8723|0.6804|2.5%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6245|21.1697|0.5453|2.64%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.7719|29.5211|0.7492|2.6%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.5034|43.7941|1.2907|3.04%|

## 40 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|bat_resnext26ts.ch_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|coatnext_nano_rw_224.sw_in1k|PASS|compilation|
|convnext_atto.d2_in1k|PASS|compilation|
|convnext_atto_ols.a2_in1k|PASS|compilation|
|convnext_femto.d1_in1k|PASS|compilation|
|convnext_femto_ols.d1_in1k|PASS|compilation|
|convnext_nano.d1h_in1k|PASS|compilation|
|convnext_nano.in12k|PASS|compilation|
|convnext_nano.in12k_ft_in1k|PASS|compilation|
|convnext_nano_ols.d1h_in1k|PASS|compilation|
|convnext_pico.d1_in1k|PASS|compilation|
|convnext_pico_ols.d1_in1k|PASS|compilation|
|convnext_tiny_hnf.a2h_in1k|PASS|compilation|
|convnextv2_atto.fcmae|PASS|compilation|
|convnextv2_atto.fcmae_ft_in1k|PASS|compilation|
|convnextv2_femto.fcmae|PASS|compilation|
|convnextv2_femto.fcmae_ft_in1k|PASS|compilation|
|convnextv2_nano.fcmae|PASS|compilation|
|convnextv2_nano.fcmae_ft_in1k|PASS|compilation|
|convnextv2_nano.fcmae_ft_in22k_in1k|PASS|compilation|
|convnextv2_nano.fcmae_ft_in22k_in1k_384|PASS|compilation|
|convnextv2_pico.fcmae|PASS|compilation|
|convnextv2_pico.fcmae_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|mobilevit_xxs|PASS|compilation|
|mobilevitv2_050|PASS|compilation|
|mobilevitv2_075|PASS|compilation|
|mobilevitv2_100|PASS|compilation|
|mobilevitv2_125|PASS|compilation|
|mobilevitv2_150|PASS|compilation|
|mobilevitv2_150_in22ft1k|PASS|compilation|
|mobilevitv2_175|PASS|compilation|
|mobilevitv2_175_in22ft1k|PASS|compilation|
|mobilevitv2_200|PASS|compilation|
|mobilevitv2_200_in22ft1k|PASS|compilation|
|rexnetr_200.sw_in12k|PASS|compilation|
|vit_base_r50_s16_384.orig_in21k_ft_in1k|PASS|compilation|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|efficientnet_b3_pruned.in1k|compilation|PASS|
|gluon_xception65|compilation|PASS|
|tf_efficientnet_b3.aa_in1k|compilation|PASS|
|tf_efficientnet_b3.ap_in1k|compilation|PASS|
|tf_efficientnet_b3.ns_jft_in1k|compilation|PASS|

