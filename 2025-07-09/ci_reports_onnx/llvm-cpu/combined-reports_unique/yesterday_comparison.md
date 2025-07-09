# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.9615|377.9094|8.9479|2.43%|
|migraphx_cadene__dpn92i1|PASS|progression|193.6728|171.701|-21.9718|-11.34%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5205.1932|5235.3026|30.1094|0.58%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.8818|314.1395|-3.7423|-1.18%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|414.67|442.3681|27.6981|6.68%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|600.141|428.2654|-171.8756|-28.64%|
|migraphx_mlperf__resnet50_v1|PASS|progression|109.7962|93.2524|-16.5438|-15.07%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|57.2623|59.3014|2.0391|3.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|208.2962|244.8849|36.5886|17.57%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|61.0726|78.7737|17.7011|28.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|19.8711|21.0279|1.1567|5.82%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1460.7213|1517.1649|56.4436|3.86%|
|migraphx_torchvision__inceptioni1|PASS|progression|227.2132|214.2829|-12.9303|-5.69%|
|migraphx_torchvision__resnet50i1|PASS|regression|95.2085|101.9294|6.7208|7.06%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1570.9128|1597.0356|26.1228|1.66%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5348.4391|5400.6239|52.1848|0.98%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9385.278|9805.354|420.076|4.48%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|145.221|164.447|19.226|13.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|248.9295|255.0201|6.0907|2.45%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|359.35|873.2191|513.8691|143.0%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|241.5726|290.8889|49.3163|20.41%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|433.1582|430.574|-2.5842|-0.6%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|666.712|774.3057|107.5937|16.14%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5108.9926|5147.0113|38.0187|0.74%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13811.8417|14052.1105|240.2688|1.74%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|23348.3371|24698.5967|1350.2596|5.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|407.4313|420.865|13.4337|3.3%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|793.5711|799.8437|6.2725|0.79%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1229.8504|1350.7594|120.909|9.83%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|750.3186|769.5631|19.2445|2.56%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1624.8661|1663.3878|38.5216|2.37%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3385.8468|3458.9687|73.1219|2.16%|

## 22 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convbert_Opset16_transformers|PASS|compilation|
|convbert_Opset17_transformers|PASS|compilation|
|model--distilgpt2-sd--aabidk|PASS|compilation|
|model--finetuned_distilgpt2_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|compilation|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|compilation|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|compilation|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedFalse_epochs1--yuhuizhang|PASS|compilation|
|model--gpt2--openai-community|PASS|compilation|
|model--gpt2-alpaca-gpt4--vicgalle|PASS|compilation|
|model--ia-detection-tiny-random-gptj--arincon|PASS|compilation|
|model--megatron-gpt2-345m--robowaifudev|PASS|compilation|
|model--my_awesome_gptj_model--anandshende|PASS|compilation|
|model--pythia-410mn-ntoxic--skrishna|PASS|compilation|
|model--pythia-70-m-finetuned--selinerdem|PASS|compilation|
|model--pythia-70m-toxicity-model--skrishna|PASS|compilation|
|model--tiny-gpt2--taufeeque|PASS|compilation|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|compilation|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|PASS|compilation|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|PASS|compilation|
|mvitv2_base|PASS|compilation|
|mvitv2_small|PASS|compilation|
|mvitv2_tiny|PASS|compilation|

## 13 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--flan-t5-large-samsum--oguuzhansahin|compilation|PASS|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|compilation|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|compilation|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|compilation|PASS|
|model--mobilebert-squadv2--aware-ai|compilation|PASS|
|model--mobilebert_cola--Alireza1044|compilation|PASS|
|model--mobilebert_mnli--Alireza1044|compilation|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|compilation|PASS|
|model--summarization-not-evaluated--autoevaluate|compilation|PASS|
|model--t5-base-fr-sum-cnndm--plguillou|compilation|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|compilation|PASS|
|t5-decoder-with-lm-head-12|compilation|PASS|
|t5-encoder-12|compilation|PASS|

