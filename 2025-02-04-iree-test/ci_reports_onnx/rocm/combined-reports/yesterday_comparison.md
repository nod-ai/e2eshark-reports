# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|104.3115|107.6051|3.2936|3.16%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.2247|108.4293|3.2045|3.05%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|473.2369|471.4913|-1.7456|-0.37%|
|migraphx_ORT__distilgpt2_1|PASS|regression|57.2271|60.1463|2.9192|5.1%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.2461|65.2843|3.0383|4.88%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|270.5913|402.6628|132.0714|48.81%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.113|35.81|1.697|4.97%|
|migraphx_bert__bert-large-uncased|PASS|regression|18.9137|24.1921|5.2784|27.91%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9141|7.2472|0.3331|4.82%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.0708|26.1964|0.1256|0.48%|
|migraphx_mlperf__resnet50_v1|PASS|progression|6.3554|4.747|-1.6084|-25.31%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.733|44.8631|2.1301|4.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|142.1062|51.1873|-90.9188|-63.98%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.9208|16.9614|-0.9593|-5.35%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.0334|7.0116|-1.0219|-12.72%|
|migraphx_torchvision__inceptioni1|PASS|progression|60.7419|4.8517|-55.8901|-92.01%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|32.1655|33.8013|1.6358|5.09%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|53.8285|59.5387|5.7102|10.61%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|71.466|169.4166|97.9506|137.06%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|11.9782|21.9022|9.924|82.85%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.487|12.3465|-0.1405|-1.12%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0597|19.1685|0.1088|0.57%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.956|12.6609|-0.2952|-2.28%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3705|13.2409|-0.1296|-0.97%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.6259|21.1536|0.5277|2.56%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|66.3516|69.7635|3.4119|5.14%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.1086|104.9528|4.8442|4.84%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|140.4156|145.7989|5.3833|3.83%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4571|14.3177|-0.1395|-0.96%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.4429|17.5223|1.0794|6.56%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|26.3738|75.6279|49.2541|186.75%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.1243|20.5393|1.415|7.4%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.7159|28.7278|2.012|7.53%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|40.1221|52.5428|12.4207|30.96%|

## 10 Regressions Found:

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

