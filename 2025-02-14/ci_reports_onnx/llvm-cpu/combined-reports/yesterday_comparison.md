# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|107.9024|84.5843|-23.318|-21.61%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.3373|88.7985|0.4612|0.52%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|254.1094|261.2007|7.0913|2.79%|
|migraphx_ORT__distilgpt2_1|Numerics|within tol|30.2544|29.434|-0.8204|-2.71%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|93.9782|84.4315|-9.5467|-10.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|1220.6149|278.3343|-942.2805|-77.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.9261|46.6372|6.7111|16.81%|
|migraphx_bert__bert-large-uncased|PASS|progression|413.0928|372.8688|-40.224|-9.74%|
|migraphx_cadene__dpn92i1|PASS|regression|168.1157|207.7378|39.6222|23.57%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5573.6152|5594.7977|21.1825|0.38%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.7709|317.9216|2.1508|0.68%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5544.1129|5230.7051|-313.4078|-5.65%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.108|399.7155|0.6075|0.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|888.3055|428.0044|-460.3011|-51.82%|
|migraphx_mlperf__resnet50_v1|PASS|progression|271.6774|98.802|-172.8754|-63.63%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|44.2754|32.0511|-12.2242|-27.61%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.8094|181.0749|-0.7344|-0.4%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.1393|78.3505|-2.7887|-3.44%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.21|44.1744|3.9645|9.86%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1455.4684|1485.1102|29.6418|2.04%|
|migraphx_torchvision__inceptioni1|PASS|progression|234.6354|207.4548|-27.1807|-11.58%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5816.4497|5724.7372|-91.7125|-1.58%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.7126|89.9482|5.2356|6.18%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5485.6705|5467.1357|-18.5348|-0.34%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2530.3166|2633.9032|103.5866|4.09%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4122.3622|4216.7174|94.3552|2.29%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5909.3393|5915.0853|5.746|0.1%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|159.8075|165.0598|5.2523|3.29%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|261.9293|293.3155|31.3862|11.98%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|388.7546|402.4843|13.7297|3.53%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|443.2074|434.6106|-8.5968|-1.94%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|602.1995|663.1766|60.9771|10.13%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.496|820.5433|10.0473|1.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5080.4809|5086.4067|5.9258|0.12%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8981.1545|8259.0183|-722.1362|-8.04%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11437.1269|11567.6343|130.5074|1.14%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|708.8474|875.1495|166.3021|23.46%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1085.742|1226.1955|140.4535|12.94%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1553.2269|2005.1393|451.9125|29.1%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1336.9308|1343.7191|6.7882|0.51%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2107.7603|2099.6976|-8.0627|-0.38%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3181.5787|3098.3795|-83.1992|-2.62%|

## 140 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_ORT__distilgpt2_1|PASS|Numerics|
|model--125M_GPTneo_reward_base--Myashka|PASS|Numerics|
|model--CodeGen-350M-Multi--xhyi|PASS|Numerics|
|model--GPyT--Sentdex|PASS|Numerics|
|model--Jasmine-350M--UBC-NLP|PASS|Numerics|
|model--PT_GPTNEO125_ATG--xhyi|PASS|Numerics|
|model--TinyStories-1Layer-21M--roneneldan|PASS|Numerics|
|model--TinyStories-1M--roneneldan|PASS|Numerics|
|model--TinyStories-2Layers-33M--roneneldan|PASS|Numerics|
|model--TinyStories-33M--roneneldan|PASS|Numerics|
|model--TinyStories-3M--roneneldan|PASS|Numerics|
|model--TinyStories-8M--roneneldan|PASS|Numerics|
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
|model--ia-detection-tiny-random-gptj--arincon|PASS|Numerics|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|PASS|Numerics|
|model--mT5-base-HunSum-1--SZTAKI-HLT|PASS|Numerics|
|model--mT5_multilingual_XLSum--csebuetnlp|PASS|Numerics|
|model--mdeberta-v3-base-squad2--sjrhuschlee|PASS|Numerics|
|model--megatron-gpt2-345m--robowaifudev|PASS|Numerics|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|PASS|Numerics|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|PASS|Numerics|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|PASS|Numerics|
|model--my_awesome_gptj_model--anandshende|PASS|Numerics|
|model--neo-125m-wills-loss-function-by-tr--Jellywibble|PASS|Numerics|
|model--outputs--ankitkupadhyay|PASS|Numerics|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|PASS|Numerics|
|model--pegasus-large-booksum--cnicu|PASS|Numerics|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|PASS|Numerics|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|PASS|Numerics|
|model--tiny-gpt2--taufeeque|PASS|Numerics|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|Numerics|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-GPTNeoForSequenceClassification--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|PASS|Numerics|
|model--wikitext-ds--mahmoudNG|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_agentmodel__AgentModel|compilation|Numerics|

