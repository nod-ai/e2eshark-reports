# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.7536|110.4707|-1.2829|-1.15%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.0611|110.0295|-0.0316|-0.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|520.7384|512.8923|-7.8461|-1.51%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.8643|68.9069|1.0426|1.54%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|76.6943|62.1541|-14.5403|-18.96%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.4493|269.4493|-4.0|-1.46%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.2284|36.1033|-1.1251|-3.02%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1132|19.1954|0.0822|0.43%|
|migraphx_cadene__dpn92i1|PASS|regression|3.4384|3.6788|0.2404|6.99%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.1891|20.3977|0.2086|1.03%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1779|4.2746|0.0967|2.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0264|7.1248|0.0983|1.4%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.6557|26.7974|0.1418|0.53%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1603|14.2388|0.0785|0.55%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.5975|43.4775|-2.12|-4.65%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|103.7222|113.5062|9.784|9.43%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.2724|19.9073|-0.3651|-1.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.7465|9.3152|-0.4313|-4.42%|
|migraphx_torchvision__densenet121i32|PASS|regression|13.7894|14.5549|0.7655|5.55%|
|migraphx_torchvision__inceptioni1|PASS|progression|3.3721|3.0582|-0.3138|-9.31%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0338|2.0506|0.0168|0.82%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.2826|25.7124|-0.5702|-2.17%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.3231|37.4313|-0.8918|-2.33%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.5115|56.223|-1.2885|-2.24%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6422|12.5684|-0.0738|-0.58%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7836|12.6642|-0.1194|-0.93%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3214|19.2622|-0.0591|-0.31%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9574|13.0332|0.0758|0.59%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.7141|19.1344|-0.5797|-2.94%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.944|19.9483|-0.9957|-4.75%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.0124|35.907|-1.1054|-2.99%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.7264|69.5553|-2.1711|-3.03%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|113.8483|111.0359|-2.8124|-2.47%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.1801|19.2146|0.0344|0.18%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.446|20.1284|-0.3176|-1.55%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4064|23.3372|-0.0693|-0.3%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.4359|20.1942|-0.2417|-1.18%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|27.8473|26.2334|-1.6139|-5.8%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.5772|32.7491|-0.8281|-2.47%|

## No Regressions Found

## 23 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset16_transformers|Numerics|PASS|
|deit3_large_patch16_384_in21ft1k_Opset17_timm|Numerics|PASS|
|deit_base_patch16_224.fb_in1k|Numerics|PASS|
|distilbert_Opset18_transformers|Numerics|PASS|
|gcvit_small|Numerics|PASS|
|gpt2lmhead_Opset16_transformers|Numerics|PASS|
|maxvit_base_tf_224.in1k|Numerics|PASS|
|migraphx_huggingface-transformers__bert_mrpc8|Numerics|PASS|
|migx_bench_bert-large-uncased_1_128|Numerics|PASS|
|model--bert-engonly-sentiment-test--SiddharthaM|Numerics|PASS|
|model--bert-large-NER--51la5|Numerics|PASS|
|model--cm_code_clippy--ncoop57|Numerics|PASS|
|model--hebrew_poetry-gpt_neo-small--Norod78|Numerics|PASS|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|Numerics|PASS|
|pit_b_distilled_224_Opset18_timm|Numerics|PASS|
|swin_base_patch4_window7_224_in22k_Opset17_timm|Numerics|PASS|
|swin_large_patch4_window7_224_in22k_Opset17_timm|Numerics|PASS|
|swinv2_large_window12to16_192to256.ms_in22k_ft_in1k|Numerics|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|Numerics|PASS|
|vit_b_16_Opset18_torch_hub|Numerics|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_relpos_base_patch16_224.sw_in1k|Numerics|PASS|
|vit_relpos_base_patch32_plus_rpn_256.sw_in1k|Numerics|PASS|

