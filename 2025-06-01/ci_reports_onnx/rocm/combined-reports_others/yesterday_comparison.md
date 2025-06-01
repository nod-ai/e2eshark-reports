# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.8591|2.297|0.4379|23.55%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|17.7093|17.7807|0.0714|0.4%|
|migraphx_torchvision__inceptioni32|PASS|within tol|24.8799|24.9705|0.0907|0.36%|
|migraphx_torchvision__resnet50i64|PASS|within tol|18.7923|18.7353|-0.0571|-0.3%|

## 22 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|alexnet_Opset17_torch_hub|PASS|Numerics|
|deit3_base_patch16_384_Opset17_timm|PASS|Numerics|
|eva_large_patch14_196.in22k_ft_in22k_in1k|PASS|Numerics|
|ig_resnext101_32x8d_Opset17_timm|PASS|Numerics|
|model--bert-finetuned-ner--buehlpa|PASS|Numerics|
|model--bert-finetuned-ner--ysharma|PASS|Numerics|
|model--distilbart-xsum-12-6--sshleifer|PASS|Numerics|
|model--distilbert-base-cased-finetuned-squad--monakth|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--avioo1|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-squad--emre|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--nazirzhumakhan|PASS|Numerics|
|model--questionansweringmodel--Shushant|PASS|Numerics|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|resnet152_Opset17_timm|PASS|Numerics|
|swinv2_cr_small_224_Opset17_timm|PASS|Numerics|
|tf_efficientnetv2_m_in21ft1k_Opset16_timm|PASS|Numerics|
|tf_efficientnetv2_xl_in21ft1k_Opset16_timm|PASS|Numerics|
|vgg19_bn_Opset16_torch_hub|PASS|Numerics|
|wide_resnet50_2_Opset17_timm|PASS|Numerics|
|xception71_Opset16_timm|PASS|Numerics|
|xcit_medium_24_p16_224_dist_Opset17_timm|PASS|Numerics|

## No Progressions Found

