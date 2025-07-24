# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|648.8072|111.7536|-537.0536|-82.78%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|129.2595|110.0611|-19.1984|-14.85%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|1274.6361|520.7384|-753.8977|-59.15%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.1733|67.8643|-0.309|-0.45%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|62.56|76.6943|14.1343|22.59%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|293.7102|273.4493|-20.2609|-6.9%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.5099|37.2284|0.7185|1.97%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2929|19.1132|-0.1797|-0.93%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4915|3.4384|-0.0531|-1.52%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.2984|20.1891|-0.1093|-0.54%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|4.4888|4.1779|-0.3108|-6.92%|
|migraphx_huggingface-transformers__bert_mrpc8|Numerics|within tol|7.3274|7.0264|-0.3009|-4.11%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.9016|26.6557|-0.246|-0.91%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.056|14.1603|0.1043|0.74%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|42.6121|45.5975|2.9854|7.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|104.0652|103.7222|-0.343|-0.33%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.1938|20.2724|0.0787|0.39%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|13.3971|9.7465|-3.6507|-27.25%|
|migraphx_torchvision__densenet121i32|PASS|progression|14.6091|13.7894|-0.8197|-5.61%|
|migraphx_torchvision__inceptioni1|PASS|regression|3.0793|3.3721|0.2927|9.51%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0884|2.0338|-0.0545|-2.61%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.7212|26.2826|-0.4386|-1.64%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|40.5316|38.3231|-2.2085|-5.45%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.2469|57.5115|-1.7354|-2.93%|
|migx_bench_bert-large-uncased_1_128|Numerics|within tol|12.8806|12.6422|-0.2384|-1.85%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|15.6475|12.7836|-2.8639|-18.3%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|22.35|19.3214|-3.0286|-13.55%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|13.7116|12.9574|-0.7543|-5.5%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.0318|19.7141|0.6823|3.59%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|23.2538|20.944|-2.3099|-9.93%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.8773|37.0124|-1.865|-4.8%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.3753|71.7264|-0.6489|-0.9%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|115.1253|113.8483|-1.277|-1.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4888|19.1801|-0.3086|-1.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.4684|20.446|-0.0224|-0.11%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.5882|23.4064|-0.1818|-0.77%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.4265|20.4359|0.0095|0.05%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5378|27.8473|1.3095|4.93%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.1014|33.5772|-0.5242|-1.54%|

## 21 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset16_transformers|PASS|Numerics|
|deit3_large_patch16_384_in21ft1k_Opset17_timm|PASS|Numerics|
|deit_base_patch16_224.fb_in1k|PASS|Numerics|
|distilbert_Opset18_transformers|PASS|Numerics|
|gpt2lmhead_Opset16_transformers|PASS|Numerics|
|maxvit_base_tf_224.in1k|PASS|Numerics|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|Numerics|
|migx_bench_bert-large-uncased_1_128|PASS|Numerics|
|model--bert-engonly-sentiment-test--SiddharthaM|PASS|Numerics|
|model--bert-large-NER--51la5|PASS|Numerics|
|model--cm_code_clippy--ncoop57|PASS|Numerics|
|model--hebrew_poetry-gpt_neo-small--Norod78|PASS|Numerics|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|PASS|Numerics|
|pit_b_distilled_224_Opset18_timm|PASS|Numerics|
|swin_large_patch4_window7_224_in22k_Opset17_timm|PASS|Numerics|
|swinv2_large_window12to16_192to256.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|PASS|Numerics|
|vit_b_16_Opset18_torch_hub|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_relpos_base_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_base_patch32_plus_rpn_256.sw_in1k|PASS|Numerics|

## 15 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_small_in22k_Opset17_timm|Numerics|PASS|
|gluon_resnet152_v1c_Opset17_timm|Numerics|PASS|
|model--bert-cased-ner-fcit499--Ahmed87|Numerics|PASS|
|model--dynamic_tinybert--Intel|Numerics|PASS|
|model--enlm-roberta-imdb--manirai91|Numerics|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|Numerics|PASS|
|mt5encoder_Opset17_transformers|Numerics|PASS|
|pit_s_distilled_224_Opset17_timm|Numerics|PASS|
|resnetrs101_Opset17_timm|Numerics|PASS|
|roformer_Opset16_transformers|Numerics|PASS|
|swinv2_large_window12_192_22k_Opset17_timm|Numerics|PASS|
|tf_efficientnet_l2_ns_475_Opset17_timm|Numerics|PASS|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|Numerics|PASS|
|vit_large_patch16_224_Opset18_timm|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|

