# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|121.0474|108.9742|-12.0732|-9.97%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|134.644|110.0983|-24.5457|-18.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|550.8144|461.3215|-89.4929|-16.25%|
|migraphx_ORT__distilgpt2_1|PASS|progression|71.8091|60.1064|-11.7027|-16.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|65.3546|62.3052|-3.0493|-4.67%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|273.3941|241.291|-32.1031|-11.74%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|180.9054|37.0947|-143.8107|-79.49%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.1414|1.9327|-0.2087|-9.75%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3168|18.9646|-0.3522|-1.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4108|7.1119|-0.2988|-4.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|41.6911|26.66|-15.0311|-36.05%|
|migraphx_mlperf__resnet50_v1|PASS|progression|6.2484|4.8039|-1.4445|-23.12%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|47.9997|43.5713|-4.4284|-9.23%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|54.2057|46.5762|-7.6294|-14.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.3198|18.356|-0.9638|-4.99%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|11.3277|8.4142|-2.9135|-25.72%|
|migraphx_torchvision__inceptioni1|PASS|progression|5.5168|4.893|-0.6238|-11.31%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.3786|32.2583|-1.1203|-3.36%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|55.3859|53.2057|-2.1802|-3.94%|
|migx_bench_bert-large-uncased_16_384|PASS|progression|74.7985|67.7909|-7.0076|-9.37%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|13.0085|12.0817|-0.9268|-7.12%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.99|12.5606|-0.4294|-3.31%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|20.4174|19.2108|-1.2065|-5.91%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|25.8245|12.9503|-12.8742|-49.85%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|73.2962|13.3975|-59.8987|-81.72%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5649|20.9186|-0.6463|-3.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.3544|65.9505|-2.404|-3.52%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|102.7338|97.1365|-5.5973|-5.45%|
|migx_bench_bert-large-uncased_32_384|PASS|progression|145.1572|137.4785|-7.6787|-5.29%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|15.1894|14.4197|-0.7697|-5.07%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.7176|16.9335|-0.7841|-4.43%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|27.4955|25.3645|-2.131|-7.75%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.8128|19.0841|-0.7286|-3.68%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5062|26.5017|-1.0045|-3.65%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|41.9192|39.0315|-2.8877|-6.89%|

## 59 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_base_tf_384.in1k|PASS|Numerics|
|maxvit_base_tf_512.in21k_ft_in1k|PASS|Numerics|
|maxvit_large_tf_384.in21k_ft_in1k|PASS|Numerics|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|PASS|compiled_inference|
|model--bert-base-uncased-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--bert-cased-ner-fcit499--Ahmed87|PASS|Numerics|
|model--bert-engonly-sentiment-test--SiddharthaM|PASS|Numerics|
|model--bert-finetuned-ner--Binaryy|PASS|Numerics|
|model--bert-finetuned-ner--CDRI-Eddy|PASS|Numerics|
|model--bert-finetuned-ner--Laure996|PASS|Numerics|
|model--bert-finetuned-ner--amir36|PASS|Numerics|
|model--bert-finetuned-ner--buehlpa|PASS|Numerics|
|model--bert-finetuned-ner--mholi|PASS|Numerics|
|model--bert-finetuned-squad--Lexie79|PASS|Numerics|
|model--bert-finetuned-squad--MarcusLee|PASS|Numerics|
|model--bert-finetuned-squad--TheWayEX|PASS|Numerics|
|model--bert-finetuned-squad--ZoeDuan|PASS|Numerics|
|model--bert-finetuned-squad--algoprivacy|PASS|Numerics|
|model--bert-finetuned-squad--amartyobanerjee|PASS|Numerics|
|model--bert-finetuned-squad--ankitkupadhyay|PASS|Numerics|
|model--bert-finetuned-squad--apatidar0|PASS|Numerics|
|model--bert-finetuned-squad--jaese|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--sam999|PASS|compiled_inference|
|model--distilcamembert-base-ner--cmarkea|PASS|Numerics|
|model--distilgpt2-stable-diffusion-v2--FredZhang7|PASS|Numerics|
|model--distillbert-base-uncased-fine-tuned-squadv2--monakth|PASS|Numerics|
|model--distilroberta-base-ner-wikiann--philschmid|PASS|Numerics|
|model--financial-summarization-pegasus--human-centered-summarization|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.2--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.5--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--Zahwa|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--bibekitani123|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--federicopascual|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--markt23917|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--rootacess|PASS|Numerics|
|model--mbert-imdb--manirai91|PASS|compiled_inference|
|model--my_awesome_qa_model--Shushant|PASS|Numerics|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|PASS|Numerics|
|model--ner_conll2003--ramybaly|PASS|Numerics|
|model--pegasus-xsum--google|PASS|Numerics|
|model--roberta-l-squadv1.1--vuiseng9|PASS|Numerics|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-large-ner-english--Jean-Baptiste|PASS|Numerics|
|model--smol_llama-81M-tied--BEE-spoke-data|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-1024-finetuned-squad-seed-42--anas-awadalla|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-256-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--spanbert-base-cased-few-shot-k-64-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_large_window12to24_192to384.ms_in22k_ft_in1k|PASS|Numerics|
|tf_efficientnet_b7.ns_jft_in1k|PASS|Numerics|
|tf_efficientnet_b8.ap_in1k|PASS|Numerics|
|xcit_medium_24_p16_384_dist|PASS|Numerics|

## 37 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|flexivit_base.1200ep_in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_small_tf_384.in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_16_384|Numerics|PASS|
|migx_bench_bert-large-uncased_2_128|Numerics|PASS|
|migx_bench_bert-large-uncased_2_256|Numerics|PASS|
|migx_bench_bert-large-uncased_32_384|Numerics|PASS|
|model--Bartlarge--Shubham09|Numerics|PASS|
|model--CodeGen-350M-Multi--xhyi|Numerics|PASS|
|model--bart-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--bart-large-cnn--facebook|Numerics|PASS|
|model--bert-base-finetuned-nli--Jihyun22|Numerics|PASS|
|model--bert-base-multilingual-cased-finetuned-squad--JensH|compiled_inference|PASS|
|model--bert-base-multilingual-cased-finetuned-squad-finetuned-squad--JensH|compiled_inference|PASS|
|model--bert-base-uncased-few-shot-k-512-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-finetuned-squad_v2--seviladiguzel|Numerics|PASS|
|model--bert-base-uncased-squad2--deepset|Numerics|PASS|
|model--bert-finetuned-ner--AIventurer|Numerics|PASS|
|model--bert-finetuned-ner--abx|Numerics|PASS|
|model--bert-finetuned-ner--alwaysgetbetter|Numerics|PASS|
|model--bert-finetuned-ner--batya66|Numerics|PASS|
|model--distilbert-base-cased-finetuned-conll03-english--elastic|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--FabianWillner|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--huggingliang|Numerics|PASS|
|model--distilroberta-base-ner-conll2003--philschmid|Numerics|PASS|
|model--finetuned-base_base--muhtasham|Numerics|PASS|
|model--finetuned-opt-squad-dataset--choohan|Numerics|PASS|
|model--finetuned-sentiment-analysis-model--federicopascual|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--bishalbaaniya|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--kbalde|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr3--Ghost1|Numerics|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|PASS|
|regnety_640.seer|Numerics|PASS|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|Numerics|PASS|

