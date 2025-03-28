# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.6028|114.8953|-0.7075|-0.61%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|118.1862|116.0267|-2.1595|-1.83%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|518.0625|524.326|6.2636|1.21%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.5671|68.4047|-1.1623|-1.67%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.7675|62.1518|-1.6157|-2.53%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|332.2419|327.4731|-4.7688|-1.44%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.0125|34.1458|-0.8667|-2.48%|
|migraphx_agentmodel__AgentModel|Numerics|regression|2.1436|2.319|0.1754|8.18%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0887|19.3|-0.7886|-3.93%|
|migraphx_cadene__dpn92i1|PASS|regression|5.0135|5.322|0.3085|6.15%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.922|29.1497|-0.7723|-2.58%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.1957|5.8898|-0.306|-4.94%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.5484|30.0167|0.4683|1.58%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2134|7.0026|-0.2109|-2.92%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.0652|27.6828|0.6175|2.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7404|4.8155|0.075|1.58%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.2264|38.7138|-1.5126|-3.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.7246|46.5331|-0.1915|-0.41%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.4592|19.1372|0.678|3.67%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.8727|9.7458|0.8732|9.84%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.9334|17.8418|-0.0916|-0.51%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8503|4.8657|0.0154|0.32%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0434|27.9652|-0.0782|-0.28%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1574|3.1784|0.021|0.67%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.6896|20.3942|-0.2954|-1.43%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.7241|26.9305|-0.7936|-2.86%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.3067|38.6996|-0.6071|-1.54%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4427|58.4238|-1.0189|-1.71%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9394|12.2247|0.2852|2.39%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5012|12.6741|0.1729|1.38%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.52|19.4782|-0.0418|-0.21%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6936|12.5691|-0.1245|-0.98%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5149|19.4277|-0.0872|-0.45%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.5827|20.2961|-0.2867|-1.39%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8194|36.7612|-1.0582|-2.8%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.734|77.5704|-2.1636|-2.71%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|121.8543|118.3974|-3.4569|-2.84%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5095|19.4878|-0.0216|-0.11%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9729|20.8429|-0.13|-0.62%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.5307|24.1207|-0.41|-1.67%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0741|20.8195|-0.2546|-1.21%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1558|27.488|-0.6678|-2.37%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.7183|34.8294|-0.8889|-2.49%|

## No Regressions Found

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large.fb_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|model--bert-finetuned-ner--cleandata|Numerics|PASS|
|model--bert-finetuned-ner--ishantja|Numerics|PASS|
|model--questionanswering-v3--abdalrahmanshahrour|Numerics|PASS|
|model--roberta-large-tweetner7-all--tner|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|PASS|

