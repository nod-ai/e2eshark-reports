# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|108.9742|110.2351|1.2609|1.16%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.0983|110.9124|0.8141|0.74%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|461.3215|474.3757|13.0542|2.83%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.1064|61.2366|1.1302|1.88%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.3052|62.9234|0.6181|0.99%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|241.291|246.2922|5.0012|2.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.0947|36.3341|-0.7607|-2.05%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.9327|2.0264|0.0936|4.84%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9646|18.9587|-0.0059|-0.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.1119|7.868|0.756|10.63%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.66|26.6891|0.0291|0.11%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8039|4.7729|-0.031|-0.64%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.5713|43.9918|0.4205|0.97%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.5762|47.4587|0.8824|1.89%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.356|18.1472|-0.2087|-1.14%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.4142|7.8135|-0.6007|-7.14%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.893|4.8831|-0.01|-0.2%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.2583|33.2699|1.0116|3.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.2057|54.4256|1.2199|2.29%|
|migx_bench_bert-large-uncased_16_384|PASS|regression|67.7909|71.2485|3.4576|5.1%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|12.0817|28.6102|16.5285|136.81%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5606|12.3225|-0.238|-1.89%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2108|19.269|0.0582|0.3%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9503|12.9017|-0.0486|-0.38%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3975|13.7607|0.3632|2.71%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.9186|21.0129|0.0943|0.45%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.9505|67.9815|2.031|3.08%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.1365|100.3621|3.2256|3.32%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|137.4785|141.3428|3.8643|2.81%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4197|14.7623|0.3426|2.38%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.9335|16.8574|-0.076|-0.45%|
|migx_bench_bert-large-uncased_4_384|Numerics|within tol|25.3645|25.5986|0.2342|0.92%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.0841|19.5262|0.4421|2.32%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5017|27.3496|0.8479|3.2%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.0315|39.9742|0.9427|2.42%|

## 16 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large.fb_in1k|PASS|Numerics|
|convnext_small.fb_in22k_ft_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_4_384|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--bert-large-uncased-en-ner--n6ai|PASS|Numerics|
|model--bert-large-uncased-finetuned-ner--Jorgeutd|PASS|Numerics|
|model--bert-large-uncased-whole-word-masking-squad2--deepset|PASS|Numerics|
|model--camembert-base-squadFR-fquad-piaf--etalab-ia|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--aaraki|PASS|Numerics|
|model--expanded-multilingual-ner--gamzenurmadan|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--aneeshmb02|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--kosec39|PASS|Numerics|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|PASS|Numerics|
|model--roberta-base-finetuned-ner--dominiqueblok|PASS|Numerics|
|swin_s3_small_224.ms_in1k|PASS|Numerics|
|xcit_small_24_p16_224_dist|PASS|Numerics|

## 58 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|maxvit_base_tf_384.in1k|Numerics|PASS|
|maxvit_base_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_large_tf_384.in21k_ft_in1k|Numerics|PASS|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|compiled_inference|PASS|
|model--bert-cased-ner-fcit499--Ahmed87|Numerics|PASS|
|model--bert-engonly-sentiment-test--SiddharthaM|Numerics|PASS|
|model--bert-finetuned-ner--Binaryy|Numerics|PASS|
|model--bert-finetuned-ner--CDRI-Eddy|Numerics|PASS|
|model--bert-finetuned-ner--Laure996|Numerics|PASS|
|model--bert-finetuned-ner--amir36|Numerics|PASS|
|model--bert-finetuned-ner--buehlpa|Numerics|PASS|
|model--bert-finetuned-ner--mholi|Numerics|PASS|
|model--bert-finetuned-squad--Lexie79|Numerics|PASS|
|model--bert-finetuned-squad--MarcusLee|Numerics|PASS|
|model--bert-finetuned-squad--TheWayEX|Numerics|PASS|
|model--bert-finetuned-squad--ZoeDuan|Numerics|PASS|
|model--bert-finetuned-squad--algoprivacy|Numerics|PASS|
|model--bert-finetuned-squad--amartyobanerjee|Numerics|PASS|
|model--bert-finetuned-squad--ankitkupadhyay|Numerics|PASS|
|model--bert-finetuned-squad--apatidar0|Numerics|PASS|
|model--bert-finetuned-squad--jaese|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--sam999|compiled_inference|PASS|
|model--distilcamembert-base-ner--cmarkea|Numerics|PASS|
|model--distilgpt2-stable-diffusion-v2--FredZhang7|Numerics|PASS|
|model--distillbert-base-uncased-fine-tuned-squadv2--monakth|Numerics|PASS|
|model--distilroberta-base-ner-wikiann--philschmid|Numerics|PASS|
|model--financial-summarization-pegasus--human-centered-summarization|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.5--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--Zahwa|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--bibekitani123|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--federicopascual|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--markt23917|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--rootacess|Numerics|PASS|
|model--mbert-imdb--manirai91|compiled_inference|PASS|
|model--my_awesome_qa_model--Shushant|Numerics|PASS|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|Numerics|PASS|
|model--ner_conll2003--ramybaly|Numerics|PASS|
|model--pegasus-xsum--google|Numerics|PASS|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|PASS|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large-ner-english--Jean-Baptiste|Numerics|PASS|
|model--smol_llama-81M-tied--BEE-spoke-data|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-1024-finetuned-squad-seed-42--anas-awadalla|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-256-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-64-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|Numerics|PASS|
|swinv2_large_window12to24_192to384.ms_in22k_ft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b8.ap_in1k|Numerics|PASS|
|xcit_medium_24_p16_384_dist|Numerics|PASS|

