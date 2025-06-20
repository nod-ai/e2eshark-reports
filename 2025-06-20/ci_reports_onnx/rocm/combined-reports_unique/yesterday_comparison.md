# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.4784|122.0705|-0.4079|-0.33%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.009|121.5853|-1.4237|-1.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|538.0441|538.4295|0.3854|0.07%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.0526|68.7585|-0.2941|-0.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.1074|66.1425|0.0351|0.05%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|341.8764|340.0242|-1.8522|-0.54%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.7295|35.3301|0.6006|1.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3713|18.9344|-0.4369|-2.26%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.7521|3.6304|-0.1216|-3.24%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.6837|19.3187|-0.365|-1.85%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.4283|4.3336|-0.0948|-2.14%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0009|6.9463|-0.0546|-0.78%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|27.4835|24.5514|-2.9321|-10.67%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9068|13.9664|0.0596|0.43%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.4763|41.6175|-0.8588|-2.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|110.5715|101.9236|-8.648|-7.82%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.6471|18.113|1.4659|8.81%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.2801|7.5709|-1.7092|-18.42%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.8366|12.9651|0.1285|1.0%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.3034|3.379|0.0756|2.29%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2422|2.23|-0.0121|-0.54%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|27.5501|26.0335|-1.5166|-5.5%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.1055|37.8325|-1.273|-3.26%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.5943|56.501|-0.0933|-0.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4486|12.2055|-0.2431|-1.95%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5206|12.3175|-0.2031|-1.62%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3457|18.9042|-0.4415|-2.28%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.917|12.5372|-0.3797|-2.94%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4865|18.881|-0.6055|-3.11%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2543|19.6427|-0.6116|-3.02%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8903|37.0789|-0.8114|-2.14%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.5925|71.7216|-0.8709|-1.2%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|112.4011|116.2524|3.8513|3.43%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5419|19.1447|-0.3972|-2.03%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8988|19.9044|-0.9945|-4.76%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|24.3464|23.0896|-1.2568|-5.16%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0114|20.0284|-0.983|-4.68%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|28.0034|26.4493|-1.5541|-5.55%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|34.6307|32.4774|-2.1532|-6.22%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|dm_nfnet_f2_Opset16_timm|PASS|compilation|
|model--deberta-v3-base__sst2__all-train--SetFit|PASS|compilation|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|PASS|compilation|

## No Progressions Found

