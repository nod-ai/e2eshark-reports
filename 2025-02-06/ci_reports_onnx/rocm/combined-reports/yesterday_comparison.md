# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|104.3115|105.669|1.3575|1.3%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.2247|107.7257|2.501|2.38%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|473.2369|471.6253|-1.6116|-0.34%|
|migraphx_ORT__distilgpt2_1|PASS|regression|57.2271|60.4139|3.1868|5.57%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.2461|62.8198|0.5738|0.92%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|270.5913|268.9543|-1.637|-0.6%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.113|33.6087|-0.5043|-1.48%|
|migraphx_bert__bert-large-uncased|PASS|regression|18.9137|83.6869|64.7732|342.47%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|6.9141|7.2645|0.3503|5.07%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.0708|52.4484|26.3775|101.18%|
|migraphx_mlperf__resnet50_v1|PASS|progression|6.3554|5.2478|-1.1075|-17.43%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.733|42.5175|-0.2154|-0.5%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|142.1062|46.2091|-95.897|-67.48%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.9208|17.0079|-0.9129|-5.09%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.0334|6.6775|-1.356|-16.88%|
|migraphx_torchvision__inceptioni1|PASS|progression|60.7419|4.9325|-55.8093|-91.88%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.1655|32.4048|0.2393|0.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.8285|54.7525|0.924|1.72%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|71.466|72.178|0.7121|1.0%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9782|11.9332|-0.045|-0.38%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.487|12.2396|-0.2473|-1.98%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0597|19.0465|-0.0132|-0.07%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.956|12.6452|-0.3108|-2.4%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3705|13.235|-0.1356|-1.01%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.6259|20.9051|0.2792|1.35%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.3516|67.5209|1.1693|1.76%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.1086|100.9518|0.8431|0.84%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|140.4156|143.9472|3.5315|2.52%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4571|14.3027|-0.1545|-1.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.4429|16.944|0.5011|3.05%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|26.3738|69.0023|42.6285|161.63%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.1243|19.505|0.3807|1.99%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.7159|26.9964|0.2806|1.05%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.1221|40.4622|0.3401|0.85%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|RDN_pytorch_vaiq_int8|Numerics|compilation|
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

