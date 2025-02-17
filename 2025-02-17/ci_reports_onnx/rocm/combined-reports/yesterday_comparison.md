# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|109.4413|134.238|24.7967|22.66%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.7713|116.0176|4.2463|3.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|475.3079|478.0184|2.7105|0.57%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|62.3902|61.3621|-1.0281|-1.65%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.8804|63.7475|1.867|3.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.2496|268.0215|0.7719|0.29%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.012|35.8198|1.8079|5.32%|
|migraphx_agentmodel__AgentModel|Numerics|regression|2.0147|2.5561|0.5415|26.88%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8949|19.2186|0.3237|1.71%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.1048|7.4783|0.3735|5.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.9793|41.7782|14.7989|54.85%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.9334|4.9059|-0.0274|-0.56%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|43.7894|55.4111|11.6216|26.54%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|45.256|54.522|9.2659|20.47%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.0955|17.5895|0.494|2.89%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.2495|7.3745|-0.875|-10.61%|
|migraphx_torchvision__inceptioni1|PASS|regression|4.9497|5.3427|0.393|7.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.0611|31.7802|-0.281|-0.88%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.4481|53.9687|0.5206|0.97%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.7879|70.0528|-0.7352|-1.04%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0914|12.0934|0.002|0.02%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7014|12.4627|-0.2387|-1.88%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4101|19.1766|-0.2335|-1.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.1048|12.7505|-0.3544|-2.7%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4419|13.5529|0.111|0.83%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7365|21.2479|0.5113|2.47%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.8711|66.4028|0.5317|0.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|99.2366|98.7194|-0.5172|-0.52%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|140.4951|139.4721|-1.023|-0.73%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3499|14.3996|0.0497|0.35%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7805|16.607|-0.1735|-1.03%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.9288|25.7398|-0.189|-0.73%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.087|19.1|0.013|0.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.4147|26.5609|0.1462|0.55%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.2503|39.3272|0.077|0.2%|

## No Regressions Found

## 108 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_ORT__distilgpt2_1|Numerics|PASS|
|model--125M_GPTneo_reward_base--Myashka|Numerics|PASS|
|model--CodeGen-350M-Multi--xhyi|Numerics|PASS|
|model--GPyT--Sentdex|Numerics|PASS|
|model--Jasmine-350M--UBC-NLP|Numerics|PASS|
|model--PT_GPTNEO125_ATG--xhyi|Numerics|PASS|
|model--TinyStories-1Layer-21M--roneneldan|Numerics|PASS|
|model--TinyStories-2Layers-33M--roneneldan|Numerics|PASS|
|model--TinyStories-33M--roneneldan|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--ArBert|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--Jorgeutd|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--Firat|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--bdickson|Numerics|PASS|
|model--albert-base-v2-imdb--textattack|Numerics|PASS|
|model--albert-base-v2-imdb-calssification--XSY|Numerics|PASS|
|model--albert-base-v2-squad2--twmkn9|Numerics|PASS|
|model--albert-base-v2-squad_v2--squirro|Numerics|PASS|
|model--albert-base-v2_squad--Palak|Numerics|PASS|
|model--albert-large-v2_ner_conll2003--Gladiator|Numerics|PASS|
|model--albert-large-v2_ner_wikiann--Gladiator|Numerics|PASS|
|model--albert-large-v2_squad--Palak|Numerics|PASS|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|Numerics|PASS|
|model--cm_code_clippy--ncoop57|Numerics|PASS|
|model--codegen-350M-mono--Salesforce|Numerics|PASS|
|model--codegen-350M-mono-4bit-qlora--iamtarun|Numerics|PASS|
|model--distilgpt2-sd--aabidk|Numerics|PASS|
|model--distilgpt2-stable-diffusion--FredZhang7|Numerics|PASS|
|model--distilgpt2-stable-diffusion-v2--FredZhang7|Numerics|PASS|
|model--distilgpt2-wikitext2--Intel|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs6--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedFalse_epochs0--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedTrue--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedTrue_epochs0--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_distilgpt2_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs2--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.05--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.2--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.5--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.5_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.8--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0005_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.05--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.05_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse_epochs30--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.5--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.5_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.8--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedFalse_epochs1--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0005_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.001_pretrainedTrue--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.05--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.0_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.5--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.8--yuhuizhang|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--gpt2--openai-community|Numerics|PASS|
|model--gpt2-650k-stable-diffusion-prompt-generator--Ar4ikov|Numerics|PASS|
|model--gpt2-alpaca-gpt4--vicgalle|Numerics|PASS|
|model--gpt2-finetuning-sentiment-model-3000-samples--LYTinn|Numerics|PASS|
|model--gpt2-imdb-sentiment-classifier--mnoukhov|Numerics|PASS|
|model--gpt2-wikitext103--himanshubeniwal|Numerics|PASS|
|model--gpt2_wikitext37_7k_pretrained_iphone_1e4--himanshubeniwal|Numerics|PASS|
|model--hebrew_poetry-gpt_neo-small--Norod78|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--megatron-gpt2-345m--robowaifudev|Numerics|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|Numerics|PASS|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|Numerics|PASS|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|Numerics|PASS|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|Numerics|PASS|
|model--tiny-random-GPTNeoForSequenceClassification--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|PASS|
|model--wikitext-ds--mahmoudNG|Numerics|PASS|

