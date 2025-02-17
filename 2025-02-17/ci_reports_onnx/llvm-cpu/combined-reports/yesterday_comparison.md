# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|88.2391|1257.9933|1169.7542|1325.66%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.6325|947.1005|860.468|993.24%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|269.5736|559.8424|290.2688|107.68%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.1439|632.1863|602.0424|1997.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|203.4828|88.0503|-115.4325|-56.73%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|696.3213|1585.5022|889.1809|127.7%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.7625|39.4468|0.6843|1.77%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.0555|1.9899|0.9345|88.54%|
|migraphx_bert__bert-large-uncased|PASS|regression|782.3532|1327.9508|545.5976|69.74%|
|migraphx_cadene__dpn92i1|PASS|regression|164.3462|652.7317|488.3855|297.17%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5560.2588|5768.7073|208.4485|3.75%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|318.1064|353.5471|35.4407|11.14%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5952.7327|5009.3722|-943.3605|-15.85%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|403.3501|825.8016|422.4515|104.74%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|500.3844|2355.7245|1855.3401|370.78%|
|migraphx_mlperf__resnet50_v1|PASS|progression|101.5061|96.0867|-5.4195|-5.34%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.5183|36.1796|4.6613|14.79%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.4899|628.3482|448.8583|250.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.7426|78.4655|-3.2771|-4.01%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|45.0965|41.6088|-3.4877|-7.73%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1483.8049|1490.5608|6.7559|0.46%|
|migraphx_torchvision__inceptioni1|PASS|regression|203.4551|557.7054|354.2503|174.12%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5723.5947|5731.4828|7.8881|0.14%|
|migraphx_torchvision__resnet50i1|PASS|regression|97.7091|127.0706|29.3616|30.05%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5542.5144|5384.7119|-157.8025|-2.85%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2633.716|2589.4483|-44.2677|-1.68%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4097.3719|4292.9136|195.5417|4.77%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6218.6971|5600.3251|-618.372|-9.94%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.3988|158.3179|-30.0809|-15.97%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|264.8086|275.1554|10.3467|3.91%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|395.9095|396.6643|0.7549|0.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|398.6322|404.6734|6.0412|1.52%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|664.6398|583.1809|-81.4588|-12.26%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|879.0534|826.5659|-52.4875|-5.97%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5539.4995|5104.6245|-434.875|-7.85%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8926.18|8220.8697|-705.3103|-7.9%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11900.4628|11544.3794|-356.0834|-2.99%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|725.8386|730.1665|4.3279|0.6%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1094.5243|1121.2258|26.7015|2.44%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1531.3067|1546.6103|15.3036|1.0%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1288.5279|1286.096|-2.4319|-0.19%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2100.3311|2418.3065|317.9755|15.14%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3077.6193|2911.2881|-166.3312|-5.4%|

## No Regressions Found

## 126 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_ORT__distilgpt2_1|Numerics|PASS|
|model--125M_GPTneo_reward_base--Myashka|Numerics|PASS|
|model--CodeGen-350M-Multi--xhyi|Numerics|PASS|
|model--GPyT--Sentdex|Numerics|PASS|
|model--Jasmine-350M--UBC-NLP|Numerics|PASS|
|model--PT_GPTNEO125_ATG--xhyi|Numerics|PASS|
|model--TinyStories-1Layer-21M--roneneldan|Numerics|PASS|
|model--TinyStories-1M--roneneldan|Numerics|PASS|
|model--TinyStories-2Layers-33M--roneneldan|Numerics|PASS|
|model--TinyStories-33M--roneneldan|Numerics|PASS|
|model--TinyStories-3M--roneneldan|Numerics|PASS|
|model--TinyStories-8M--roneneldan|Numerics|PASS|
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
|model--ia-detection-tiny-random-gptj--arincon|Numerics|PASS|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--mT5_multilingual_XLSum--csebuetnlp|Numerics|PASS|
|model--megatron-gpt2-345m--robowaifudev|Numerics|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|Numerics|PASS|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|Numerics|PASS|
|model--my_awesome_gptj_model--anandshende|Numerics|PASS|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|Numerics|PASS|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|Numerics|PASS|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|Numerics|PASS|
|model--tiny-gpt2--taufeeque|Numerics|PASS|
|model--tiny-gpt2-magicprompt--pszemraj|Numerics|PASS|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-GPTNeoForSequenceClassification--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|PASS|
|model--wikitext-ds--mahmoudNG|Numerics|PASS|

