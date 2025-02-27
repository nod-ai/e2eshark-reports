# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.2823|109.0737|-1.2086|-1.1%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.473|109.7362|1.2632|1.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|463.092|463.6887|0.5968|0.13%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.5896|60.5984|0.0088|0.01%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.3379|61.3912|0.0533|0.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|277.5893|239.7181|-37.8712|-13.64%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|65.0404|40.5043|-24.5361|-37.72%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.0781|2.0523|-0.0259|-1.24%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0195|18.9389|-0.0805|-0.42%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1957|7.543|0.3473|4.83%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.1418|26.7562|0.6144|2.35%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.8499|5.1941|0.3443|7.1%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.6462|44.7987|-0.8475|-1.86%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|49.9384|45.6185|-4.3199|-8.65%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.9352|17.6779|0.7427|4.39%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.8183|7.8421|-0.9762|-11.07%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.975|5.0|0.025|0.5%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.4597|32.3153|-0.1444|-0.44%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.187|53.2748|0.0877|0.16%|
|migx_bench_bert-large-uncased_16_384|PASS|regression|69.1234|74.4357|5.3123|7.69%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|24.1552|12.085|-12.0702|-49.97%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3894|12.5009|0.1116|0.9%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.9723|43.5868|23.6145|118.24%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9111|12.934|0.0228|0.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4679|13.4062|-0.0617|-0.46%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.8326|20.6821|-0.1505|-0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.1142|66.101|-0.0132|-0.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.6084|98.7815|1.1731|1.2%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|137.1133|138.7715|1.6582|1.21%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1235|14.9117|-0.2118|-1.4%|
|migx_bench_bert-large-uncased_4_256|Numerics|within tol|16.745|16.5042|-0.2408|-1.44%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.1865|24.9858|-0.2008|-0.8%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.0025|44.1883|25.1858|132.54%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.648|27.2691|0.6211|2.33%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|38.8285|38.8862|0.0578|0.15%|

## 69 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge.fb_in22k_ft_in1k_384|PASS|Numerics|
|convnextv2_base.fcmae_ft_in22k_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_4_256|PASS|Numerics|
|model--MTL-bert-base-uncased-ww-squad--jgammack|PASS|Numerics|
|model--MetaQA--haritzpuerto|PASS|Numerics|
|model--bert-base-cased-finetuned-squad--Seongkyu|PASS|Numerics|
|model--bert-base-cased-finetuned-squad--ss756|PASS|compiled_inference|
|model--bert-base-uncased-finetuned-squad--harveyagraphcore|PASS|Numerics|
|model--bert-finetuned-ner--Hasanmurad|PASS|Numerics|
|model--bert-finetuned-ner--JAS100|PASS|Numerics|
|model--bert-finetuned-ner--amartyobanerjee|PASS|Numerics|
|model--bert-finetuned-ner--mxalmeida|PASS|Numerics|
|model--bert-finetuned-ner--suonbo|PASS|Numerics|
|model--bert-finetuned-ner--tomjam|PASS|Numerics|
|model--bert-finetuned-ner--yixi|PASS|Numerics|
|model--bert-finetuned-squad--Asmit|PASS|Numerics|
|model--bert-finetuned-squad--Dylan1999|PASS|Numerics|
|model--bert-finetuned-squad--OMEGAROFLING|PASS|Numerics|
|model--bert-finetuned-squad--Pranath|PASS|Numerics|
|model--bert-finetuned-squad--TheWayEX|PASS|Numerics|
|model--bert-finetuned-squad--bbbbearczx|PASS|Numerics|
|model--bert-finetuned-squad--jfarmerphd|PASS|Numerics|
|model--bert-finetuned-squad--jmoraes|PASS|Numerics|
|model--bert-finetuned-squad--nickong|PASS|Numerics|
|model--bert-finetuned-squad--spasis|PASS|Numerics|
|model--bert-finetuned-squad-legalbert--Jasu|PASS|Numerics|
|model--bert-large-NER--51la5|PASS|Numerics|
|model--distilbert-base-cased-finetuned-conll03-english--elastic|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-conll03-english--elastic|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--emre|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--gudjonk93|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--kenlevine|PASS|Numerics|
|model--electra-finetuned-cpgqa--hung200504|PASS|Numerics|
|model--finetuned-opt-squad-dataset--choohan|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.2--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.5_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuning-movie-sentiment-model-9000-samples--Manishkalra|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--Hackerino|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--KarimKhalil|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--PeterKh|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--csam|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--monusingh|PASS|compiled_inference|
|model--first_finetuning-sentiment-model-3000-samples--Positroniy|PASS|Numerics|
|model--gpt2_wikitext37_7k_pretrained_iphone_1e4--himanshubeniwal|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--miesnerjacob|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--mxalmeida|PASS|Numerics|
|model--my_awesome_qa_model--satyamverma|PASS|Numerics|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--roberta-base-finetuned-squad--Firat|PASS|Numerics|
|model--roberta-base-finetuned-squad-3--huxxx657|PASS|Numerics|
|model--roberta-base-spanish-squades--IIC|PASS|Numerics|
|model--roberta-large-finetuned-ner--romainlhardy|PASS|Numerics|
|model--roberta-large-synqa-ext--mbartolo|PASS|Numerics|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|Numerics|
|model--sentiment-model-sample--jkhan447|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-16-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--xlm-roberta-base-squad2--deepset|PASS|Numerics|
|model--xlm-roberta-ner-japanese--tsmatz|PASS|Numerics|
|swin_small_patch4_window7_224.ms_in1k|PASS|Numerics|

## 46 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_384.in22k_ft_in22k_in1k|compilation|PASS|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|Numerics|PASS|
|cait_m36_384|compilation|PASS|
|cait_m48_448|compilation|PASS|
|coatnet_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in1k|compilation|PASS|
|convnext_large.fb_in22k_ft_in1k_384|compilation|Numerics|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|compilation|PASS|
|convnext_large_mlp.clip_laion2b_ft_320|compilation|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|compilation|PASS|
|convnextv2_large.fcmae|compilation|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k_384|compilation|PASS|
|crossvit_18_dagger_408|compilation|PASS|
|deit3_base_patch16_384.fb_in1k|compilation|PASS|
|deit3_base_patch16_384.fb_in22k_ft_in1k|compilation|PASS|
|deit3_large_patch16_224.fb_in1k|Numerics|PASS|
|deit_base_distilled_patch16_384.fb_in1k|compilation|Numerics|
|deit_base_patch16_384.fb_in1k|compilation|PASS|
|densenet201|compilation|PASS|
|eva_large_patch14_336.in22k_ft_in22k_in1k|Numerics|PASS|
|maxvit_small_tf_512.in1k|Numerics|PASS|
|migraphx_cadene__dpn92i1|compilation|PASS|
|migraphx_cadene__inceptionv4i16|compilation|PASS|
|migraphx_cadene__resnext101_64x4di1|compilation|PASS|
|migraphx_cadene__resnext101_64x4di16|compilation|PASS|
|migraphx_torchvision__densenet121i32|compilation|PASS|
|migraphx_torchvision__inceptioni32|compilation|PASS|
|migraphx_torchvision__resnet50i1|compilation|PASS|
|migraphx_torchvision__resnet50i64|compilation|PASS|
|migx_bench_bert-large-uncased_32_256|Numerics|PASS|
|model--TinyStories-33M--roneneldan|Numerics|PASS|
|model--bart-large-xsum--facebook|Numerics|PASS|
|model--bert-finetuned-squad--nightlighttw|Numerics|PASS|
|model--bert-finetuned-squad--vsrinivas|Numerics|PASS|
|model--distilbart-xsum-9-6--sshleifer|Numerics|PASS|
|model--marian-finetuned-kde4-cs2sv--ksaml|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--kbalde|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--ornil1|Numerics|PASS|
|model--smol_llama-81M-tied--BEE-spoke-data|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|twins_svt_base|Numerics|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in1k|Numerics|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|

