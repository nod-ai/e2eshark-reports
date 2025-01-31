# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|120.9299|97.4008|-23.5291|-19.46%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.4861|91.2703|2.7842|3.15%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|255.797|253.4645|-2.3325|-0.91%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|29.955|31.0442|1.0891|3.64%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|95.5575|84.2744|-11.2831|-11.81%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|249.9069|572.4404|322.5335|129.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|45.6843|40.244|-5.4404|-11.91%|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.5307|370.1002|-0.4304|-0.12%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.3352|164.2987|-0.0365|-0.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5602.3825|5571.1048|-31.2777|-0.56%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.8749|311.1995|-8.6755|-2.71%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5080.6141|4972.8223|-107.7918|-2.12%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|372.9824|374.0662|1.0838|0.29%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.0605|418.9067|-5.1538|-1.22%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.8105|103.5266|2.7161|2.69%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.9567|32.097|1.1403|3.68%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.9147|180.3023|0.3876|0.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|91.7118|76.3558|-15.356|-16.74%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|39.805|45.6536|5.8486|14.69%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1492.9308|1492.351|-0.5798|-0.04%|
|migraphx_torchvision__inceptioni1|PASS|within tol|203.0548|204.6526|1.5978|0.79%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5776.5917|5792.2729|15.6812|0.27%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.5608|86.6117|3.0508|3.65%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5426.43|5416.9999|-9.4301|-0.17%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2611.5524|2544.9632|-66.5892|-2.55%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4077.2371|4199.8584|122.6214|3.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5815.3013|5689.463|-125.8383|-2.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.0547|157.1469|-2.9078|-1.82%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.0947|259.3493|-3.7454|-1.42%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|388.8945|379.3879|-9.5066|-2.44%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|452.7449|384.2456|-68.4993|-15.13%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|581.1372|609.1193|27.982|4.82%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|843.2373|890.535|47.2978|5.61%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5027.396|5143.936|116.54|2.32%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8816.0027|8072.5558|-743.4469|-8.43%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11271.7559|11254.2081|-17.5479|-0.16%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|737.3061|778.9573|41.6512|5.65%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1076.4619|1078.7228|2.2608|0.21%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1552.408|1506.9964|-45.4116|-2.93%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1305.3583|1313.0773|7.719|0.59%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2062.4858|2042.6735|-19.8123|-0.96%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2887.2919|2878.3515|-8.9404|-0.31%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|Numerics|PASS|

