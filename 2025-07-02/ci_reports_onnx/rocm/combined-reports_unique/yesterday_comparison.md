# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|130.5755|125.8213|-4.7541|-3.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|122.2671|124.6706|2.4035|1.97%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|552.3509|542.8825|-9.4684|-1.71%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.9182|69.5253|-0.3929|-0.56%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.6152|67.6149|0.9997|1.5%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.9805|344.4653|3.4848|1.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|35.0818|38.8519|3.7701|10.75%|
|migraphx_bert__bert-large-uncased|PASS|progression|68.8196|19.5029|-49.3167|-71.66%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5239|3.5416|0.0177|0.5%|
|migraphx_cadene__inceptionv4i16|PASS|progression|21.5728|20.0865|-1.4862|-6.89%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|7.6363|4.2178|-3.4185|-44.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|14.8119|7.0691|-7.7428|-52.27%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|27.0352|25.4651|-1.5701|-5.81%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1076|14.0063|-0.1013|-0.72%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.651|46.4399|0.789|1.73%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.0375|105.8206|2.7831|2.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.8419|20.8393|3.9973|23.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.1139|9.6037|1.4899|18.36%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.4407|13.7817|-0.659|-4.56%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.197|3.1616|-0.0354|-1.11%|
|migraphx_torchvision__resnet50i1|PASS|progression|4.9457|2.0446|-2.9011|-58.66%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.3291|26.9873|0.6581|2.5%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.3195|38.1846|0.865|2.32%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.492|57.7212|1.2292|2.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6112|12.5949|-0.0163|-0.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.818|12.8956|0.0776|0.61%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|32.1728|19.3997|-12.7731|-39.7%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.1155|12.9381|-0.1774|-1.35%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2308|19.3636|0.1328|0.69%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.1202|19.9243|-0.1959|-0.97%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.0503|37.1543|1.104|3.06%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|187.4422|71.7507|-115.6914|-61.72%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|133.6146|113.3468|-20.2678|-15.17%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|19.6917|31.6204|11.9287|60.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1667|20.328|0.1614|0.8%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.5514|23.7885|0.237|1.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3166|20.5039|0.1873|0.92%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|99.6336|26.6969|-72.9368|-73.2%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|134.6317|33.6673|-100.9643|-74.99%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-ner--dbsamu|PASS|Numerics|
|model--gpt2-alpaca-gpt4--vicgalle|PASS|Numerics|
|model--pegasus-large-booksum--cnicu|PASS|Numerics|
|vgg13_Opset18_torch_hub|PASS|Numerics|
|vit_large_patch16_384_Opset16_timm|PASS|Numerics|

## 12 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|RDN_pytorch_vaiq_int8|compilation|Numerics|
|ShuffleNet_v2_x2_0_vaiq_int8|compilation|PASS|
|cait_m48_448_Opset16_timm|Numerics|PASS|
|cait_s24_384_Opset16_timm|Numerics|PASS|
|deit3_base_patch16_224_Opset16_timm|Numerics|PASS|
|ig_resnext101_32x32d_Opset18_timm|Numerics|PASS|
|model--bert-german-ner--lunesco|Numerics|PASS|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|PASS|
|swin_large_patch4_window7_224_in22k_Opset17_timm|Numerics|PASS|
|swin_s_Opset18_torch_hub|Numerics|PASS|
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k|Numerics|PASS|
|swinv2_base_window8_256_Opset17_timm|Numerics|PASS|

