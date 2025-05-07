# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.3047|116.9488|1.6441|1.43%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.5736|116.4265|-1.1472|-0.98%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|525.8207|523.5961|-2.2246|-0.42%|
|migraphx_ORT__distilgpt2_1|PASS|progression|72.7048|69.056|-3.6487|-5.02%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.8913|64.5657|1.6744|2.66%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|307.5469|311.7629|4.216|1.37%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.7065|34.3731|-1.3333|-3.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1429|19.149|0.0061|0.03%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.697|3.7093|0.0123|0.33%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.133|27.2942|0.1612|0.59%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.4567|4.3762|-0.0805|-1.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9217|7.0808|0.159|2.3%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.2442|27.5374|0.2932|1.08%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0044|13.9369|-0.0676|-0.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.5287|41.4696|1.9409|4.91%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|124.6527|127.6573|3.0046|2.41%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.5234|17.7116|-0.8118|-4.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.948|7.4147|-2.5333|-25.47%|
|migraphx_torchvision__densenet121i32|PASS|regression|17.6731|18.7022|1.0291|5.82%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.3482|4.3707|0.0225|0.52%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1596|3.1342|-0.0253|-0.8%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.155|27.7185|0.5635|2.08%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.9893|40.1552|1.1659|2.99%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9535|59.4305|1.477|2.55%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3975|12.3773|-0.0203|-0.16%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4446|12.4896|0.045|0.36%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3541|19.2763|-0.0778|-0.4%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6284|12.5519|-0.0765|-0.61%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.233|19.1945|-0.0385|-0.2%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.0324|20.2906|0.2582|1.29%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.7031|38.7978|1.0946|2.9%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|73.8512|75.3823|1.5311|2.07%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|115.8694|115.9362|0.0669|0.06%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.3079|19.4212|0.1133|0.59%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.4974|20.7206|0.2232|1.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1573|24.4156|0.2583|1.07%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6117|20.7933|0.1816|0.88%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5849|28.2393|0.6544|2.37%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.5497|35.5289|0.9792|2.83%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|dla169_Opset16_timm|PASS|Numerics|

## 10 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_224.in22k_ft_in22k_in1k|Numerics|PASS|
|bvlcalexnet-12|compilation|PASS|
|bvlcalexnet-8|compilation|PASS|
|coatnet_3_rw_224.sw_in12k|Numerics|PASS|
|eca_resnext26ts_Opset17_timm|compilation|compiled_inference|
|edgenext_x_small|compilation|PASS|
|model--distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es--mrm8488|Numerics|PASS|
|model--pegasus-cnn_dailymail--google|Numerics|PASS|
|opt_Opset16_transformers|Numerics|PASS|
|xcit_medium_24_p8_384_dist_Opset17_timm|Numerics|PASS|

