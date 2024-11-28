# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.4505|111.3148|-2.1357|-1.88%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.8076|115.6462|-0.1615|-0.14%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|367.2797|369.5719|2.2922|0.62%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|65.742|65.0916|-0.6503|-0.99%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.1779|73.274|1.0961|1.52%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.0233|279.9829|5.9596|2.17%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.0886|39.6594|1.5708|4.12%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.1868|20.1188|-0.068|-0.34%|
|migraphx_bert__bertsquad-12|PASS|regression|18.5731|19.7333|1.1602|6.25%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.737|155.9702|3.2333|2.12%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|215.1557|217.7704|2.6147|1.22%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4966|7.5554|0.0588|0.78%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|42.7258|45.9079|3.1821|7.45%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4589|6.594|0.1351|2.09%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.2124|33.0364|0.8241|2.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.3541|53.3558|1.0017|1.91%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|22.3021|27.4237|5.1215|22.96%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|11.4327|15.6887|4.256|37.23%|
|migraphx_torchvision__densenet121i32|PASS|within tol|52.161|52.78|0.6191|1.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9308|15.9994|0.0686|0.43%|
|migraphx_torchvision__inceptioni32|PASS|within tol|142.9626|146.3037|3.3411|2.34%|
|migraphx_torchvision__resnet50i64|PASS|within tol|189.1703|193.1968|4.0264|2.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.5641|34.6986|1.1345|3.38%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.9224|59.7912|1.8689|3.23%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.2657|75.8248|2.5591|3.49%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5814|13.6103|0.0289|0.21%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.9669|13.8189|-0.148|-1.06%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0116|20.404|0.3924|1.96%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4069|13.4517|0.0448|0.33%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.087|13.9735|-0.1134|-0.81%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6295|21.9813|0.3517|1.63%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.3779|71.5602|2.1824|3.15%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.7366|108.0951|3.3585|3.21%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.179|150.356|5.177|3.57%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0168|15.1255|0.1087|0.72%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.4877|17.7908|0.3031|1.73%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6726|27.4286|0.756|2.83%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1061|20.477|0.3709|1.84%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0543|29.007|0.9527|3.4%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.3811|42.8217|1.4406|3.48%|

## No Regressions Found

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|resmlp_12_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_12_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_24_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_24_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_36_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_36_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|compilation|PASS|

