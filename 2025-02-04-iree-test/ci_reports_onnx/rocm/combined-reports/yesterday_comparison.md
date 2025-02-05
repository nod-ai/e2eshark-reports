# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|104.3115|117.8489|13.5374|12.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.2247|109.5026|4.2779|4.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|473.2369|476.7706|3.5336|0.75%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|57.2271|59.5576|2.3305|4.07%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.2461|63.7424|1.4963|2.4%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|270.5913|271.5731|0.9817|0.36%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.113|34.3663|0.2533|0.74%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9137|19.0305|0.1168|0.62%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|6.9141|7.2988|0.3846|5.56%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.0708|26.3857|0.3149|1.21%|
|migraphx_mlperf__resnet50_v1|PASS|progression|6.3554|4.9565|-1.3989|-22.01%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.733|42.576|-0.1569|-0.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|142.1062|45.2029|-96.9033|-68.19%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.9208|17.3506|-0.5701|-3.18%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.0334|7.0426|-0.9909|-12.33%|
|migraphx_torchvision__inceptioni1|PASS|progression|60.7419|4.855|-55.8869|-92.01%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.1655|33.2819|1.1164|3.47%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.8285|55.562|1.7335|3.22%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|71.466|80.7984|9.3325|13.06%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9782|11.9829|0.0047|0.04%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.487|14.3234|1.8364|14.71%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0597|19.0753|0.0156|0.08%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.956|12.7401|-0.2159|-1.67%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3705|13.2418|-0.1287|-0.96%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|20.6259|34.6924|14.0665|68.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.3516|68.3986|2.047|3.09%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.1086|103.7638|3.6551|3.65%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|140.4156|146.445|6.0294|4.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4571|14.3062|-0.1509|-1.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.4429|16.9197|0.4768|2.9%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|26.3738|144.6119|118.2381|448.32%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.1243|19.5266|0.4023|2.1%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.7159|28.7692|2.0533|7.69%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|40.1221|82.2422|42.1201|104.98%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|lambda_resnet26t|PASS|compilation|
|lambda_resnet50ts|PASS|compilation|
|mobilevitv2_050|PASS|compilation|
|mobilevitv2_075|PASS|compilation|
|mobilevitv2_125|PASS|compilation|
|mobilevitv2_150|PASS|compilation|
|mobilevitv2_150_in22ft1k|PASS|compilation|
|mobilevitv2_175|PASS|compilation|
|mobilevitv2_175_384_in22ft1k|Numerics|compilation|
|mobilevitv2_175_in22ft1k|PASS|compilation|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|Numerics|

## 20 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|focalnet_base_lrf.ms_in1k|Numerics|PASS|
|focalnet_base_srf.ms_in1k|Numerics|PASS|
|focalnet_small_lrf.ms_in1k|Numerics|PASS|
|focalnet_small_srf.ms_in1k|Numerics|PASS|
|focalnet_tiny_lrf.ms_in1k|Numerics|PASS|
|focalnet_tiny_srf.ms_in1k|Numerics|PASS|
|maxvit_large_tf_224.in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|PASS|
|maxvit_tiny_rw_224.sw_in1k|Numerics|PASS|
|migraphx_mlperf__resnet50_v1|Numerics|PASS|
|mobilevitv2_200_384_in22ft1k|Numerics|PASS|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|Numerics|PASS|
|model--qa_tquad_convbert-base-turkish--Izzet|Numerics|PASS|
|model--qa_ytu_convbert-base-turkish--Izzet|Numerics|PASS|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|tf_efficientnet_b0.aa_in1k|Numerics|PASS|
|tf_efficientnet_b0.ap_in1k|Numerics|PASS|
|tf_efficientnet_b0.ns_jft_in1k|Numerics|PASS|

