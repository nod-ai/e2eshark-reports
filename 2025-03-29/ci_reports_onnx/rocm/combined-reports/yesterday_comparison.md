# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.8953|116.1765|1.2812|1.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.0267|118.2465|2.2198|1.91%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|524.326|521.9952|-2.3308|-0.44%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.4047|68.7238|0.3191|0.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.1518|63.422|1.2702|2.04%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|327.4731|332.7059|5.2328|1.6%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1458|34.8937|0.7479|2.19%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.319|2.0473|-0.2718|-11.72%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3|19.8212|0.5211|2.7%|
|migraphx_cadene__dpn92i1|PASS|progression|5.322|5.0175|-0.3045|-5.72%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.1497|29.6782|0.5286|1.81%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.8898|5.9562|0.0664|1.13%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.0167|29.5154|-0.5014|-1.67%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0026|7.3509|0.3483|4.97%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.6828|26.6724|-1.0103|-3.65%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8155|4.927|0.1115|2.32%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|38.7138|39.9405|1.2267|3.17%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.5331|47.0886|0.5555|1.19%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.1372|17.6442|-1.493|-7.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.7458|9.0072|-0.7386|-7.58%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8418|17.891|0.0492|0.28%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8657|4.9829|0.1172|2.41%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.9652|28.0365|0.0713|0.25%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1784|3.1939|0.0155|0.49%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.3942|20.6653|0.2711|1.33%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.9305|27.8463|0.9158|3.4%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.6996|39.4754|0.7757|2.0%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.4238|59.3115|0.8876|1.52%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2247|12.0779|-0.1468|-1.2%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6741|12.5357|-0.1384|-1.09%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4782|19.4291|-0.0491|-0.25%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5691|12.5581|-0.011|-0.09%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4277|19.5159|0.0882|0.45%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2961|20.5695|0.2734|1.35%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.7612|37.7668|1.0056|2.74%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.5704|79.6387|2.0683|2.67%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.3974|121.6883|3.2909|2.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4878|19.73|0.2422|1.24%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8429|21.5777|0.7348|3.53%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1207|24.5391|0.4184|1.73%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8195|21.0415|0.222|1.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.488|28.1764|0.6884|2.5%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.8294|35.665|0.8356|2.4%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-ner--fengi|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|PASS|Numerics|

## No Progressions Found

