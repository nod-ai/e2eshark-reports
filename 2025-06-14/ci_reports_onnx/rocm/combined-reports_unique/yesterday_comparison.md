# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.3143|122.5808|1.2665|1.04%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.4841|122.2074|-1.2767|-1.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|539.0623|542.046|2.9837|0.55%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.9557|69.4662|0.5105|0.74%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.3982|66.5341|0.1359|0.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|339.9772|341.2177|1.2405|0.36%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.4609|34.3234|-0.1375|-0.4%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3457|19.4418|0.0961|0.5%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.7823|3.7248|-0.0575|-1.52%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.2995|19.2486|-0.0509|-0.26%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.3936|4.3611|-0.0325|-0.74%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9417|7.0447|0.103|1.48%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.2382|25.2604|0.0222|0.09%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9252|13.9736|0.0484|0.35%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.5156|41.3279|-0.1876|-0.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|104.4245|103.4816|-0.9429|-0.9%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.4082|18.6745|0.2663|1.45%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.3968|8.5459|-1.8509|-17.8%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.8324|12.8375|0.0051|0.04%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.2399|3.3057|0.0658|2.03%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2687|2.2474|-0.0213|-0.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.512|27.4947|-0.0173|-0.06%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.7262|38.7848|-0.9413|-2.37%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|57.4222|56.0811|-1.3411|-2.34%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3524|12.3139|-0.0385|-0.31%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6181|12.6164|-0.0017|-0.01%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.316|19.4224|0.1064|0.55%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.725|12.7688|0.0439|0.34%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.8617|19.4656|-0.3961|-1.99%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2969|20.2585|-0.0384|-0.19%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.18|37.6518|-0.5282|-1.38%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.6106|71.5655|-1.0451|-1.44%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|112.0987|110.0407|-2.0581|-1.84%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6543|19.5885|-0.0658|-0.33%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.0804|20.7244|-0.356|-1.69%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.3898|24.224|-0.1658|-0.68%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9802|20.8814|-0.0989|-0.47%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0894|28.0406|-0.0488|-0.17%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.8545|34.5196|-0.3349|-0.96%|

## 5 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--bert-base-multilingual-uncased-finetuned-squad--Martin97Bozic|PASS|Numerics|
|model--distilbert-base-german-cased-finetuned-ner--FabianWillner|PASS|Numerics|
|model--distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es--mrm8488|PASS|Numerics|
|model--dynamic_tinybert--Intel|PASS|Numerics|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|PASS|Numerics|

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|cait_m48_448_Opset16_timm|Numerics|PASS|
|migx_bench_bert-large-uncased_2_256|Numerics|PASS|
|tf_efficientnetv2_l_in21k_Opset16_timm|Numerics|PASS|

