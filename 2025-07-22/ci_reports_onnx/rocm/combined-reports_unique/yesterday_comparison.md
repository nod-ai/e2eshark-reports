# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.4364|112.4615|2.0251|1.83%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.6843|111.9553|3.271|3.01%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|509.9542|1051.6694|541.7152|106.23%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.6229|67.4808|-0.142|-0.21%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.7691|63.7039|0.9348|1.49%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|271.2825|271.167|-0.1155|-0.04%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.6878|36.0265|0.3387|0.95%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1829|19.1719|-0.011|-0.06%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5661|3.5013|-0.0648|-1.82%|
|migraphx_cadene__inceptionv4i16|PASS|regression|20.5276|90.0738|69.5462|338.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2104|4.2129|0.0024|0.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0898|7.3267|0.2369|3.34%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.3157|25.9853|-0.3304|-1.26%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1299|14.2472|0.1174|0.83%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.5125|45.9773|0.4648|1.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|105.4351|105.4887|0.0536|0.05%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.8971|18.3698|-0.5274|-2.79%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.0631|9.93|1.8669|23.15%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.7794|14.0264|0.247|1.79%|
|migraphx_torchvision__inceptioni1|PASS|regression|3.0446|3.2646|0.22|7.22%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0487|2.0206|-0.0281|-1.37%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.1751|26.2166|0.0415|0.16%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|38.8353|41.8107|2.9755|7.66%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.752|59.1589|1.4068|2.44%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5539|12.6015|0.0476|0.38%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.8211|39.4486|26.6275|207.68%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3459|20.0159|0.67|3.46%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.874|13.3785|0.5045|3.92%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3226|19.0127|-0.3099|-1.6%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|19.8677|21.0413|1.1736|5.91%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|38.027|41.2818|3.2549|8.56%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|71.7482|84.4984|12.7502|17.77%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|114.3128|114.8031|0.4903|0.43%|
|migx_bench_bert-large-uncased_4_128|Numerics|regression|19.4789|20.8558|1.3769|7.07%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|20.1948|21.4494|1.2547|6.21%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|23.5217|27.1995|3.6778|15.64%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|20.3151|28.0199|7.7048|37.93%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.6056|27.4132|0.8076|3.04%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|33.9335|46.639|12.7054|37.44%|

## 23 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_base.clip_laion2b_augreg_ft_in1k|PASS|Numerics|
|crossvit_18_240_Opset16_timm|PASS|Numerics|
|deit_base_distilled_patch16_384_Opset18_timm|PASS|Numerics|
|maxxvit_rmlp_small_rw_256.sw_in1k|PASS|Numerics|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|Numerics|
|migx_bench_bert-large-uncased_4_128|PASS|Numerics|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|PASS|Numerics|
|model--nbailab-base-ner-scandi--saattrupdan|PASS|Numerics|
|model--ner-bert-base-cased-pt-lenerbr--pierreguillou|PASS|Numerics|
|model--pythia-70m-toxicity-model--skrishna|PASS|Numerics|
|model--roberta-base-finetuned-mbti-0901--GItaf|PASS|Numerics|
|model--sberbank-rubert-base-collection3--viktoroo|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|openaigpt_Opset16_transformers|PASS|Numerics|
|opt_Opset18_transformers|PASS|Numerics|
|pit_s_224_Opset18_timm|PASS|Numerics|
|pit_xs_224|PASS|Numerics|
|pit_xs_224_Opset16_timm|PASS|Numerics|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|switchtransformersencoder_Opset16_transformers|PASS|Numerics|
|tf_efficientnetv2_l_in21ft1k_Opset17_timm|PASS|Numerics|
|twins_svt_large_Opset16_timm|PASS|Numerics|
|xlmroberta_Opset17_transformers|PASS|Numerics|

## 11 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnext_nano_rw_224.sw_in1k|Numerics|PASS|
|deit_base_patch16_384_Opset17_timm|Numerics|PASS|
|efficientnetv2_rw_m_Opset16_timm|Numerics|PASS|
|maxvit_base_tf_224.in1k|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--opt-350m--facebook|Numerics|PASS|
|mvitv2_large|Numerics|PASS|
|resmlp_36_224_Opset17_timm|Numerics|PASS|
|swinv2_small_window16_256_Opset17_timm|Numerics|PASS|
|wide_resnet101_2_Opset17_torch_hub|Numerics|PASS|
|xcit_small_24_p8_224_Opset18_timm|Numerics|PASS|

