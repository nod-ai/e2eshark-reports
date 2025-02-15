# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.8055|111.496|0.6905|0.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.4396|113.1232|2.6837|2.43%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|475.9645|472.3042|-3.6603|-0.77%|
|migraphx_ORT__distilgpt2_1|Numerics|within tol|59.7175|61.9906|2.2731|3.81%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|65.1242|63.7032|-1.4209|-2.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.3051|271.3102|-1.9949|-0.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1093|34.6067|0.4973|1.46%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0136|18.912|-0.1016|-0.53%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2484|7.1524|-0.096|-1.33%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.2489|26.3869|0.138|0.53%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2237|5.3531|0.1294|2.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.7191|43.7184|-0.0007|-0.0%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.9665|48.202|1.2355|2.63%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.5505|17.801|-0.7495|-4.04%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.3029|8.5003|-0.8025|-8.63%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8899|4.8897|-0.0002|-0.0%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.8203|32.6651|-0.1551|-0.47%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|57.8731|54.8144|-3.0587|-5.29%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.5504|72.2432|-0.3072|-0.42%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0646|12.0043|-0.0603|-0.5%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4202|12.4318|0.0115|0.09%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.1856|19.3728|0.1872|0.98%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7913|12.9852|0.194|1.52%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4941|13.3771|-0.117|-0.87%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0018|21.0326|0.0309|0.15%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.1018|67.7778|-0.324|-0.48%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|101.5628|101.3853|-0.1775|-0.17%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|143.2972|143.2587|-0.0385|-0.03%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3931|14.5902|0.1971|1.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.4591|16.8728|-0.5863|-3.36%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.3859|26.4432|0.0573|0.22%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1202|19.7336|-0.3866|-1.92%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.1946|27.1239|-0.0707|-0.26%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.3803|40.367|-0.0133|-0.03%|

## 121 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_ORT__distilgpt2_1|PASS|Numerics|
|model--125M_GPTneo_reward_base--Myashka|PASS|Numerics|
|model--CodeGen-350M-Multi--xhyi|PASS|Numerics|
|model--GPyT--Sentdex|PASS|Numerics|
|model--Jasmine-350M--UBC-NLP|PASS|Numerics|
|model--PT_GPTNEO125_ATG--xhyi|PASS|Numerics|
|model--TinyStories-1Layer-21M--roneneldan|PASS|Numerics|
|model--TinyStories-2Layers-33M--roneneldan|PASS|Numerics|
|model--TinyStories-33M--roneneldan|PASS|Numerics|
|model--albert-base-v2-finetuned-ner--ArBert|PASS|Numerics|
|model--albert-base-v2-finetuned-ner--Jorgeutd|PASS|Numerics|
|model--albert-base-v2-finetuned-squad--Firat|PASS|Numerics|
|model--albert-base-v2-finetuned-squad--bdickson|PASS|Numerics|
|model--albert-base-v2-imdb--textattack|PASS|Numerics|
|model--albert-base-v2-imdb-calssification--XSY|PASS|Numerics|
|model--albert-base-v2-squad2--twmkn9|PASS|Numerics|
|model--albert-base-v2-squad_v2--squirro|PASS|Numerics|
|model--albert-base-v2_squad--Palak|PASS|Numerics|
|model--albert-large-v2_ner_conll2003--Gladiator|PASS|Numerics|
|model--albert-large-v2_ner_wikiann--Gladiator|PASS|Numerics|
|model--albert-large-v2_squad--Palak|PASS|Numerics|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|PASS|Numerics|
|model--cm_code_clippy--ncoop57|PASS|Numerics|
|model--codegen-350M-mono--Salesforce|PASS|Numerics|
|model--codegen-350M-mono-4bit-qlora--iamtarun|PASS|Numerics|
|model--deberta-italian-question-answering--osiria|PASS|Numerics|
|model--deberta-v3-base-qa-en--LLukas22|PASS|Numerics|
|model--deberta-v3-base-squad2--deepset|PASS|Numerics|
|model--deberta-v3-base-squad2--navteca|PASS|Numerics|
|model--deberta-v3-base__sst2__all-train--SetFit|PASS|Numerics|
|model--deberta-v3-large-squad2--deepset|PASS|Numerics|
|model--deberta-v3-large-squad2--sjrhuschlee|PASS|Numerics|
|model--deberta-v3-xsmall-squad2--nlpconnect|PASS|Numerics|
|model--deberta_squadnewsqa--sophiebottani|PASS|Numerics|
|model--distilgpt2-sd--aabidk|PASS|Numerics|
|model--distilgpt2-stable-diffusion--FredZhang7|PASS|Numerics|
|model--distilgpt2-stable-diffusion-v2--FredZhang7|PASS|Numerics|
|model--distilgpt2-wikitext2--Intel|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs6--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedFalse_epochs0--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedTrue--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedTrue_epochs0--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_distilgpt2_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs2--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.01--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.05--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.2--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.5--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.5_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.8--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0005_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.05--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.05_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse_epochs30--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.2--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.5--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.5_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.8--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2-medium_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedFalse_epochs1--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0005_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.001_pretrainedTrue--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.05--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.5--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.8--yuhuizhang|PASS|Numerics|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|PASS|Numerics|
|model--flan-t5-large-samsum--oguuzhansahin|PASS|Numerics|
|model--gpt2--openai-community|PASS|Numerics|
|model--gpt2-650k-stable-diffusion-prompt-generator--Ar4ikov|PASS|Numerics|
|model--gpt2-alpaca-gpt4--vicgalle|PASS|Numerics|
|model--gpt2-finetuning-sentiment-model-3000-samples--LYTinn|PASS|Numerics|
|model--gpt2-imdb-sentiment-classifier--mnoukhov|PASS|Numerics|
|model--gpt2-wikitext103--himanshubeniwal|PASS|Numerics|
|model--gpt2_wikitext37_7k_pretrained_iphone_1e4--himanshubeniwal|PASS|Numerics|
|model--hebrew_poetry-gpt_neo-small--Norod78|PASS|Numerics|
|model--mT5-base-HunSum-1--SZTAKI-HLT|PASS|Numerics|
|model--mdeberta-v3-base-squad2--sjrhuschlee|PASS|Numerics|
|model--megatron-gpt2-345m--robowaifudev|PASS|Numerics|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|PASS|Numerics|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|PASS|Numerics|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|PASS|Numerics|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|PASS|Numerics|
|model--outputs--ankitkupadhyay|PASS|Numerics|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|PASS|Numerics|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|PASS|Numerics|
|model--tiny-random-GPTNeoForSequenceClassification--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|PASS|Numerics|
|model--wikitext-ds--mahmoudNG|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_agentmodel__AgentModel|compilation|Numerics|
|model--roberta_shared_bbc_xsum--patrickvonplaten|Numerics|PASS|

