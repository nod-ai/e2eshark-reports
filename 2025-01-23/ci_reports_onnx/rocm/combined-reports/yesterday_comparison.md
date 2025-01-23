# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.9468|24.3787|-0.5681|-2.28%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.5895|44.1828|-0.4067|-0.91%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|148.5629|143.9395|-4.6233|-3.11%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|14.9002|16.2473|1.347|9.04%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.0389|6.9054|-1.1335|-14.1%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|68.8314|65.4871|-3.3443|-4.86%|
|migraphx_torchvision__inceptioni1|PASS|progression|66.4423|61.1921|-5.2502|-7.9%|
|migraphx_torchvision__inceptioni32|PASS|progression|107.9048|101.2842|-6.6206|-6.14%|
|migraphx_torchvision__resnet50i1|Numerics|progression|17.0446|15.8675|-1.1771|-6.91%|
|migraphx_torchvision__resnet50i64|Numerics|progression|155.2292|146.3296|-8.8995|-5.73%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.1684|32.7751|-0.3933|-1.19%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|55.5816|54.8635|-0.718|-1.29%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|74.6733|73.4942|-1.179|-1.58%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|12.6311|11.9604|-0.6707|-5.31%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2832|12.6263|-0.6569|-4.95%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|20.6758|19.5553|-1.1205|-5.42%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|13.5192|15.5314|2.0123|14.88%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|13.9891|13.2286|-0.7605|-5.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.1784|22.4334|0.255|1.15%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.3575|67.4521|-0.9054|-1.32%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|102.9122|101.6803|-1.2319|-1.2%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|151.7671|149.0102|-2.757|-1.82%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|15.2263|14.3348|-0.8915|-5.85%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.6851|16.7637|0.0786|0.47%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|27.0227|31.5935|4.5708|16.91%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|21.933|19.3161|-2.6169|-11.93%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|27.5509|31.3873|3.8364|13.92%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.9558|40.8824|-0.0734|-0.18%|

## 153 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|AlexNet_vaiq_int8|PASS|compiled_inference|
|CSP-DarkNet_vaiq_int8|PASS|compiled_inference|
|ConvNeXt_vaiq_int8|Numerics|compiled_inference|
|DarkNet53_vaiq|PASS|compiled_inference|
|DarkNet53_vaiq_int8|Numerics|compiled_inference|
|DeepLabV3_resnet50_vaiq_int8|PASS|compiled_inference|
|DenseNet201_vaiq_int8|PASS|compiled_inference|
|EfficientNet_b0_vaiq|Numerics|compiled_inference|
|EfficientNet_b1_vaiq|PASS|compiled_inference|
|EfficientNet_b2_vaiq|Numerics|compiled_inference|
|EfficientNet_b3_vaiq|Numerics|compiled_inference|
|EfficientNet_b4_vaiq|Numerics|compiled_inference|
|EfficientNet_b5_vaiq|PASS|compiled_inference|
|EfficientNet_b6_vaiq|PASS|compiled_inference|
|EfficientNet_b7_vaiq|Numerics|compiled_inference|
|EfficientNet_v2_l_vaiq|Numerics|compiled_inference|
|EfficientNet_v2_m_vaiq|Numerics|compiled_inference|
|EfficientNet_v2_s_vaiq|Numerics|compiled_inference|
|EfficientNet_v2_s_vaiq_int8|PASS|compiled_inference|
|FCN_vaiq_int8|PASS|compiled_inference|
|GoogLeNet_vaiq|PASS|compiled_inference|
|GoogLeNet_vaiq_int8|PASS|compiled_inference|
|Inception_v3_vaiq|PASS|compiled_inference|
|Inception_v4_vaiq_int8|PASS|compiled_inference|
|LRASPP_vaiq_int8|PASS|compiled_inference|
|MNASNet_1_3_vaiq_int8|PASS|compiled_inference|
|MobileNetV2_vaiq|PASS|compiled_inference|
|MobileNetV3_large_vaiq|PASS|compiled_inference|
|MobileNetV3_small_vaiq|Numerics|compiled_inference|
|MobileNetV3_small_vaiq_int8|Numerics|compiled_inference|
|RAFT_vaiq_int8|Numerics|compiled_inference|
|RDN_pytorch_vaiq_int8|Numerics|compiled_inference|
|RRDB_ESRGAN_vaiq_int8|Numerics|compiled_inference|
|bat_resnext26ts.ch_in1k|PASS|compiled_inference|
|beit_base_patch16_224.in22k_ft_in22k_in1k|PASS|compiled_inference|
|beit_base_patch16_384.in22k_ft_in22k_in1k|PASS|compiled_inference|
|beit_large_patch16_224.in22k_ft_in22k_in1k|PASS|compiled_inference|
|beit_large_patch16_384.in22k_ft_in22k_in1k|PASS|compiled_inference|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|PASS|compiled_inference|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|PASS|compiled_inference|
|botnet26t_256|PASS|compiled_inference|
|cait_m36_384|PASS|compiled_inference|
|cait_m48_448|PASS|compiled_inference|
|cait_s24_224|PASS|compiled_inference|
|convnext_xlarge.fb_in22k_ft_in1k_384|PASS|compiled_inference|
|crossvit_15_dagger_240|PASS|compilation|
|gluon_xception65|PASS|compilation|
|migraphx_ORT__bert_base_cased_1|PASS|compiled_inference|
|migraphx_ORT__bert_base_uncased_1|PASS|compiled_inference|
|migraphx_ORT__bert_large_uncased_1|PASS|compiled_inference|
|migraphx_ORT__distilgpt2_1|PASS|compiled_inference|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|compiled_inference|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|compiled_inference|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|compiled_inference|
|migraphx_bert__bert-large-uncased|PASS|compiled_inference|
|migraphx_cadene__dpn92i1|Numerics|compiled_inference|
|migraphx_cadene__inceptionv4i16|PASS|compiled_inference|
|migraphx_cadene__resnext101_64x4di1|Numerics|compiled_inference|
|migraphx_cadene__resnext101_64x4di16|Numerics|compiled_inference|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|compiled_inference|
|model--125M_GPTneo_reward_base--Myashka|PASS|compiled_inference|
|model--BART--Shubham09|Numerics|compiled_inference|
|model--BERT_summary--Shobhank-iiitdwd|PASS|compiled_inference|
|model--Bartlarge--Shubham09|Numerics|compiled_inference|
|model--Bert_Squad--johnjose223|PASS|compiled_inference|
|model--BioBERT-finetuned-ner-conll2003--ViktorDo|PASS|compiled_inference|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|PASS|compiled_inference|
|model--CodeGen-350M-Multi--xhyi|PASS|compiled_inference|
|model--Distil_BERT_Fine_Tune_3--satyamverma|PASS|compiled_inference|
|model--bert-finetuned-squad--kenyaari|PASS|compiled_inference|
|model--bert-finetuned-squad--krolis|PASS|compiled_inference|
|model--bert-finetuned-squad--lewtun|PASS|compiled_inference|
|model--bert-finetuned-squad--makdong|PASS|compiled_inference|
|model--bert-finetuned-squad--marcowong02|PASS|compiled_inference|
|model--bert-finetuned-squad--mkkc58|PASS|compiled_inference|
|model--bert-finetuned-squad--momtaz|PASS|compiled_inference|
|model--bert-finetuned-squad--mrp|PASS|compiled_inference|
|model--bert-finetuned-squad--mxalmeida|PASS|compiled_inference|
|model--bert-finetuned-squad--nenwa204|PASS|compiled_inference|
|model--bert-finetuned-squad--nickong|PASS|compiled_inference|
|model--bert-finetuned-squad--nightlighttw|PASS|compiled_inference|
|model--bert-finetuned-squad--ntu700t|PASS|compiled_inference|
|model--bert-finetuned-squad--peterhsu|PASS|compiled_inference|
|model--bert-finetuned-squad--qgrantq|PASS|compiled_inference|
|model--bert-finetuned-squad--rainanabul|PASS|compiled_inference|
|model--bert-finetuned-squad--raychang7|PASS|compiled_inference|
|model--bert-finetuned-squad--reza-aditya|PASS|compiled_inference|
|model--bert-finetuned-squad--rghosh8|PASS|compiled_inference|
|model--bert-finetuned-squad--robkayinto|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nachowdh|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nastorian|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nazirzhumakhan|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nhero|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nigeltc|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--rachtxxy|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--rh-jayson|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--saptarshidatta96|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--snehasunilnair|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--sukhendrasingh|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--sunilkumardash9|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--svenvonnatzmer|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--timokurtz|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--underoohcf|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--usmanazhar|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples-imdb--bharadwajkg|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples-practice--aki6022|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples-testcopy--federicopascual|PASS|compiled_inference|
|model--finetuning-sentiment-model-4000-samples--Manishkalra|PASS|compiled_inference|
|model--finetuning-sentiment-model-5000-samples--heyal|PASS|compiled_inference|
|model--finetuning-sentiment-model-5000-samples--mofyrt|PASS|compiled_inference|
|model--finetuning-sentiment-model-Test--Seema09|PASS|compiled_inference|
|model--finetuning-sentiment-model-Test--gokhalevikrant|PASS|compiled_inference|
|model--finetuning-sentiment-model-imdb--Panos|PASS|compiled_inference|
|model--finetuning-sentiment-model-imdb--Zhaohui|PASS|compiled_inference|
|model--finetuning-sentiment-model-imdb-train--dementor|PASS|compiled_inference|
|model--finetuning-sentiment-model-twitter-samples--Zhaohui|PASS|compiled_inference|
|model--first_finetuning-sentiment-model-3000-samples--Positroniy|PASS|compiled_inference|
|resnet200d_train_vaiq|PASS|compiled_inference|
|resnet200d_vaiq|PASS|compiled_inference|
|resnet26_test_vaiq|PASS|compiled_inference|
|resnet26_vaiq|PASS|compiled_inference|
|resnet26d_test_vaiq|PASS|compiled_inference|
|resnet26d_vaiq|PASS|compiled_inference|
|resnet26t_test_vaiq|PASS|compiled_inference|
|resnet26t_vaiq|PASS|compiled_inference|
|resnet32ts.ra2_in1k_train_vaiq|PASS|compiled_inference|
|resnet33ts.ra2_in1k_train_vaiq|PASS|compiled_inference|
|resnet34_test_vaiq|PASS|compiled_inference|
|resnet34_vaiq|PASS|compiled_inference|
|resnet34d_test_vaiq|PASS|compiled_inference|
|resnet34d_vaiq|PASS|compiled_inference|
|resnet50_gn_test_vaiq|Numerics|compiled_inference|
|resnet50_gn_vaiq|PASS|compiled_inference|
|resnet50_test_vaiq|PASS|compiled_inference|
|resnet50_vaiq|PASS|compiled_inference|
|resnet50d_test_vaiq|PASS|compiled_inference|
|resnet50d_vaiq|PASS|compiled_inference|
|resnet51q.ra2_in1k_train_vaiq|PASS|compiled_inference|
|resnet51q.ra2_in1k_vaiq|PASS|compiled_inference|
|resnet61q.ra2_in1k_train_vaiq|PASS|compiled_inference|
|resnet61q.ra2_in1k_vaiq|PASS|compiled_inference|
|resnetaa50_train_vaiq|PASS|compiled_inference|
|resnetaa50_vaiq|PASS|compiled_inference|
|resnetblur50_test_vaiq|PASS|compiled_inference|
|resnetblur50_vaiq|PASS|compiled_inference|
|resnetrs101_train_vaiq|PASS|compiled_inference|
|resnetrs101_vaiq|Numerics|compiled_inference|
|resnetrs152_train_vaiq|PASS|compiled_inference|
|resnetrs152_vaiq|PASS|compiled_inference|
|resnetrs200_train_vaiq|PASS|compiled_inference|
|resnetrs200_vaiq|PASS|compiled_inference|
|resnetrs50_train_vaiq|PASS|compiled_inference|
|tf_efficientnet_l2.ns_jft_in1k|PASS|Numerics|

## No Progressions Found

