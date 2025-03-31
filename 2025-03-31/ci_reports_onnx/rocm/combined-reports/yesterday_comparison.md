# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.0624|117.7717|2.7093|2.35%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.3117|115.4937|0.182|0.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|520.5785|519.8766|-0.7019|-0.13%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|72.0165|69.5903|-2.4261|-3.37%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.3158|62.358|0.0421|0.07%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|327.5292|328.9088|1.3796|0.42%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.3647|34.3718|0.0071|0.02%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.4948|2.0163|-0.4784|-19.18%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.7565|19.3536|-0.4029|-2.04%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.1513|5.0288|-0.1225|-2.38%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.6589|29.2005|-0.4584|-1.55%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|5.9409|6.2839|0.343|5.77%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.6999|29.568|-0.1319|-0.44%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3772|7.0151|-0.3621|-4.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.3037|26.4381|0.1343|0.51%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7772|4.7938|0.0166|0.35%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.5648|39.3273|-0.2375|-0.6%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|52.13|45.9563|-6.1738|-11.84%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.2668|19.3015|-0.9653|-4.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.7112|9.0222|0.3111|3.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8461|17.903|0.0569|0.32%|
|migraphx_torchvision__inceptioni1|PASS|progression|20.1096|4.8373|-15.2722|-75.95%|
|migraphx_torchvision__inceptioni32|PASS|within tol|27.895|27.9258|0.0308|0.11%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1572|3.12|-0.0372|-1.18%|
|migraphx_torchvision__resnet50i64|PASS|progression|40.7182|20.5048|-20.2133|-49.64%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.9952|27.0403|0.0451|0.17%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.4029|38.3949|-0.0079|-0.02%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.2043|57.9293|-0.275|-0.47%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1193|12.0789|-0.0404|-0.33%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.492|13.1857|0.6937|5.55%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3985|19.3972|-0.0012|-0.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7443|12.6866|-0.0577|-0.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4754|19.5023|0.0269|0.14%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.42|20.3421|-0.0779|-0.38%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.9981|36.6688|-0.3293|-0.89%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.8245|77.6777|-0.1468|-0.19%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|119.3534|118.3675|-0.9859|-0.83%|
|migx_bench_bert-large-uncased_4_128|Numerics|within tol|19.6254|19.5116|-0.1138|-0.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8004|20.8978|0.0974|0.47%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.2439|24.2321|-0.0118|-0.05%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9061|20.9201|0.014|0.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5779|27.7639|0.1859|0.67%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.1771|34.9291|-0.248|-0.71%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_base.clip_laiona_augreg_ft_in1k_384|PASS|Numerics|
|migx_bench_bert-large-uncased_4_128|PASS|Numerics|
|model--bert-medium-squad2-distilled--deepset|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--Ibrahim-Alam|PASS|Numerics|
|model--lsg-bart-base-4096-booksum--ccdv|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|

## 9 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|VGG19_bn_vaiq|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k|Numerics|PASS|
|migraphx_cadene__inceptionv4i16|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-squad--tmgondal|Numerics|PASS|
|model--gpt2--openai-community|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-32-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|vgg19_bn_vaiq|Numerics|PASS|

