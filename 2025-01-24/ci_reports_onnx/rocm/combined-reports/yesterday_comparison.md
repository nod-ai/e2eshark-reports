# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|24.3787|25.6579|1.2792|5.25%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.1828|44.2068|0.024|0.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|143.9395|176.8625|32.923|22.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.2473|16.0874|-0.1599|-0.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.9054|7.117|0.2116|3.06%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.1921|61.0407|-0.1514|-0.25%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.7751|32.8221|0.047|0.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.8635|54.9033|0.0398|0.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.4942|73.5072|0.013|0.02%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9604|12.0313|0.0709|0.59%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6263|12.7431|0.1167|0.92%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5553|19.5764|0.021|0.11%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|15.5314|12.7847|-2.7468|-17.69%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2286|13.2128|-0.0157|-0.12%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|22.4334|21.2132|-1.2203|-5.44%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.4521|67.3136|-0.1385|-0.21%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|101.6803|100.7408|-0.9395|-0.92%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|149.0102|148.7837|-0.2265|-0.15%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3348|14.3871|0.0523|0.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7637|16.7307|-0.033|-0.2%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|31.5935|26.2815|-5.312|-16.81%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.3161|19.2126|-0.1036|-0.54%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|31.3873|27.428|-3.9593|-12.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.8824|40.604|-0.2783|-0.68%|

## 65 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_384.in22k_ft_in22k_in1k|compiled_inference|compilation|
|cait_m36_384|compiled_inference|compilation|
|cait_m48_448|compiled_inference|compilation|
|coatnet_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in1k|PASS|compilation|
|convnext_large.fb_in22k_ft_in1k_384|PASS|compilation|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|PASS|compilation|
|convnext_large_mlp.clip_laion2b_ft_320|PASS|compilation|
|convnext_large_mlp.clip_laion2b_ft_soup_320|PASS|compilation|
|convnextv2_large.fcmae|PASS|compilation|
|convnextv2_large.fcmae_ft_in22k_in1k_384|PASS|compilation|
|deit3_base_patch16_384.fb_in1k|PASS|compilation|
|deit3_base_patch16_384.fb_in22k_ft_in1k|PASS|compilation|
|deit_base_distilled_patch16_384.fb_in1k|PASS|compilation|
|deit_base_patch16_384.fb_in1k|PASS|compilation|
|densenet201|Numerics|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|jx_nest_small|PASS|compilation|
|jx_nest_tiny|PASS|compilation|
|maxvit_base_tf_224.in1k|Numerics|compilation|
|maxvit_small_tf_224.in1k|Numerics|compilation|
|maxvit_tiny_tf_224.in1k|Numerics|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|migraphx_cadene__dpn92i1|compiled_inference|compilation|
|migraphx_cadene__inceptionv4i16|compiled_inference|compilation|
|migraphx_cadene__resnext101_64x4di1|compiled_inference|compilation|
|migraphx_cadene__resnext101_64x4di16|compiled_inference|compilation|
|migraphx_torchvision__densenet121i32|Numerics|compilation|
|migraphx_torchvision__inceptioni32|PASS|compilation|
|migraphx_torchvision__resnet50i1|Numerics|compilation|
|migraphx_torchvision__resnet50i64|Numerics|compilation|
|resmlp_big_24_224.fb_in1k|PASS|compilation|
|resmlp_big_24_224.fb_in22k_ft_in1k|PASS|compilation|
|resnest269e|PASS|compilation|
|tf_efficientnetv2_l.in1k|PASS|compilation|
|tf_efficientnetv2_l.in21k_ft_in1k|PASS|compilation|
|vit_base_patch16_384.augreg_in1k|PASS|compilation|
|vit_base_patch16_384.augreg_in21k_ft_in1k|PASS|compilation|
|vit_base_patch16_384.orig_in21k_ft_in1k|PASS|compilation|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|compilation|
|vit_base_patch16_clip_384.laion2b_ft_in1k|PASS|compilation|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|PASS|compilation|
|vit_base_patch16_clip_384.openai_ft_in1k|PASS|compilation|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|PASS|compilation|
|vit_base_patch8_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|compilation|
|xcit_large_24_p16_224|PASS|compilation|
|xcit_large_24_p16_224_dist|PASS|compilation|
|xcit_large_24_p16_384_dist|PASS|compilation|
|xcit_large_24_p8_224|PASS|compilation|
|xcit_large_24_p8_224_dist|PASS|compilation|
|xcit_medium_24_p16_224|PASS|compilation|
|xcit_medium_24_p16_224_dist|PASS|compilation|
|xcit_small_12_p8_224|PASS|compilation|
|xcit_small_12_p8_224_dist|PASS|compilation|
|xcit_small_24_p8_224|PASS|compilation|
|xcit_small_24_p8_224_dist|PASS|compilation|

## 146 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|AlexNet_vaiq_int8|compiled_inference|PASS|
|CSP-DarkNet_vaiq_int8|compiled_inference|PASS|
|ConvNeXt_vaiq_int8|compiled_inference|Numerics|
|DarkNet53_vaiq|compiled_inference|PASS|
|DarkNet53_vaiq_int8|compiled_inference|Numerics|
|DeepLabV3_resnet50_vaiq_int8|compiled_inference|PASS|
|DenseNet201_vaiq_int8|compiled_inference|PASS|
|EfficientNet_b0_vaiq|compiled_inference|Numerics|
|EfficientNet_b1_vaiq|compiled_inference|PASS|
|EfficientNet_b2_vaiq|compiled_inference|Numerics|
|EfficientNet_b3_vaiq|compiled_inference|Numerics|
|EfficientNet_b4_vaiq|compiled_inference|Numerics|
|EfficientNet_b5_vaiq|compiled_inference|PASS|
|EfficientNet_b6_vaiq|compiled_inference|PASS|
|EfficientNet_b7_vaiq|compiled_inference|Numerics|
|EfficientNet_v2_l_vaiq|compiled_inference|Numerics|
|EfficientNet_v2_m_vaiq|compiled_inference|Numerics|
|EfficientNet_v2_s_vaiq|compiled_inference|Numerics|
|EfficientNet_v2_s_vaiq_int8|compiled_inference|PASS|
|FCN_vaiq_int8|compiled_inference|PASS|
|GoogLeNet_vaiq|compiled_inference|PASS|
|GoogLeNet_vaiq_int8|compiled_inference|PASS|
|Inception_v3_vaiq|compiled_inference|PASS|
|Inception_v4_vaiq_int8|compiled_inference|PASS|
|LRASPP_vaiq_int8|compiled_inference|PASS|
|MNASNet_1_3_vaiq_int8|compiled_inference|PASS|
|MobileNetV2_vaiq|compiled_inference|PASS|
|MobileNetV3_large_vaiq|compiled_inference|PASS|
|MobileNetV3_small_vaiq|compiled_inference|Numerics|
|MobileNetV3_small_vaiq_int8|compiled_inference|Numerics|
|RAFT_vaiq_int8|compiled_inference|Numerics|
|RDN_pytorch_vaiq_int8|compiled_inference|Numerics|
|RRDB_ESRGAN_vaiq_int8|compiled_inference|Numerics|
|bat_resnext26ts.ch_in1k|compiled_inference|PASS|
|beit_base_patch16_224.in22k_ft_in22k_in1k|compiled_inference|PASS|
|beit_large_patch16_224.in22k_ft_in22k_in1k|compiled_inference|PASS|
|beit_large_patch16_384.in22k_ft_in22k_in1k|compiled_inference|PASS|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|compiled_inference|PASS|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|compiled_inference|PASS|
|botnet26t_256|compiled_inference|PASS|
|cait_s24_224|compiled_inference|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|compiled_inference|PASS|
|crossvit_15_dagger_240|compilation|PASS|
|gluon_xception65|compilation|PASS|
|migraphx_ORT__bert_base_cased_1|compiled_inference|PASS|
|migraphx_ORT__bert_base_uncased_1|compiled_inference|PASS|
|migraphx_ORT__bert_large_uncased_1|compiled_inference|PASS|
|migraphx_ORT__distilgpt2_1|compiled_inference|PASS|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|compiled_inference|Numerics|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|compiled_inference|Numerics|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|compiled_inference|Numerics|
|migraphx_bert__bert-large-uncased|compiled_inference|PASS|
|migraphx_huggingface-transformers__bert_mrpc8|compiled_inference|PASS|
|model--125M_GPTneo_reward_base--Myashka|compiled_inference|PASS|
|model--BART--Shubham09|compiled_inference|Numerics|
|model--BERT_summary--Shobhank-iiitdwd|compiled_inference|PASS|
|model--Bartlarge--Shubham09|compiled_inference|Numerics|
|model--Bert_Squad--johnjose223|compiled_inference|PASS|
|model--BioBERT-finetuned-ner-conll2003--ViktorDo|compiled_inference|PASS|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|compiled_inference|PASS|
|model--CodeGen-350M-Multi--xhyi|compiled_inference|PASS|
|model--Distil_BERT_Fine_Tune_3--satyamverma|compiled_inference|PASS|
|model--bert-finetuned-squad--kenyaari|compiled_inference|PASS|
|model--bert-finetuned-squad--krolis|compiled_inference|PASS|
|model--bert-finetuned-squad--lewtun|compiled_inference|PASS|
|model--bert-finetuned-squad--makdong|compiled_inference|PASS|
|model--bert-finetuned-squad--marcowong02|compiled_inference|PASS|
|model--bert-finetuned-squad--mkkc58|compiled_inference|PASS|
|model--bert-finetuned-squad--momtaz|compiled_inference|PASS|
|model--bert-finetuned-squad--mrp|compiled_inference|PASS|
|model--bert-finetuned-squad--mxalmeida|compiled_inference|PASS|
|model--bert-finetuned-squad--nenwa204|compiled_inference|PASS|
|model--bert-finetuned-squad--nickong|compiled_inference|PASS|
|model--bert-finetuned-squad--nightlighttw|compiled_inference|PASS|
|model--bert-finetuned-squad--ntu700t|compiled_inference|PASS|
|model--bert-finetuned-squad--peterhsu|compiled_inference|PASS|
|model--bert-finetuned-squad--qgrantq|compiled_inference|PASS|
|model--bert-finetuned-squad--rainanabul|compiled_inference|PASS|
|model--bert-finetuned-squad--raychang7|compiled_inference|PASS|
|model--bert-finetuned-squad--reza-aditya|compiled_inference|PASS|
|model--bert-finetuned-squad--rghosh8|compiled_inference|PASS|
|model--bert-finetuned-squad--robkayinto|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nachowdh|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nastorian|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nazirzhumakhan|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nhero|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nigeltc|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--rachtxxy|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--rh-jayson|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--saptarshidatta96|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--snehasunilnair|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--sukhendrasingh|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--sunilkumardash9|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--svenvonnatzmer|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--timokurtz|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--underoohcf|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--usmanazhar|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples-imdb--bharadwajkg|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples-practice--aki6022|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples-testcopy--federicopascual|compiled_inference|PASS|
|model--finetuning-sentiment-model-4000-samples--Manishkalra|compiled_inference|PASS|
|model--finetuning-sentiment-model-5000-samples--heyal|compiled_inference|PASS|
|model--finetuning-sentiment-model-5000-samples--mofyrt|compiled_inference|PASS|
|model--finetuning-sentiment-model-Test--Seema09|compiled_inference|PASS|
|model--finetuning-sentiment-model-Test--gokhalevikrant|compiled_inference|PASS|
|model--finetuning-sentiment-model-imdb--Panos|compiled_inference|PASS|
|model--finetuning-sentiment-model-imdb--Zhaohui|compiled_inference|PASS|
|model--finetuning-sentiment-model-imdb-train--dementor|compiled_inference|PASS|
|model--finetuning-sentiment-model-twitter-samples--Zhaohui|compiled_inference|PASS|
|model--first_finetuning-sentiment-model-3000-samples--Positroniy|compiled_inference|PASS|
|resnet200d_train_vaiq|compiled_inference|PASS|
|resnet200d_vaiq|compiled_inference|PASS|
|resnet26_test_vaiq|compiled_inference|PASS|
|resnet26_vaiq|compiled_inference|PASS|
|resnet26d_test_vaiq|compiled_inference|PASS|
|resnet26d_vaiq|compiled_inference|PASS|
|resnet26t_test_vaiq|compiled_inference|PASS|
|resnet26t_vaiq|compiled_inference|PASS|
|resnet32ts.ra2_in1k_train_vaiq|compiled_inference|PASS|
|resnet33ts.ra2_in1k_train_vaiq|compiled_inference|PASS|
|resnet34_test_vaiq|compiled_inference|PASS|
|resnet34_vaiq|compiled_inference|PASS|
|resnet34d_test_vaiq|compiled_inference|PASS|
|resnet34d_vaiq|compiled_inference|PASS|
|resnet50_gn_test_vaiq|compiled_inference|Numerics|
|resnet50_gn_vaiq|compiled_inference|PASS|
|resnet50_test_vaiq|compiled_inference|PASS|
|resnet50_vaiq|compiled_inference|PASS|
|resnet50d_test_vaiq|compiled_inference|PASS|
|resnet50d_vaiq|compiled_inference|PASS|
|resnet51q.ra2_in1k_train_vaiq|compiled_inference|PASS|
|resnet51q.ra2_in1k_vaiq|compiled_inference|PASS|
|resnet61q.ra2_in1k_train_vaiq|compiled_inference|PASS|
|resnet61q.ra2_in1k_vaiq|compiled_inference|PASS|
|resnetaa50_train_vaiq|compiled_inference|PASS|
|resnetaa50_vaiq|compiled_inference|PASS|
|resnetblur50_test_vaiq|compiled_inference|PASS|
|resnetblur50_vaiq|compiled_inference|PASS|
|resnetrs101_train_vaiq|compiled_inference|PASS|
|resnetrs101_vaiq|compiled_inference|Numerics|
|resnetrs152_train_vaiq|compiled_inference|PASS|
|resnetrs152_vaiq|compiled_inference|PASS|
|resnetrs200_train_vaiq|compiled_inference|PASS|
|resnetrs200_vaiq|compiled_inference|PASS|
|resnetrs50_train_vaiq|compiled_inference|PASS|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|PASS|

