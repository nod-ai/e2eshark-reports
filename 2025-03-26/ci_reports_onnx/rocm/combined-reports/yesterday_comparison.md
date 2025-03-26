# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.9947|1.8424|-0.1523|-7.64%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.7205|29.425|-0.2955|-0.99%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0127|27.959|-0.0537|-0.19%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.5409|20.5272|-0.0137|-0.07%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|model--bert-finetuned-squad--trjindal01|PASS|Numerics|

## 16 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|flexivit_base.300ep_in1k|Numerics|PASS|
|model--bart-large-xsum--facebook|Numerics|PASS|
|model--bart-mofe-rl-xsum--praf-choub|Numerics|PASS|
|model--bert-base-cased_conll2003-sm-first-ner--jordyvl|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-1024-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-ner--Cartinoe5930|Numerics|PASS|
|model--bert-finetuned-ner--ShadowTwin41|Numerics|PASS|
|model--bert-finetuned-squad--vsrinivas|Numerics|PASS|
|model--bert-finetuned-squad1--Ghost1|Numerics|PASS|
|model--bert-large-uncased-finetuned-ner--Jorgeutd|Numerics|PASS|
|model--deberta-v3-base-squad2--navteca|Numerics|PASS|
|model--finetuned_gpt2_sst2_negation0.05--yuhuizhang|Numerics|PASS|
|model--finetuning-sentiment-model-300-samples--Roshan777|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-512-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|swin_base_patch4_window12_384.ms_in22k_ft_in1k|Numerics|PASS|

