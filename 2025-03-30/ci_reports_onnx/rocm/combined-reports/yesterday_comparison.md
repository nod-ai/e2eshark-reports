# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.1765|115.0624|-1.1141|-0.96%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|118.2465|115.3117|-2.9348|-2.48%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.9952|520.5785|-1.4167|-0.27%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.7238|72.0165|3.2926|4.79%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.422|62.3158|-1.1061|-1.74%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|332.7059|327.5292|-5.1768|-1.56%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8937|34.3647|-0.529|-1.52%|
|migraphx_agentmodel__AgentModel|Numerics|regression|2.0473|2.4948|0.4475|21.86%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.8212|19.7565|-0.0646|-0.33%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0175|5.1513|0.1338|2.67%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|29.6782|29.6589|-0.0194|-0.07%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.9562|5.9409|-0.0153|-0.26%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.5154|29.6999|0.1845|0.63%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3509|7.3772|0.0264|0.36%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.6724|26.3037|-0.3687|-1.38%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.927|4.7772|-0.1498|-3.04%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.9405|39.5648|-0.3757|-0.94%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|47.0886|52.13|5.0414|10.71%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.6442|20.2668|2.6226|14.86%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.0072|8.7112|-0.2961|-3.29%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.891|17.8461|-0.0449|-0.25%|
|migraphx_torchvision__inceptioni1|PASS|regression|4.9829|20.1096|15.1267|303.57%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0365|27.895|-0.1414|-0.5%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1939|3.1572|-0.0367|-1.15%|
|migraphx_torchvision__resnet50i64|PASS|regression|20.6653|40.7182|20.0529|97.04%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.8463|26.9952|-0.8511|-3.06%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.4754|38.4029|-1.0725|-2.72%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.3115|58.2043|-1.1072|-1.87%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0779|12.1193|0.0415|0.34%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5357|12.492|-0.0437|-0.35%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4291|19.3985|-0.0306|-0.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5581|12.7443|0.1862|1.48%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5159|19.4754|-0.0405|-0.21%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.5695|20.42|-0.1495|-0.73%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.7668|36.9981|-0.7687|-2.04%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.6387|77.8245|-1.8141|-2.28%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|121.6883|119.3534|-2.3349|-1.92%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.73|19.6254|-0.1046|-0.53%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.5777|20.8004|-0.7773|-3.6%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.5391|24.2439|-0.2952|-1.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0415|20.9061|-0.1354|-0.64%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1764|27.5779|-0.5984|-2.12%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.665|35.1771|-0.4879|-1.37%|

## 9 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|VGG19_bn_vaiq|PASS|Numerics|
|convnextv2_base.fcmae_ft_in1k|PASS|Numerics|
|convnextv2_large.fcmae_ft_in22k_in1k|PASS|Numerics|
|migraphx_cadene__inceptionv4i16|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-squad--tmgondal|PASS|Numerics|
|model--gpt2--openai-community|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-32-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|vgg19_bn_vaiq|PASS|Numerics|

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-ner--fengi|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|Numerics|PASS|

