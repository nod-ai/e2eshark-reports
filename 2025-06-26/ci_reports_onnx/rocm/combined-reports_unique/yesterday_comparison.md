# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.5107|125.7632|3.2525|2.65%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|122.6842|152.8956|30.2114|24.63%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|538.3967|543.9936|5.5969|1.04%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|70.0717|69.6381|-0.4336|-0.62%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.8552|68.0551|1.1999|1.79%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.19|343.6955|3.5055|1.03%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.2712|35.9505|0.6792|1.93%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9492|18.9986|0.0494|0.26%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.6472|3.6979|0.0507|1.39%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.375|19.7125|0.3376|1.74%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.3101|4.2079|-0.1022|-2.37%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9446|6.9685|0.0239|0.34%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.1423|26.7519|0.6096|2.33%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9785|13.9115|-0.067|-0.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|46.3647|47.8898|1.525|3.29%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|103.5837|113.4234|9.8397|9.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.7465|17.5792|-2.1673|-10.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.7207|7.7837|-2.937|-27.4%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.9452|12.9237|-0.0215|-0.17%|
|migraphx_torchvision__inceptioni1|Numerics|progression|4.2986|3.3343|-0.9643|-22.43%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2481|2.2296|-0.0185|-0.82%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.0986|26.5486|0.45|1.72%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.6561|38.7285|1.0724|2.85%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.4218|57.6185|1.1967|2.12%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2867|12.2807|-0.006|-0.05%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.412|12.4298|0.0178|0.14%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.9968|18.8898|-0.107|-0.56%|
|migx_bench_bert-large-uncased_2_128|Numerics|within tol|12.5291|12.409|-0.1201|-0.96%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.8318|18.8417|0.0099|0.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8262|19.8253|-0.0009|-0.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.0456|38.0498|1.0042|2.71%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.4425|73.1504|1.7078|2.39%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|115.8462|124.4318|8.5856|7.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.2354|19.0268|-0.2085|-1.08%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.9579|20.0431|0.0852|0.43%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.213|23.4125|0.1995|0.86%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0911|20.1912|0.1001|0.5%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.4361|26.872|0.436|1.65%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.3906|33.293|0.9024|2.79%|

## 9 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|cait_m48_448_Opset16_timm|PASS|Numerics|
|ibert_Opset17_transformers|PASS|Numerics|
|maxvit_rmlp_small_rw_224.sw_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_2_128|PASS|Numerics|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3--husnu|PASS|Numerics|
|model--flan-t5-large-samsum--oguuzhansahin|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|PASS|Numerics|
|model--roberta-large-finetuned-ner--romainlhardy|PASS|Numerics|
|swin_base_patch4_window12_384.ms_in1k|PASS|Numerics|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|cait_m36_384_Opset16_timm|Numerics|PASS|
|cait_m48_448_Opset17_timm|Numerics|PASS|
|model--deberta-v3-xsmall-squad2--nlpconnect|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--marian-finetuned-kde4-cs2sv--ksaml|Numerics|PASS|

