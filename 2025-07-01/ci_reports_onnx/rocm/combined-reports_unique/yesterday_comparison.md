# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|121.4508|130.5755|9.1247|7.51%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|121.2695|122.2671|0.9976|0.82%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|542.306|552.3509|10.0449|1.85%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|70.0133|69.9182|-0.0951|-0.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.0022|66.6152|0.613|0.93%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.1807|340.9805|0.7998|0.24%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.0791|35.0818|1.0026|2.94%|
|migraphx_bert__bert-large-uncased|PASS|regression|18.8441|68.8196|49.9756|265.21%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.6515|3.5239|-0.1277|-3.5%|
|migraphx_cadene__inceptionv4i16|PASS|regression|20.0537|21.5728|1.519|7.57%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|4.3106|7.6363|3.3257|77.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|6.9734|14.8119|7.8386|112.41%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|25.2744|27.0352|1.7608|6.97%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0642|14.1076|0.0434|0.31%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|41.7441|45.651|3.9068|9.36%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|102.9511|103.0375|0.0865|0.08%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.3538|16.8419|-0.5119|-2.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.5156|8.1139|-0.4018|-4.72%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.995|14.4407|0.4457|3.18%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1379|3.197|0.059|1.88%|
|migraphx_torchvision__resnet50i1|PASS|regression|2.048|4.9457|2.8977|141.49%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7977|26.3291|0.5314|2.06%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.37|37.3195|-0.0505|-0.14%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|55.5028|56.492|0.9893|1.78%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1548|12.6112|0.4564|3.75%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3906|12.818|0.4274|3.45%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|18.9654|32.1728|13.2074|69.64%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5196|13.1155|0.5959|4.76%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9597|19.2308|0.2711|1.43%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8498|20.1202|0.2704|1.36%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.6596|36.0503|-0.6093|-1.66%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|70.7435|187.4422|116.6987|164.96%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|115.9955|133.6146|17.6191|15.19%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.1069|19.6917|0.5848|3.06%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.8073|20.1667|0.3594|1.81%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|22.9852|23.5514|0.5662|2.46%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0328|20.3166|0.2837|1.42%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.3591|99.6336|73.2745|277.99%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|32.2249|134.6317|102.4067|317.79%|

## 10 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|cait_m48_448_Opset16_timm|PASS|Numerics|
|cait_s24_384_Opset16_timm|PASS|Numerics|
|deit3_base_patch16_224_Opset16_timm|PASS|Numerics|
|ig_resnext101_32x32d_Opset18_timm|PASS|Numerics|
|model--bert-german-ner--lunesco|PASS|Numerics|
|model--roberta-l-squadv1.1--vuiseng9|PASS|Numerics|
|swin_large_patch4_window7_224_in22k_Opset17_timm|PASS|Numerics|
|swin_s_Opset18_torch_hub|PASS|Numerics|
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_base_window8_256_Opset17_timm|PASS|Numerics|

## 18 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset16_transformers|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_large_patch16_224.fb_in1k|Numerics|PASS|
|eca_resnet33ts.ra2_in1k_train_vaiq|compilation|PASS|
|eca_resnet33ts.ra2_in1k_vaiq|compilation|PASS|
|eca_resnext26ts.ch_in1k_train_vaiq|compilation|PASS|
|eca_resnext26ts.ch_in1k_vaiq|compilation|PASS|
|maxvit_base_tf_224.in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_16_256|Numerics|PASS|
|mixer_l16_224_in21k_Opset16_timm|Numerics|PASS|
|model--Translation--shed-e|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-hi--vsrinivas|Numerics|PASS|
|model--pegasus-cnn_dailymail--google|Numerics|PASS|
|model--pythia-410mn-ntoxic--skrishna|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|squeezenet1.0-13-qdq|compilation|PASS|
|swin_s3_small_224_Opset16_timm|Numerics|PASS|
|swin_small_patch4_window7_224_Opset16_timm|Numerics|PASS|

