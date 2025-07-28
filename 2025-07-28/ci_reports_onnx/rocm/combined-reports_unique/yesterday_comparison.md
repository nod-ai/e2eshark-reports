# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.7888|112.5328|1.744|1.57%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.8527|111.1975|0.3448|0.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|511.3361|508.4894|-2.8467|-0.56%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.792|67.9671|-0.8249|-1.2%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.2051|62.612|0.4069|0.65%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|269.6178|271.4497|1.832|0.68%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.6721|36.0113|-1.6608|-4.41%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4176|19.2126|-0.205|-1.06%|
|migraphx_cadene__dpn92i1|PASS|regression|3.4809|3.6683|0.1874|5.38%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.0688|20.1174|0.0487|0.24%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|4.5856|4.3001|-0.2854|-6.22%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.1028|7.4991|0.3964|5.58%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|27.7088|26.7848|-0.9239|-3.33%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1289|14.1952|0.0663|0.47%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|46.9013|45.091|-1.8103|-3.86%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|110.8017|114.0075|3.2058|2.89%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.4284|19.6811|1.2527|6.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.3645|9.8617|1.4971|17.9%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.2397|14.2463|0.0066|0.05%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0883|3.0498|-0.0385|-1.25%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.045|2.0729|0.0279|1.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7282|25.8209|0.0927|0.36%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.4454|37.6626|0.2172|0.58%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.9528|56.7779|0.8251|1.47%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5515|12.5635|0.012|0.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6224|12.908|0.2856|2.26%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4274|19.4897|0.0623|0.32%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9717|12.9487|-0.0229|-0.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2794|19.2134|-0.066|-0.34%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6513|19.7632|0.1119|0.57%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.7345|36.1394|0.4048|1.13%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.279|70.2206|0.9416|1.36%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|110.745|112.3743|1.6293|1.47%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4557|19.5873|0.1316|0.68%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2065|20.1386|-0.0679|-0.34%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3269|23.4849|0.158|0.68%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2192|20.3324|0.1133|0.56%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2263|26.2722|0.0459|0.18%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.595|33.0225|0.4275|1.31%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|PASS|compilation|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|compilation|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|compilation|
|vit_srelpos_small_patch16_224_Opset16_timm|PASS|compilation|

## No Progressions Found

