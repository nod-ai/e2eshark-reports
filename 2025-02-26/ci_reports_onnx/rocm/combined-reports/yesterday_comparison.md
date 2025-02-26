# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.9361|110.2823|3.3462|3.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.9591|108.473|0.5139|0.48%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|458.7627|463.092|4.3293|0.94%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.4951|60.5896|1.0944|1.84%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.7969|61.3379|-0.459|-0.74%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|240.7266|277.5893|36.8627|15.31%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|35.6908|65.0404|29.3496|82.23%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.7201|2.0781|0.3581|20.82%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5617|19.0195|-0.5422|-2.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0784|7.1957|0.1173|1.66%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|28.3782|26.1418|-2.2364|-7.88%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.0961|4.8499|-0.2462|-4.83%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.8178|45.6462|1.8284|4.17%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|46.492|49.9384|3.4464|7.41%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.2084|16.9352|-1.2732|-6.99%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.0105|8.8183|2.8078|46.71%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8999|4.975|0.0751|1.53%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.3466|32.4597|0.1131|0.35%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.5609|53.187|-0.3738|-0.7%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|69.0177|69.1234|0.1058|0.15%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|12.1167|24.1552|12.0385|99.35%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|43.1761|12.3894|-30.7867|-71.31%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2727|19.9723|0.6996|3.63%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8005|12.9111|0.1107|0.86%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|295.4942|13.4679|-282.0263|-95.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.8686|20.8326|-0.0361|-0.17%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|237.7795|66.1142|-171.6653|-72.2%|
|migx_bench_bert-large-uncased_32_256|Numerics|within tol|98.0254|97.6084|-0.417|-0.43%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|138.1536|137.1133|-1.0403|-0.75%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4131|15.1235|0.7104|4.93%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.5652|16.745|0.1798|1.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.1823|25.1865|0.0043|0.02%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.1242|19.0025|-0.1217|-0.64%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.9861|26.648|-0.3381|-1.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.0936|38.8285|-0.2651|-0.68%|

## 18 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|deit3_large_patch16_224.fb_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in22k_in1k|PASS|Numerics|
|maxvit_rmlp_small_rw_224.sw_in1k|PASS|Numerics|
|maxvit_small_tf_512.in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_32_256|PASS|Numerics|
|model--TinyStories-33M--roneneldan|PASS|Numerics|
|model--bart-large-xsum--facebook|PASS|Numerics|
|model--bert-finetuned-squad--nightlighttw|PASS|Numerics|
|model--bert-finetuned-squad--vsrinivas|PASS|Numerics|
|model--distilbart-xsum-9-6--sshleifer|PASS|Numerics|
|model--marian-finetuned-kde4-cs2sv--ksaml|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--kbalde|PASS|Numerics|
|model--marian-finetuned-kde4-en-to-fr--ornil1|PASS|Numerics|
|model--smol_llama-81M-tied--BEE-spoke-data|PASS|Numerics|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|PASS|Numerics|
|twins_svt_base|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|

## 89 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_large_patch16_224.fb_in22k_ft_in1k|Numerics|PASS|
|dm_nfnet_f3.dm_in1k|Numerics|PASS|
|flexivit_base.1200ep_in1k|Numerics|PASS|
|flexivit_base.300ep_in1k|Numerics|PASS|
|flexivit_large.600ep_in1k|Numerics|PASS|
|focalnet_base_lrf.ms_in1k|Numerics|PASS|
|gcvit_base|Numerics|PASS|
|gcvit_tiny|compilation|PASS|
|gcvit_xtiny|compilation|PASS|
|gcvit_xxtiny|compilation|PASS|
|jx_nest_small|compilation|PASS|
|jx_nest_tiny|compilation|PASS|
|maxvit_base_tf_224.in1k|compilation|PASS|
|maxvit_small_tf_224.in1k|compilation|PASS|
|maxvit_tiny_tf_224.in1k|compilation|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|migx_bench_bert-large-uncased_1_256|Numerics|PASS|
|mixer_b16_224.goog_in21k_ft_in1k|Numerics|PASS|
|mobilevitv2_050|compilation|PASS|
|mobilevitv2_075|compilation|PASS|
|mobilevitv2_125|compilation|PASS|
|mobilevitv2_150|compilation|PASS|
|mobilevitv2_150_384_in22ft1k|compilation|PASS|
|mobilevitv2_150_in22ft1k|compilation|PASS|
|mobilevitv2_175|compilation|PASS|
|mobilevitv2_175_384_in22ft1k|compilation|PASS|
|mobilevitv2_175_in22ft1k|compilation|PASS|
|model--NLP_DEEP_2--Bictole|Numerics|PASS|
|model--SENATOR-Scaled--RANG012|Numerics|PASS|
|model--TinyStories-2Layers-33M--roneneldan|Numerics|PASS|
|model--Translation--shed-e|Numerics|PASS|
|model--bart-base-cnn--ainize|Numerics|PASS|
|model--bart-base-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--bart-base-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bart-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--bart-base-finetuned-squad--huxxx657|Numerics|PASS|
|model--bert-base-uncased-few-shot-k-256-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-squad--yaozeguo|Numerics|PASS|
|model--bert-l-squadv1.1-sl256--vuiseng9|Numerics|PASS|
|model--bert-large-uncased-whole-word-masking-squad2--deepset|Numerics|PASS|
|model--bert-medium-squad2-distilled--deepset|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--BillZou|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--aaraki|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad--laampt|Numerics|PASS|
|model--distilbert-base-uncased-finetuned-squad-colab--Adrian|Numerics|PASS|
|model--hebert-finetuned-hebrew-squad--tdklab|Numerics|PASS|
|model--hebrew_poetry-gpt_neo-small--Norod78|Numerics|PASS|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-es--tmobaggins|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--Thinkcru|Numerics|PASS|
|model--medium-mlm-imdb-target-imdb--muhtasham|Numerics|PASS|
|resmlp_big_24_224.fb_in1k|compilation|PASS|
|resmlp_big_24_224.fb_in22k_ft_in1k|compilation|PASS|
|resnest269e|compilation|PASS|
|tf_efficientnet_b6.ns_jft_in1k|Numerics|PASS|
|tf_efficientnetv2_l.in1k|compilation|PASS|
|tf_efficientnetv2_l.in21k_ft_in1k|compilation|PASS|
|twins_svt_large|Numerics|PASS|
|vit_base_patch16_384.augreg_in1k|compilation|PASS|
|vit_base_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_384.orig_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in1k|compilation|Numerics|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_384.openai_ft_in1k|compilation|PASS|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|compilation|PASS|
|vit_base_patch8_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|
|xcit_large_24_p16_224|compilation|PASS|
|xcit_large_24_p16_224_dist|compilation|PASS|
|xcit_large_24_p16_384_dist|compilation|PASS|
|xcit_large_24_p8_224|compilation|PASS|
|xcit_large_24_p8_224_dist|compilation|PASS|
|xcit_medium_24_p16_224|compilation|PASS|
|xcit_medium_24_p16_224_dist|compilation|PASS|
|xcit_nano_12_p16_384_dist|compilation|PASS|
|xcit_small_12_p16_384_dist|compilation|PASS|
|xcit_small_12_p8_224|compilation|PASS|
|xcit_small_12_p8_224_dist|compilation|PASS|
|xcit_small_24_p16_384_dist|compilation|PASS|
|xcit_small_24_p8_224|compilation|PASS|
|xcit_small_24_p8_224_dist|compilation|PASS|
|xcit_tiny_12_p8_384_dist|compilation|PASS|
|xcit_tiny_24_p8_384_dist|compilation|PASS|

