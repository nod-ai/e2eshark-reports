# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.1399|115.7285|-1.4113|-1.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.7285|114.724|-2.0045|-1.72%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|522.8982|519.3104|-3.5878|-0.69%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.208|67.6791|-1.529|-2.21%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.8649|62.6804|-1.1846|-1.85%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|332.4008|329.2767|-3.1241|-0.94%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.067|35.2523|0.1854|0.53%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.8313|19.3353|-0.4959|-2.5%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0534|5.0375|-0.0159|-0.31%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.3458|29.8702|0.5243|1.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.0094|5.897|-0.1124|-1.87%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0964|6.9401|-0.1563|-2.2%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.6765|27.2688|-0.4077|-1.47%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.0093|4.7728|-0.2365|-4.72%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.2264|40.007|-0.2194|-0.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.7591|46.5727|-0.1864|-0.4%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.5147|16.5864|-0.9282|-5.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.009|8.2507|-0.7583|-8.42%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.9842|17.85|-0.1343|-0.75%|
|migraphx_torchvision__inceptioni1|PASS|regression|4.8879|6.9557|2.0678|42.31%|
|migraphx_torchvision__resnet50i1|PASS|progression|3.7584|3.1513|-0.607|-16.15%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.8119|27.0167|-0.7952|-2.86%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.2676|38.8481|-0.4196|-1.07%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|60.7276|58.6949|-2.0327|-3.35%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2664|12.1564|-0.11|-0.9%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4699|12.6359|0.1659|1.33%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3727|19.4803|0.1075|0.56%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5963|12.786|0.1897|1.51%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4012|19.5501|0.1488|0.77%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.5879|20.3352|-0.2527|-1.23%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8856|37.2196|-0.666|-1.76%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|79.8018|78.3964|-1.4055|-1.76%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|122.3364|120.2772|-2.0592|-1.68%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6311|19.5986|-0.0325|-0.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.0974|20.7298|-0.3676|-1.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.5823|24.3599|-0.2223|-0.9%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.2019|20.9648|-0.2371|-1.12%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1641|27.6317|-0.5324|-1.89%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|36.1435|35.1207|-1.0227|-2.83%|

## 25 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|cait_m36_384|PASS|Numerics|
|cait_s24_224|PASS|Numerics|
|model--TinyStories-33M--roneneldan|PASS|Numerics|
|model--bert-finetuned-ner--jatinshah|PASS|Numerics|
|model--bert-german-ler--elenanereiss|PASS|Numerics|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|PASS|Numerics|
|model--cm_code_clippy--ncoop57|PASS|Numerics|
|model--deberta-v3-base-qa-en--LLukas22|PASS|Numerics|
|model--distilbert-base-NER--51la5|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--DravenTay|PASS|Numerics|
|model--google_electra-base-discriminator_squad--Palak|PASS|Numerics|
|model--llama-wikitext--manu|PASS|Numerics|
|model--microsoft_deberta-large_squad--Palak|PASS|Numerics|
|model--nd-qna--Trisert|PASS|Numerics|
|model--ner_conll2003--ramybaly|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|swinv2_tiny_window16_256.ms_in1k|PASS|Numerics|
|tf_efficientnet_l2.ns_jft_in1k|PASS|Numerics|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch32_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_medium_patch16_gap_384.in12k_ft_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_224.sw_in1k|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|model--m2m100_418M-finetuned-kde4-en-to-pt_BR--danhsf|Numerics|PASS|

