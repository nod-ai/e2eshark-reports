# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.297|2.0374|-0.2596|-11.3%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|17.7807|15.3351|-2.4456|-13.75%|
|migraphx_torchvision__inceptioni32|PASS|progression|24.9705|20.9856|-3.9849|-15.96%|
|migraphx_torchvision__resnet50i64|PASS|progression|18.7353|15.5928|-3.1425|-16.77%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|convnextv2_base.fcmae_ft_in22k_in1k_384|PASS|Numerics|
|ig_resnext101_32x48d_Opset17_timm|PASS|Numerics|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--bert-base-uncased-finetuned-squad--FabianWillner|PASS|Numerics|
|model--bert-finetuned-ner--CptBaas|PASS|Numerics|
|model--bert-l-squadv1.1-sl384--vuiseng9|PASS|Numerics|
|model--questionanswering-v4--abdalrahmanshahrour|PASS|Numerics|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|switchtransformersencoder_Opset17_transformers|PASS|Numerics|
|tf_efficientnetv2_l_in21k_Opset17_timm|PASS|Numerics|

## 33 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|alexnet_Opset17_torch_hub|Numerics|PASS|
|deit3_base_patch16_384_Opset17_timm|Numerics|PASS|
|eva_large_patch14_196.in22k_ft_in22k_in1k|Numerics|PASS|
|ig_resnext101_32x8d_Opset17_timm|Numerics|PASS|
|model--bert-finetuned-ner--buehlpa|Numerics|PASS|
|model--bert-finetuned-ner--ysharma|Numerics|PASS|
|model--distilbart-xsum-12-6--sshleifer|Numerics|PASS|
|model--distilbert-base-cased-finetuned-squad--monakth|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--avioo1|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--emre|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples--nazirzhumakhan|Numerics|PASS|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|compilation|PASS|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|compilation|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|compilation|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|compilation|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|compilation|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|compilation|PASS|
|model--questionansweringmodel--Shushant|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|compilation|PASS|
|regnet_x_32gf_Opset17_torch_hub|compilation|PASS|
|regnet_x_32gf_Opset18_torch_hub|compilation|PASS|
|regnetx_320_Opset16_timm|compilation|PASS|
|regnetx_320_Opset18_timm|compilation|PASS|
|resnet152_Opset17_timm|Numerics|PASS|
|swinv2_cr_small_224_Opset17_timm|Numerics|PASS|
|tf_efficientnetv2_m_in21ft1k_Opset16_timm|Numerics|PASS|
|tf_efficientnetv2_xl_in21ft1k_Opset16_timm|Numerics|PASS|
|vgg19_bn_Opset16_torch_hub|Numerics|PASS|
|wide_resnet50_2_Opset17_timm|Numerics|PASS|
|xception71_Opset16_timm|Numerics|PASS|
|xcit_medium_24_p16_224_dist_Opset17_timm|Numerics|PASS|

