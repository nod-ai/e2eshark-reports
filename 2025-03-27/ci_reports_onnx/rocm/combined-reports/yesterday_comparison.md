# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.8504|115.6028|-0.2476|-0.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.8623|118.1862|2.3239|2.01%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.4951|518.0625|-3.4327|-0.66%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.7991|69.5671|1.768|2.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.4181|63.7675|1.3494|2.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|329.3012|332.2419|2.9408|0.89%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|66.6629|35.0125|-31.6503|-47.48%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.8424|2.1436|0.3012|16.35%|
|migraphx_bert__bert-large-uncased|PASS|progression|26.3277|20.0887|-6.2391|-23.7%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0484|5.0135|-0.0349|-0.69%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2747|29.922|0.6473|2.21%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.1267|6.1957|0.0691|1.13%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.425|29.5484|0.1234|0.42%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9221|7.2134|0.2914|4.21%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.4216|27.0652|0.6436|2.44%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.3042|4.7404|-0.5638|-10.63%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.3929|40.2264|0.8334|2.12%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.1576|46.7246|0.567|1.23%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.6331|18.4592|1.8261|10.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.8287|8.8727|2.0439|29.93%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.9378|17.9334|-0.0044|-0.02%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8926|4.8503|-0.0423|-0.86%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.959|28.0434|0.0844|0.3%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1774|3.1574|-0.0199|-0.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.5272|20.6896|0.1624|0.79%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.9378|27.7241|0.7863|2.92%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.6779|39.3067|0.6289|1.63%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.7841|59.4427|0.6586|1.12%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0676|11.9394|-0.1282|-1.06%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4957|12.5012|0.0055|0.04%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4096|19.52|0.1105|0.57%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5852|12.6936|0.1084|0.86%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.6028|19.5149|-0.0879|-0.45%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3125|20.5827|0.2702|1.33%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.1032|37.8194|0.7162|1.93%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|78.5117|79.734|1.2223|1.56%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|119.997|121.8543|1.8573|1.55%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4822|19.5095|0.0272|0.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2071|20.9729|0.7658|3.79%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1012|24.5307|0.4294|1.78%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8899|21.0741|0.1841|0.88%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0709|28.1558|0.0849|0.3%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|59.2858|35.7183|-23.5675|-39.75%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large.fb_in1k|PASS|Numerics|
|convnextv2_large.fcmae_ft_in1k|PASS|Numerics|
|model--bert-finetuned-ner--cleandata|PASS|Numerics|
|model--bert-finetuned-ner--ishantja|PASS|Numerics|
|model--questionanswering-v3--abdalrahmanshahrour|PASS|Numerics|
|model--roberta-large-tweetner7-all--tner|PASS|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|PASS|Numerics|

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migx_bench_bert-large-uncased_1_384|Numerics|PASS|
|model--YuisekinAI-mistral-0.7B--yuiseki|Numerics|PASS|
|model--bert-finetuned-squad--trjindal01|Numerics|PASS|

