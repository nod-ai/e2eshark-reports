# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|111.3363|97.6794|-13.6568|-12.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|111.4028|143.4788|32.076|28.79%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.8733|498.6834|-23.1899|-4.44%|
|migraphx_ORT__distilgpt2_1|PASS|progression|59.863|53.5052|-6.3578|-10.62%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.2229|61.6097|-2.6132|-4.07%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|271.4076|270.2742|-1.1334|-0.42%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|35.4331|31.1684|-4.2646|-12.04%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.2935|19.5178|-0.7757|-3.82%|
|migraphx_bert__bertsquad-12|PASS|progression|21.0515|7.7931|-13.2585|-62.98%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|159.7881|159.6211|-0.1671|-0.1%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|222.8037|185.4601|-37.3436|-16.76%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.7391|9.7533|2.0142|26.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|44.5565|24.9989|-19.5576|-43.89%|
|migraphx_mlperf__resnet50_v1|Numerics|progression|6.4654|6.0782|-0.3872|-5.99%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|48.2369|116.104|67.8671|140.7%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|55.0135|46.9677|-8.0458|-14.63%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|20.9742|18.1158|-2.8583|-13.63%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|13.358|6.3886|-6.9694|-52.17%|
|migraphx_torchvision__densenet121i32|PASS|regression|73.6844|83.0635|9.3791|12.73%|
|migraphx_torchvision__inceptioni1|PASS|regression|16.9452|21.0498|4.1046|24.22%|
|migraphx_torchvision__inceptioni32|PASS|progression|149.3517|137.0343|-12.3174|-8.25%|
|migraphx_torchvision__resnet50i64|PASS|progression|196.7706|166.2221|-30.5485|-15.52%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|35.6159|33.7214|-1.8945|-5.32%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|61.4829|58.9535|-2.5294|-4.11%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|78.8686|74.951|-3.9176|-4.97%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.6263|13.117|-0.5093|-3.74%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|13.824|13.1306|-0.6934|-5.02%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|20.4582|19.428|-1.0301|-5.04%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4355|12.8732|-0.5624|-4.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9779|13.5163|-0.4616|-3.3%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.1402|21.3609|-0.7794|-3.52%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.9608|70.6411|-3.3198|-4.49%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.7631|107.1181|-4.645|-4.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|156.1963|149.2199|-6.9764|-4.47%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|15.2916|14.4801|-0.8115|-5.31%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|18.4407|36.653|18.2123|98.76%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.8723|26.6558|-1.2165|-4.36%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|21.1697|19.9508|-1.2189|-5.76%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.5211|28.1284|-1.3926|-4.72%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.7941|45.2793|1.4853|3.39%|

## 8 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|efficientnet_b3_pruned.in1k|PASS|compilation|
|gluon_xception65|PASS|compilation|
|model--marian-finetuned-kde4-en-to-fr--amartyobanerjee|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--vmehlin_distilbert-finetuned-squad--vanme|PASS|Numerics|
|tf_efficientnet_b3.aa_in1k|PASS|compilation|
|tf_efficientnet_b3.ap_in1k|PASS|compilation|
|tf_efficientnet_b3.ns_jft_in1k|PASS|compilation|

## 40 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|bat_resnext26ts.ch_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnext_nano_rw_224.sw_in1k|compilation|PASS|
|convnext_atto.d2_in1k|compilation|PASS|
|convnext_atto_ols.a2_in1k|compilation|PASS|
|convnext_femto.d1_in1k|compilation|PASS|
|convnext_femto_ols.d1_in1k|compilation|PASS|
|convnext_nano.d1h_in1k|compilation|PASS|
|convnext_nano.in12k|compilation|PASS|
|convnext_nano.in12k_ft_in1k|compilation|PASS|
|convnext_nano_ols.d1h_in1k|compilation|PASS|
|convnext_pico.d1_in1k|compilation|PASS|
|convnext_pico_ols.d1_in1k|compilation|PASS|
|convnext_tiny_hnf.a2h_in1k|compilation|PASS|
|convnextv2_atto.fcmae|compilation|PASS|
|convnextv2_atto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_femto.fcmae|compilation|PASS|
|convnextv2_femto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae|compilation|PASS|
|convnextv2_nano.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|compilation|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k_384|compilation|PASS|
|convnextv2_pico.fcmae|compilation|PASS|
|convnextv2_pico.fcmae_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|mobilevit_xxs|compilation|PASS|
|mobilevitv2_050|compilation|PASS|
|mobilevitv2_075|compilation|PASS|
|mobilevitv2_100|compilation|PASS|
|mobilevitv2_125|compilation|PASS|
|mobilevitv2_150|compilation|PASS|
|mobilevitv2_150_in22ft1k|compilation|PASS|
|mobilevitv2_175|compilation|PASS|
|mobilevitv2_175_in22ft1k|compilation|PASS|
|mobilevitv2_200|compilation|PASS|
|mobilevitv2_200_in22ft1k|compilation|PASS|
|rexnetr_200.sw_in12k|compilation|PASS|
|vit_base_r50_s16_384.orig_in21k_ft_in1k|compilation|PASS|

