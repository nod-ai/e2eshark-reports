# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|104.9154|107.7275|2.8121|2.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|104.2585|114.3833|10.1248|9.71%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|468.659|1970.7065|1502.0475|320.5%|
|migraphx_ORT__distilgpt2_1|PASS|regression|59.9171|116.4683|56.5513|94.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|64.8662|123.4787|58.6125|90.36%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.163|279.7768|7.6138|2.8%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.1215|33.2873|1.1658|3.63%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4497|19.5861|0.1364|0.7%|
|migraphx_cadene__dpn92i1|Numerics|within tol|64.7155|64.7762|0.0607|0.09%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.1809|150.2789|-3.9019|-2.53%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|173.5548|175.3103|1.7555|1.01%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|387.5817|391.708|4.1262|1.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1895|7.4013|0.2119|2.95%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.8883|25.3181|0.4298|1.73%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.8731|43.4749|0.6018|1.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.8684|144.4191|1.5508|1.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.6375|15.693|-0.9446|-5.68%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.9748|6.956|-1.0188|-12.78%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|69.0149|66.2454|-2.7695|-4.01%|
|migraphx_torchvision__inceptioni1|PASS|within tol|62.2161|61.0628|-1.1533|-1.85%|
|migraphx_torchvision__inceptioni32|PASS|within tol|105.7796|101.9857|-3.7939|-3.59%|
|migraphx_torchvision__resnet50i1|Numerics|progression|17.124|15.8179|-1.3061|-7.63%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|148.077|147.4967|-0.5802|-0.39%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.4837|34.9694|1.4857|4.44%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.0522|59.1036|2.0514|3.6%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.8827|78.9767|3.094|4.08%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1022|12.1871|0.0848|0.7%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7756|12.7183|-0.0573|-0.45%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.6206|19.711|0.0904|0.46%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8439|12.8694|0.0255|0.2%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3652|13.4397|0.0745|0.56%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6407|21.9388|0.298|1.38%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.0899|71.8752|2.7853|4.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.6748|108.7969|4.1221|3.94%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.1271|160.7717|6.6446|4.31%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4459|14.5448|0.0989|0.68%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.0856|17.659|0.5733|3.36%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.0122|27.8717|0.8595|3.18%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.6553|20.2989|0.6436|3.27%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1444|29.2123|1.0678|3.79%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.1224|43.6448|1.5223|3.61%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|mvitv2_small|compilation|PASS|

